# Dubai-Real-estate

## Problem Statement

The real estate market in Dubai is highly dynamic, with property prices varying significantly based on factors such as location, property type, size, and developer. Investors, real estate agents, and policymakers require clear and data-driven insights to understand market trends, identify high-value areas, and make informed investment decisions.

However, raw housing datasets often contain inconsistencies, missing values, and unstructured information that make analysis difficult. Without proper data preparation and visualization, it is challenging to extract meaningful insights from the data.

This project aims to build an interactive Power BI dashboard that analyzes Dubai housing data and provides actionable insights into property prices, property distribution, and investment opportunities. By performing data cleaning, feature engineering, and visualization, the dashboard helps stakeholders easily explore real estate trends and make better decisions.

Project Workflow / Steps Involved
1. Data Collection

The dataset contains information about Dubai housing properties with attributes such as:

Location

Price

Bedrooms

Bathrooms

Size (Square Feet)

Property Type

Developer

Year Built

Furnishing Status

2. Data Cleaning and Preparation (Power Query)

The raw dataset was cleaned and transformed before analysis.

Key steps:

Removed duplicate records

Handled missing or incorrect values

Converted columns to correct data types

Numeric → price, size

Categorical → property type, location

Standardized column names for consistency

3. Feature Engineering

New calculated fields were created to enrich the dataset and support better analysis.

Price per Sqft

price_per_sqft = price / size

Property Age

property_age = 2025 - year_built

Listing Category

Properties were categorized based on price distribution:

Budget

Mid-Range

High-End

4. Data Modeling

The cleaned and enriched dataset was loaded into Power BI where:

Relationships between fields were defined

Measures and aggregations were created

Dataset optimized for visualization

5. Dashboard Development

An interactive Power BI dashboard was created containing multiple analytical visuals.

Key Metrics (KPI Cards)

Total Listings

Average Property Price

Average Property Size (sqft)

Highest Priced Property

Average Price per Sqft

Visual Analytics

The dashboard includes the following visuals:

Map Visualization

Displays average property prices by location.

Bar Chart

Comparison of prices across different property types.

Stacked Column Chart

Distribution of listings by number of bedrooms and property type.

Line Chart

Property price trends over time.

Treemap

Property listings by developer and property type.

6. Interactivity Features

To enhance user experience, the dashboard includes:

Filters (Slicers) for:

Bedrooms

Property Type

Furnishing Status

Price Range

Location

Dynamic tooltips showing price per sqft

Drill-down capabilities for deeper insights

7. Insights and Business Value

The dashboard enables users to:

Identify high-value real estate locations

Compare property prices across property types

Analyze price trends

Understand developer contributions to the market

Filter properties based on investment preferences

Tools Used

Power BI – Dashboard development and visualization

Power Query – Data cleaning and transformation

Excel / CSV Dataset – Data source
