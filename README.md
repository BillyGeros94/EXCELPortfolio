# Excel Portfolio

Welcome to my Excel Portfolio! This repository showcases a range of projects that demonstrate my expertise in data analysis, visualization, and reporting using Microsoft Excel. Each project covers different datasets and analysis techniques, providing practical insights and solutions for various business needs.

Contents

- **Project 1: Data Developer Salary**

    In this Excel project, I analyzed a dataset focused on data developer salaries. The dataset included key information such as the year, experience level, employment type, job title, salary in local currency, salary in USD, employee residence, remote work ratio, and company location and size. I performed data transformations to improve the readability of fields like experience level, employment type, and company size, making the dataset clearer and more suitable for visualization.

    After preparing the data, I created pivot tables and pivot charts to facilitate dynamic data analysis and visualization. I also incorporated slicers based on job title and company location to allow for more interactive filtering. The final dashboard features vertical bar charts that showcase the average salary by experience level, and employment type. Additionally, horizontal bar charts illustrate the average salary by company size, and a line chart tracks salary trends over the years. Vertical bar charts also provide insights into how the average salary has changed year by year for each experience level.

- **Project 2: Employee Performance Dashboard**

    This project contains three sheets: Employee Data, Monthly Sales Data, and Attendance Data. The dataset includes employee details such as name, role, and department, as well as monthly sales information like month, sales amount, and sales target. The attendance data includes fields for month, days worked, and total working days.

    In this project, I utilized the VLOOKUP function to extract employee names, roles, and departments from the Employee Data sheet to the Monthly Sales Data sheet. I then used functions such as SUMIF, AVERAGEIF, and COUNTIF to calculate total sales per employee, average sales per role, and the number of employees per department. I also computed the sales target achievement and formatted it as a percentage. To enhance data interpretation, I applied conditional formatting to highlight employees who did not meet their expected sales targets based on sales amount and target achievement.

    Additionally, I used VLOOKUP to extract employee names into the Attendance Data sheet. I applied SUMIF to calculate total sales per employee and used appropriate formulas to calculate daily sales for each employee. Conditional formatting was also used to provide insights into the number of days worked compared to total available days, and to compare employees based on their daily sales performance.

    Finally, I created a dashboard to visualize employee performance. It features a pie chart showcasing the distribution of employees by department, a horizontal bar chart displaying daily sales for each employee with an accompanying legend, a vertical bar chart illustrating average sales by role, and a line chart visualizing total sales for each employee.
  
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
