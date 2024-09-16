# Excel Portfolio

Welcome to my Excel Portfolio! This repository showcases a range of projects that demonstrate my expertise in data analysis, visualization, and reporting using Microsoft Excel. Each project covers different datasets and analysis techniques, providing practical insights and solutions for various business needs.

Contents

- **Project 1: Data Developer Salary**

    In this project, I created a Data Developer Salary Dashboard to provide insights into salary trends across different categories. The dataset included key information such as the 
    year, experience level, employment type, job title, salary in local currency, salary in USD, employee residence, remote work ratio, and company location and size. I performed data 
    transformations to improve the readability of fields like experience level, employment type, and company size, making the dataset clearer and more suitable for visualization.

    After preparing the data, I created pivot tables and pivot charts to facilitate dynamic data analysis and visualization. I also incorporated slicers based on job title and company 
    location to allow for more interactive filtering. The dashboard visualizes key aspects such as salary distribution by experience level, company size, employment type, and year. 
    Starting with experience level, it's clear that executive roles command the highest salaries, followed by senior-level, mid-level, and entry-level positions. This indicates a direct 
    correlation between experience and compensation, which is expected in most industries but particularly pronounced in data-related roles.

    The analysis by company size shows that larger companies tend to offer higher salaries compared to medium and small-sized firms. This is likely due to the increased resources, 
    budgets, and demands for data expertise in larger organizations. Interestingly, there is a consistent trend over the years, with average salaries increasing from 2020 to 2023. This 
    could be indicative of the growing importance of data roles and the rising demand for skilled professionals in this field, driving up compensation.

    When looking at employment type, full-time positions offer significantly higher average salaries than part-time, contract, and freelance positions, which typically come with less 
    job security and fewer benefits. This demonstrates the premium companies are willing to pay for full-time, dedicated employees. Additionally, the dashboard also breaks down salary 
    averages per year, reflecting an upward trend. This year-on-year increase highlights the overall growth of the data industry and suggests that it is becoming an even more integral 
    part of business operations, with companies willing to invest more in their data teams.

    Finally, the bottom section of the dashboard shows the yearly average salary per experience level, reinforcing the earlier finding that experience plays a critical role in 
    determining salary. Across all experience levels, there is an upward trend in compensation, particularly for senior and executive roles, which saw the most significant growth. This 
    suggests that as the demand for leadership in data development increases, so too does the willingness of companies to offer competitive salaries to attract top talent.

- **Project 2: Employee Performance Dashboard**

    This project contains three sheets: Employee Data, Monthly Sales Data, and Attendance Data. The dataset includes employee details such as name, role, and department, as well as 
    monthly sales information like month, sales amount, and sales target. The attendance data includes fields for month, days worked, and total working days.

    In this project, I utilized the VLOOKUP function to extract employee names, roles, and departments from the Employee Data sheet to the Monthly Sales Data sheet. I then used 
    functions such as SUMIF, AVERAGEIF, and COUNTIF to calculate total sales per employee, average sales per role, and the number of employees per department. I also computed the sales 
    target achievement and formatted it as a percentage. To enhance data interpretation, I applied conditional formatting to highlight employees who did not meet their expected sales 
    targets based on sales amount and target achievement.

    Additionally, I used VLOOKUP to extract employee names into the Attendance Data sheet. I applied SUMIF to calculate total sales per employee and used appropriate formulas to 
    calculate daily sales for each employee. Conditional formatting was also used to provide insights into the number of days worked compared to total available days, and to compare 
    employees based on their daily sales performance.

    Finally, I created a dashboard to visualize employee performance. I focused on visualizing the performance of employees in terms of sales and marketing metrics. The breakdown of 
    employees by department shows that the majority of the workforce, 75%, is in sales, while marketing accounts for the remaining 25%. This suggests that sales is the driving force of 
    the company’s revenue, with a much larger proportion of staff dedicated to direct customer interaction and closing deals compared to the marketing team, which likely plays more of a 
    supportive role in generating leads.

    In terms of daily sales performance, the data highlights the top performers. John Smith has the highest daily sales total at $4,772.73, followed by Michael Brown with $3,904.76, 
    then Emily Davis at $3,250.00, and Sara Johnson trailing with $2,736.84. The difference in daily sales indicates that John Smith significantly outperforms his peers.

    When analyzing the average sales per role, sales managers have the highest average at $52,500.00, which makes sense given their leadership and responsibility for overseeing larger 
    accounts and teams. Marketing executives also perform well with an average of $41,000.00, suggesting that while marketing staff are fewer in number, they play a crucial role in 
    driving higher-value deals. Sales executives and sales representatives have relatively lower averages at $29,250.00, but this could be expected given their focus on individual 
    clients and smaller deals.

    The total sales per employee graph emphasizes individual performance over time. John Smith leads significantly with total sales of $105,000.00, while Michael Brown follows with 
    $82,000.00. Emily Davis contributes $65,000.00 in total sales, and Sara Johnson, despite lower daily sales, totals $52,000.00. This suggests that while some employees consistently 
    perform better daily, the overall contribution to the company's revenue varies, potentially due to factors like deal size, client relationships, or time in role. The data implies 
    opportunities for improving lower performers’ strategies or giving them the support needed to match their higher-performing colleagues.
  
- **Project 3: IMDb Dataset**
  
   This Excel file contained raw and unorganized data from an IMDb movies database. First, I used the appropriate formula to combine all relevant data into a single column and then copied the values to a new sheet. Next, I utilized the Text to Columns feature to split the data into separate columns using the semicolon as a delimiter. After splitting the data, I formatted it into a table with proper headers.

   I then transformed each column to the correct data format, and cleaned and standardized the data to improve readability. This included columns like movie title, release year, genre, country, score, and director. Additionally, I filled in any missing values and corrected inaccurate information, ensuring the dataset was clean and ready for analysis.

- **Project 4: Sports Teams Valuations**

    This dataset was personally scraped using a Python script I developed to gather data on sports teams and their valuations from various Wikipedia pages. The dataset includes key information such as the team name, country, territory, value, revenue, operating income, sport, and league.

    I used pivot tables to manipulate and explore the data, allowing for detailed insights, and created pivot charts for visualization and analysis. The final product was a Sports Teams Valuations Dashboard, featuring line charts that showcase the average team valuation by country and the average operating income by sport. Additionally, the dashboard includes a vertical bar chart illustrating the average team valuation per sport and a horizontal bar chart providing insights into the average revenue by sport. To enhance interactivity, I added slicers for league, country, and territory, allowing for improved filtering and deeper insights into the data.

- **Project 5: Top 100 Companies Analysis**
  
   This dataset includes information on the top 100 companies by revenue, featuring data such as company name, industry, revenue (in million USD), revenue growth, number of employees, and headquarters location. In this project, I first copied the industries column to a new sheet and used the Remove Duplicates feature to keep only the unique values.

   I then applied functions such as SUMIF, COUNTIF, and AVERAGEIF to calculate key metrics, including total revenue per industry, total employees per industry, the number of companies per industry, and the average revenue growth by industry. To enhance data analysis, I employed various types of conditional formatting, including data bars, color scales, and icon sets.

  Finally, I used VLOOKUP on a separate sheet to extract data for selected companies from the main dataset, allowing for a more focused analysis of specific entries.

- **Project 6:** Under construction, coming shortly!

## Each project contains the following:

- **.xlsx File:** The main Excel workbook with data, analysis, and visualizations.
- **Data Source:** The underlying raw data (if applicable) used for analysis into the xlsx File.

If you have any questions or feedback, feel free to reach out!
