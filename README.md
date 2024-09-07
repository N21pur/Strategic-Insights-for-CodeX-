# Strategic-Insights-for-CodeX

Welcome to the repository for the 6th Resume Project Challenge at Codebasics! This project focuses on analyzing consumer survey responses to support CodeX, a German beverage company, in its expansion into the Indian energy drinks market. The data covers 10,000 respondents across 10 cities, with insights drawn from various demographics, consumption patterns, brand perceptions, and marketing preferences.

## Project Overview

The goal of this project is to analyze the survey data and provide actionable insights to drive marketing strategies, product development, and brand positioning for CodeX. By understanding consumer behavior and preferences, CodeX aims to enter the Indian market with a tailored product that resonates with local demands.

## Dataset Description

The project is based on three CSV files:

- **dim_respondents.csv**: Contains demographic information of respondents.
  - **Key Columns:**
    - `Respondent_ID`: Unique identifier for each respondent.
    - `Age_Group`: Categorized age groups (15-18, 19-30, etc.).
    - `Gender`: Gender of the respondent (Male, Female, Non-binary).
    - `City_ID`: City identifier.

- **dim_cities.csv**: Provides details about cities.
  - **Key Columns:**
    - `City_ID`: Unique city identifier.
    - `City`: Name of the city (Delhi, Mumbai, etc.).
    - `Tier`: Economic tier category of the city.

- **fact_survey_responses.csv**: Stores survey responses.
  - **Key Columns:**
    - `Response_ID`: Unique identifier for each response.
    - `Consume_frequency`: Frequency of energy drink consumption.
    - `Consume_time`: Time of energy drink consumption (before exercise, for work/study, etc.).
    - `Current_brands`: Brands currently consumed (CodeX, Cola-Coka, etc.).
    - `Price_range`: Preferred price range for energy drinks.
    - ...and many more responses covering consumption habits, brand preferences, and marketing channels.

## Tools & Technologies

- **SQL**: Used for data querying, exploration, and deriving insights.
- **Power BI**: Visualized key trends, demographics, and consumption patterns with interactive dashboards.
- **Excel**: Performed data cleaning, preprocessing, and analysis of survey results.

## Key Insights

- **Consumption Trends**: Identified which demographic groups consume energy drinks the most and when they prefer to do so.
- **Brand Awareness**: Analyzed awareness and perception of CodeX among respondents, revealing insights on brand positioning.
- **Marketing Channels**: Found the most effective marketing channels for reaching target audiences.
- **Price Sensitivity**: Explored pricing preferences to optimize product pricing for the Indian market.

## Visualizations

The Power BI dashboards provide an in-depth view of:

- **Demographics**: Age group, gender, and city breakdowns.
- **Consumption Behavior**: Frequency, time, and reasons for consuming energy drinks.
- **Brand Preferences**: Preferred brands and reasons for choosing them.
- **Marketing Insights**: Channels where consumers frequently encounter energy drink advertisements.

## How to Use

You can explore the code and data in this repository to replicate the analysis and gain further insights. The SQL queries and Power BI files are available for detailed exploration.

## Acknowledgements

A special thank you to Dhaval Patel and Hemanand Vadivel for their guidance and support throughout this project. Their insights have been instrumental in delivering this analysis with confidence.

---

Feel free to explore the repository, review the data and analyses, and use the provided tools to generate additional insights.

Happy Analyzing!
