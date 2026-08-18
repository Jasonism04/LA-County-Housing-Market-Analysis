
# Los Angeles County Housing Market Analysis (2022--2025)

An exploratory data analysis project examining recent home-price trends
and housing supply--demand conditions in Los Angeles County using
monthly Redfin county-level housing data.

## Project Overview

This project analyzes 48 monthly observations from January 2022 through
December 2025. The goal is to understand how Los Angeles County home
prices changed and how those changes were related to housing supply,
sales activity, and market speed.

## Questions

1.  How did home prices change from 2022 to 2025?
2.  How did housing supply change?
3.  How did housing demand and market activity change?
4.  What was the relationship between home prices, supply, and demand?

## Tools

-   Python
-   Pandas
-   NumPy
-   Matplotlib
-   Seaborn
-   Jupyter Notebook

## Dataset

The analysis uses monthly Redfin county-level housing market data and
filters the dataset to **Los Angeles County, California**.

Key variables include:

-   Median sale price
-   Homes sold
-   Active listings
-   New listings
-   Pending sales
-   Median days on market

## Analysis Workflow

The notebook:

1.  Imports and inspects the raw housing dataset.
2.  Filters observations to Los Angeles County.
3.  Checks key variables for missing values.
4.  Creates annual summaries from monthly observations.
5.  Analyzes price, supply, demand, and market-activity trends.
6.  Calculates year-over-year changes and correlations among major
    housing indicators.
7.  Visualizes the results and summarizes the main findings.

## Key Findings

-   **Home prices increased overall, but growth was uneven.** Median
    sale price rose from **\$825,000 in January 2022 to \$890,000 in
    December 2025**, a cumulative increase of approximately **7.88%**.
-   **Housing inventory expanded by 2025.** Average active listings
    increased from approximately **18,823 in 2022 to 23,101 in 2025**,
    an increase of about **22.73%**.
-   **Sales activity remained below 2022 levels.** Total homes sold
    declined from **61,106 in 2022 to 49,981 in 2025**, a decrease of
    approximately **18.21%**.
-   **Homes took longer to sell.** Average days on market increased from
    approximately **36.6 days in 2022 to 49.9 days in 2025**.
-   The relationship between inventory growth and price growth was not
    simply inverse, suggesting that Los Angeles County housing prices
    were influenced by multiple market forces rather than supply alone.

## Limitations

-   The dataset covers four years, so the project focuses on recent
    trends rather than long-term housing cycles.
-   County-level data can hide differences among individual cities and
    neighborhoods.
-   Correlations describe statistical relationships but do not establish
    causation.

## Conclusion

Los Angeles County experienced modest overall home-price growth between
2022 and 2025 despite weaker sales activity and a later recovery in
housing inventory. By 2025, buyers had more listings to choose from and
homes generally remained on the market longer, while prices still
finished above early-2022 levels. The results highlight the importance
of evaluating price, supply, demand, and market-speed indicators
together when assessing housing-market conditions.

## Repository Files

-   `LA_County_Housing_Analysis_2022_2025.ipynb` --- complete analysis
    notebook
-   `redfin_county_housing_2022_2025.csv` --- dataset used in the
    analysis
