# Cohort analysis. App Business Metrics Analysis.

### Coding with Yandex.Practicum: Here, I keep the outcomes of my learning and creative experiments.

In this project, we will explore data from a marketing analytics perspective for the entertainment application Procrastinate Pro+. Despite significant investments in advertising, the company has been incurring losses over the past few months. Our task is to understand the reasons behind this and help the company turn a profit.

**We have data on users acquired from May 1st to October 27th, 2019, including:**

- Server logs with data on their visits.
- Data on their purchases during this period.
- Advertising expenses.

**We will investigate:**

- Where users come from and what devices they use.
- The cost of acquiring users from different advertising channels.
- How much revenue each customer generates.
- When the customer acquisition costs pay off.
- Factors hindering customer acquisition.

**Step 1. Load Data and Prepare for Analysis**

Load data on visits, orders, and advertising expenses from CSV files into variables. The file paths are as follows:

1. /datasets/visits_info_short.csv
2. /datasets/orders_info_short.csv
3. /datasets/costs_info_short.csv

Examine the data and perform preprocessing. Are there any missing values or duplicates in the data? Ensure that data types in all columns match the values stored in them. Pay special attention to columns with dates and times.

**Step 2. Define Functions for Calculating and Analyzing LTV, ROI, Retention, and Conversion**

**These functions will calculate metric values:**

- get_profiles() for creating user profiles.
- get_retention() for calculating Retention Rate.
- get_conversion() for calculating conversion.
- get_ltv() for calculating LTV.

**These functions will create graphs:**

- filter_data() for smoothing data.
- plot_retention() for plotting the Retention Rate graph.
- plot_conversion() for plotting the conversion graph.
- plot_ltv_roi() for visualizing LTV and ROI.

**Step 3. Exploratory Data Analysis**

**Create user profiles. Determine the minimum and maximum user acquisition dates.**
- Find out from which countries users come to the application and which country has the highest percentage of paying users. Create a table showing the number of users and the share of paying users from each country.
- Learn about the devices used by customers and which devices are preferred by paying users. Create a table showing the number of users and the share of paying users for each device.
- Study the advertising sources for user acquisition and identify the channels from which the most paying users come. Create a table showing the number of users and the share of paying users for each acquisition channel.
- After each step, draw conclusions.

**Step 4. Marketing**

- Calculate the total marketing expenses.
- Determine how expenses are distributed among advertising sources, i.e., how much money was spent on each source.
- Create a visualization of the dynamics of expense changes over time (weekly and monthly) for each source. Try to reflect this on one graph.
- Find out the average cost of acquiring one user (CAC) from each source. Use user profiles.
- Write intermediate conclusions.

**Step 5. Assess the Effectiveness of Advertising**

- Using LTV, ROI, and CAC graphs, analyze the effectiveness of advertising. Assume that November 1, 2019, is the date, and the business plan states that users should pay off no later than two weeks after acquisition. Determine the need to include organic users in the analysis independently.
- Analyze the profitability of advertising with LTV, ROI, and CAC graphs, as well as the dynamics of LTV, CAC, and ROI.
- Check user conversion rates and its dynamics. Do the same with user retention. Create and study conversion and retention graphs.
- Analyze the profitability of advertising with a breakdown by devices. Create LTV and ROI graphs, as well as the dynamics of LTV, CAC, and ROI.
- Analyze the profitability of advertising with a breakdown by countries. Create LTV and ROI graphs, as well as the dynamics of LTV, CAC, and ROI.
- Analyze the profitability of advertising with a breakdown by advertising channels. Create LTV and ROI graphs, as well as the dynamics of LTV, CAC, and ROI.

**Answer such questions:**

1. Is advertising aimed at user acquisition paying off overall?
2. What devices, countries, and advertising channels may negatively impact advertising ROI?
3. What could be the causes of profitability issues?
4. Write a conclusion, describe possible reasons for the identified problems, and provide intermediate recommendations for the marketing department.

**Step 6. Write Conclusions**

- Identify the reasons for the ineffectiveness of user acquisition.
- Formulate recommendations for the marketing department.
