# Data Dictionary and Analysis Methodology

## Dataset overview

The project uses the public Marketing Campaign dataset linked in the repository README. The analyzed dataset contains 22,029 records and 16 columns.

## Data dictionary

| Column | Description |
|---|---|
| Campaign_ID | Unique identifier for a campaign record |
| Company | Company associated with the campaign |
| Campaign_Type | Type or category of marketing campaign |
| Target_Audience | Intended audience for the campaign |
| Duration | Recorded campaign duration |
| Channel_Used | Marketing channel used |
| Conversion_Rate | Recorded conversion rate |
| Acquisition_Cost | Recorded cost of acquiring customers |
| ROI | Return on investment recorded for the campaign |
| Location | Geographic location associated with the campaign |
| Language | Language associated with the campaign |
| Clicks | Number of recorded clicks |
| Impressions | Number of recorded impressions |
| Engagement_Score | Recorded campaign engagement score |
| Customer_Segment | Customer segment associated with the campaign |
| Date | Campaign date |

Column descriptions are based on the field names and the analysis performed in the notebook. The dataset source does not provide a detailed formal schema in this project, so units, scoring scales, and calculation formulas should not be assumed where they are not explicitly documented.

## Analysis methodology

1. **Load:** Read the source CSV into a Pandas DataFrame.
2. **Inspect:** Review sample records, dataset dimensions, column names, data types, descriptive statistics, and category counts.
3. **Validate:** Check missing values and inspect key fields and their distinct values.
4. **Explore:** Compare conversion rate, acquisition cost, ROI, and engagement across campaign types, channels, audience groups, customer segments, languages, dates, and locations.
5. **Visualize:** Use Matplotlib and Seaborn charts to explore distributions, group comparisons, relationships, and time patterns.
6. **Interpret:** Summarize observed patterns and translate them into practical campaign evaluation and optimization recommendations.

## Interpretation and limitations

- Findings describe patterns in this dataset; they do not establish that a campaign attribute caused an outcome.
- Engagement should not be treated as a substitute for conversion or ROI. The notebook reports a very weak correlation (approximately 0.01) between Engagement Score and Conversion Rate.
- The dataset's units, business definitions, and metric calculation methods are not fully specified in the project source. Interpret metric values in that context.
- Results may not generalize to other companies, markets, or time periods.
