# Cyclistic Bike-share

## Table of Contents
- [Project Overview](#project-overview)
- [Data Overview](#data-overview)
- [Project Objectives](#project-objectives)
- [Tools Used](#tools-used)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Key Insights](#key-insights)
- [Recommendations](#recommendations)
- [Data Limitations](#data-limitations)

### Project Overview
Cyclistic is a fictional Chicago-based bike-share company launched in 2016. Operates 5,800 geo-tracked cycles with 692 stations across Chicago.

Pricing Plans:
- Single Ride Pass
- Full Day Pass
- Annual Memberships

In this project, customers who purchase Single Ride Passes or Full Day Passes are classified as **Casual Riders**, while those with annual memberships are classified as **Members**.

This project analyses Cyclistic bike-share data using Excel Pivot Tables and Power Query. The goal is to understand how casual riders and annual members use the service differently and provide actionable insights to increase annual memberships.

### Data Overview:
- Source: Data was provided by a real company for educational, research, and analysis purposes.
- Period: May 2023 to April 2024.
- Volume: 5.7 million rows of data.
- Format : .csv

### Project Objectives:
- Understand usage patterns of casual riders vs. annual members.
- Identify high-level trends in ride behavior (e.g., duration, day/time, bike type).
- Provide marketing strategies to convert casual riders into annual members.

### Tools Used:
- Power Query : For cleaning, transforming and consolidating raw data.
- Excel Pivot Tables : For creating summaries and charts.
- Excel Charts : For visualizing insights (e.g., bike type usage, average ride duration).

### Data Cleaning and Preparation
In the initial data preparation phase, we performed the following task:
1. Data loading and inspections
2. Handling missing values
3. Data cleaning and formatting

### Exploratory Data Analysis
EDA involves exploring the data to answer the key questions such as,
- How annual members and casual riders use Cyclistic bikes differently.
- Identify key insights to drive marketing strategies for converting casual riders.
- Provide actionable recommendations for improving ridership and revenue.

### Project Structure
- data/: Contains a sample cleaned dataset for demonstration purposes and **data_dictionary.md** file explains the structure and meaning of the dataset’s columns.
- visuals/: Includes charts created using Excel.
- README.md: Provides project overview and instructions.
- LICENSE: Contains licensing terms.

### Key Insights:
The analysis key insights are summarised as follows : 
1. Bike Type Usage:
    - Casual riders prefer classic and electric bikes.
    - Members have balanced usage across all bike types.
2. Ride Duration:
    - Casual riders take longer rides, especially on weekends.
    - Members tend to use bikes for shorter, consistent weekday rides.
3. Monthly Trends:
    - Summer months show peak usage for both casual riders and members.

### Recommendations:
Base on the analysis, the following actions are recommended : 

1. Collaborate with Local Influencers:
    - Hire content creators to promote bike-share trips around Chicago.
2. Launch Weekend Membership Plans:
    - Offer short-term plans targeting casual riders.
3. Marketing Campaigns for Summer:
    - Promote annual memberships during peak usage months.

### Data Limitations
- Purpose of the ride is not available.
- Pricing structure is not included, limiting cost-benefit analysis.
- Fleet distribution and docking station context are missing.
- No demographic data for users to segment effectively.
    #### Suggestions:
    - Conduct surveys to collect ride purpose.
    - Incorporate pricing and station data into future datasets.
    - Explore demographic data collection for better user targeting.


### How to Use
- Data Cleaning: Open cleaned_data.xlsx to view the prepared dataset, processed using Power Query.
- Analysis: Explore pivot tables and charts in pivot_table_analysis.xlsx to review key insights.
- Visualizations: View .png files in the visuals/ directory for each chart.

### License:
This project is licensed under the MIT License.


