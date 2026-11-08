# Marketing Campaign Performance Insights

> A data analytics project exploring campaign effectiveness, customer engagement, acquisition costs, and return on investment (ROI) using Python.

## Project Overview

This project analyzes **22,029 marketing campaign records across 16 columns** to understand how campaign performance varies by marketing type, channel, customer segment, language, company, and location.

The goal is to turn campaign data into practical business insights that can support better marketing decisions, campaign optimization, and budget allocation.

## Business Questions

- Which marketing channels and campaign types generate stronger engagement and conversion?
- How do acquisition costs relate to campaign ROI?
- Which customer segments perform best across different languages?
- How does campaign performance vary by company and location?
- What patterns appear in campaign activity and engagement over time?

## Tools & Technologies

- **Python** – analysis and data processing
- **Pandas, NumPy** – data cleaning, manipulation, and aggregation
- **Matplotlib, Seaborn** – exploratory data analysis and visualization
- **Jupyter Notebook** – analysis workflow and documentation

## Analysis Workflow

1. Loaded the campaign dataset into a Pandas DataFrame.
2. Reviewed dataset structure, data types, descriptive statistics, and category distributions.
3. Explored campaign performance across channels, campaign types, and companies.
4. Analyzed customer segments and language-level conversion patterns.
5. Examined time-based and geographic performance trends.
6. Developed business insights and recommendations from the analysis.

## Selected Findings

- Social Media campaigns show relatively high engagement in the channel comparison.
- Conversion rates are broadly similar across the marketing channels examined.
- Engagement Score and Conversion Rate have a very weak correlation (**0.01**) in this dataset.
- Campaign performance differs across customer segments and target audiences.
- Average conversion rate is highest for English-language campaigns in the language comparison.
- Acquisition Cost and ROI show a broad pattern in which higher-cost campaigns tend to have lower maximum ROI, although individual campaign results vary.

## Business Recommendations

- Evaluate campaigns using ROI and conversion rate alongside engagement metrics.
- Identify high-performing audience segments and tailor campaigns to their needs.
- Compare acquisition costs across channels and locations before reallocating budgets.
- Continue monitoring channel performance rather than relying on engagement alone.
- Review underperforming campaigns regularly and test improvements using measurable outcomes.

## Repository Contents

| File | Description |
|---|---|
| `Marketing_Campaign_Performance_Insights.ipynb` | Main notebook containing the analysis, code, visualizations, and findings |
| `Marketing_Campaign_Performance_Insights.html` | Browser-friendly exported version of the notebook |
| `requirements.txt` | Python libraries required to run the analysis |

## Dataset

The project uses the Marketing Campaign dataset published by ArchanaInsights:

[Download the dataset (CSV)](https://raw.githubusercontent.com/ArchanaInsights/Datasets/main/marketing_campaign.csv)

The dataset includes campaign identifiers, company, campaign type, target audience, duration, channel, conversion rate, acquisition cost, ROI, location, language, clicks, impressions, engagement score, customer segment, and date.

## Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/shanmukhkoyya/Marketing-Campaign-Performance-Insights.git
   cd Marketing-Campaign-Performance-Insights
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Launch Jupyter:
   ```bash
   jupyter notebook
   ```
4. Open `Marketing_Campaign_Performance_Insights.ipynb` and run the cells.

## Author

**Shanmukh Koyya**  
[GitHub Profile](https://github.com/shanmukhkoyya)

---

*This project demonstrates practical skills in Python-based data analysis, exploratory data analysis, visualization, and translating findings into business recommendations.*
