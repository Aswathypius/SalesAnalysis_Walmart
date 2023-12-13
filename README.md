# SalesAnalysis_Walmart

This is my first guided SQL project. 

### Table of contents

-[Project overview](#project-overview)

-[Data source](#data-source)

-[Tool used](#tool-used)

-[Approaches used](#approaches-used)

-[Findings](#findings)

-[Recommendations](#recommendations)

### Project overview

The aim of this project is to examine Walmart sales data in order to comprehend top-performing branches and products, trends in product sales, and consumer behavior. The goal is to investigate ways to optimize and enhance sales methods.

### Data source

This project uses only one dataset.The dataset was obtained from the Kaggle Walmart Sales Forecasting Competition.

### Tool used
- MySQL is used for data cleaning and exploratory data anlysis.

### Approaches used

1. Data cleaning: In this initial step, data is inspected to ensure that missing and NULL values are found, and data replacement techniques are applied to replace any such values.

    - Build a database.
    - Create table and insert the data.
    - Since it was specified NOT NULL for every field when table created, null values are filtered out and there aren't any in the database.
  
2. Addition of new columns:

   - time_of_day - to give insight into sales in the morning, afternoon, and evening.
   - day_name - to give insight into sales in the week days (Mon, Tue, Wed, Thur, Fri).
   - month_name - to give insight into sales in the months Jan, Feb and Mar.

3. Exploratory data analysis: EDA is done to answer key questions in terms of analysing the product, sales and customers such as:

   - How many unique product lines does the data have?
   - Which month has the highest sales?
   - Which customer type buys the most?

### Findings

- The fashion accessories is the most selling product line.
- Food and beverages have the largest revenue.
- Naypyitaw is the city which has the largest revenue.
- Fashion accessories are the most common among females while it is health and beauty among males.
- The highest average rating is for food and beverages.
- Member brought the highest gross income.

### Recommendations

- As fashion accessories is the most selling product line and it is the most common among females, invest more in it.
- Focus more on Naypyitaw city as it has generated largest revenue.
- Invest in marketing and promotions on food and beverages as it have the largest revenue and highest average rating.
- Some special offers can be given to member customers as they brought in highest gross income. 
  
[Link to guided project](https://www.youtube.com/watch?v=Qr1Go2gP8fo)
