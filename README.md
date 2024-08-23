<h1>Walmart Sales Data Analysis Project</h1>

<h2>Description</h2>
This project analyzes Walmart sales data from the Kaggle Sales Forecasting Competition to identify top-performing branches and products, as well as sales trends and customer behavior. By leveraging historical sales data from 45 Walmart stores across various regions, the analysis aims to enhance sales strategies and optimize performance. The dataset includes department-level sales information, along with the impact of holiday markdown events, allowing for a comprehensive understanding of how these factors influence sales across different departments.
<br />
<br />

In my Walmart Sales Data Analysis project, I created a detailed sales table and enhanced the dataset by incorporating new features such as time_of_day, day_name, and month_name using SQL functions and CASE statements. This allowed for a more granular analysis of sales patterns. I identified key trends, including the most common payment methods, top-selling product lines, and monthly revenue trends. Additionally, I analyzed branch and city performance by calculating total revenue and identifying high-performing branches. By assessing customer feedback and average ratings across different times and locations, I provided insights that can help optimize marketing strategies and improve customer experience, showcasing my strong skills in data analysis and SQL.
<br />


<h2>Methods Used</h2>

- <b>Data Wrangling:</b>
In the first step of my project, I inspected the data to identify any NULL or missing values.
I implemented various data replacement methods to ensure that all gaps in the dataset were addressed, maintaining data integrity for the analysis.
  - Tasks Completed:
    - Build a database
    - Create table and insert the data.
    - Select columns with null values in them. There are no null values in our database as in creating the tables, we set NOT NULL for each field, hence null values are filtered out.
- <b>Feature Engineering:</b>
In this phase of the project, I generated new columns from the existing data to enhance my analysis. 
  - Tasks Completed:
    - Add a column named time_of_day to categorize sales into Morning, Afternoon, and Evening, which provided insights into when most sales occur throughout the day.
    - Create a day_name column to extract the day of the week for each transaction, allowing me to identify which days are the busiest for each branch.
    - Introduce a month_name column to extract the months from the transaction dates, helping me determine which months yield the highest sales and profits.
- <b>Exploratory Data Analysis (EDA):</b>
During the exploratory data analysis phase, I focused on answering the key questions and objectives outlined for the project.  I analyzed various metrics, such as sales performance across different branches, product categories, and time frames. By visualizing the data through charts and graphs, I gained valuable insights that guided my understanding of customer behavior and sales trends, ultimately informing strategies for optimizing sales performance.
  - Tasks Completed:
    - Examinine the dataset to uncover patterns, trends, and relationships within the data.
    - Analyze various metrics, such as sales performance across different branches, product categories, and time frames.
    - Gain valuable insights that guided my understanding of customer behavior and sales trends, ultimately providing opportunities to develop strategies for optimizing sales performance.

<h2>Business Questions with Answers</h2>

- <b>Generic Questions</b>
  - How many unique cities does the data have?
    - 3
  - In which city is each branch?
    - Yagnon = Branch A
    - Naypyitaw = Branch C
    - Mandalay = Branch B
   
- <b>Product Questions</b>
  - How many unique product lines does the data have?
    - 6
  - What is the most common payment method?
    - Cash, with 344 transactions
  - What is the most selling product line?
    - Fashion Accessories, with 178 products sold.
  - What is the total revenue by month?
    - January = $116,292
    - March = $108,867
    - February = $95,727
  - What month had the largest COGS (Costs of Goods Sold)?
    - January = $110,754
  - What product line had the largest revenue?
    - Food and Beverages = $56,145
  - What is the city with the largest revenue?
    - Naypyitaw = $110,491
  - What product line had the largest VAT (Value Added Tax)?
    - Home and Lifestyle = Average VAT of 16.03
  - Which branch sold more products than average product sold?
    - Branch A = 1849 products sold
  - What is the most common product line by gender?
    - Female: Fashion and Accessories = 96
    - Male: Health and Beauty = 88
  - What is the average rating of each product line?
    - Food and Beverages = 7.11 
    - Fashion Accessories = 7.03
    - Health and Beauty = 6.98
    - Electronic Accessories = 6.91
    - Sports and Travel = 6.86
    - Home and Lifestyle = 6.84

- <b>Sales Questions</b>
  - Number of sales made in each time of the day per weekday?
    - Monday:
      -   Morning: 20
      -   Afternoon: 48
      -   Evening: 56
    - Tuesday:
      -   Morning: 36
      -   Afternoon: 53
      -   Evening: 69
    - Wednesday:
      -   Morning: 22
      -   Afternoon: 61
      -   Evening: 58
    - Thursday:
      -   Morning: 33
      -   Afternoon: 49
      -   Evening: 56
    -  Friday:
      -   Morning: 29
      -   Afternoon: 58
      -   Evening: 51
  - Which of the customer types brings the most revenue?
    - Member = $163,625
  - Which city has the largest tax percent/ VAT (Value Added Tax)?
    - Naypyitaw = Average VAT of 16.09
  - Which customer type pays the most in VAT?
    - Member = Average VAT 15.61
  
- <b>Customer Questions</b>
  - How many unique customer types does the data have?
    - 2, Normal and Member
  - How many unique payment methods does the data have?
    - 3, Credit Card, E-Wallet, Cash
  - Which customer type buys the most?
    - Member = 499
  - What is the gender of most of the customers?
    - Male = 498
  - What is the gender distribution per branch?
    - Branch A:
      - Male: 179
      - Female: 160
    - Branch B:
      - Male: 169
      - Female: 160
    - Branch C:
      - Male: 150
      - Female: 177
  - Which time of the day do customers give most ratings?
    - Afternoon, giving an average rating of 7.02
  - Which time of the day do customers give most ratings per branch?
    - Evening, with an average rating of 7.10
  - Which day of the week has the best average ratings?
    - Monday with an average rating of 7.13
  - Which day of the week has the best average ratings per branch?
    - Saturday with an average rating per branch of 7.23
  
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
