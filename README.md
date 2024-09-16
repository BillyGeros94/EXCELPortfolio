# Excel Portfolio

Welcome to my Excel Portfolio! This repository showcases a range of projects that demonstrate my expertise in data analysis, visualization, and reporting using Microsoft Excel. Each project covers different datasets and analysis techniques, providing practical insights and solutions for various business needs.

Contents

- **Project 1: Data Developer Salary**

    In this project, I created a Data Developer Salary Dashboard to provide insights into salary trends across different categories. I also incorporated slicers based on job title and 
    company location to allow for more interactive filtering. The dashboard visualizes key aspects such as salary distribution by experience level, company size, employment type, and 
    year. 

    Starting with experience level, it's clear that executive roles command the highest salaries, followed by senior-level, mid-level, and entry-level positions. This indicates a direct 
    correlation between experience and compensation, which is expected in most industries but particularly pronounced in data-related roles. The analysis by company size shows that 
    larger companies tend to offer higher salaries compared to medium and small-sized firms. This is likely due to the increased resources, budgets, and demands for data expertise in 
    larger organizations. Interestingly, there is a consistent trend over the years, with average salaries increasing from 2020 to 2023. This could be indicative of the growing 
    importance of data roles and the rising demand for skilled professionals in this field, driving up compensation.

    When looking at employment type, full-time positions offer significantly higher average salaries than part-time, contract, and freelance positions, which typically come with less 
    job security and fewer benefits. This demonstrates the premium companies are willing to pay for full-time, dedicated employees. Additionally, the dashboard also breaks down salary 
    averages per year, reflecting an upward trend. This year-on-year increase highlights the overall growth of the data industry and suggests that it is becoming an even more integral 
    part of business operations, with companies willing to invest more in their data teams.

    Finally, the bottom section of the dashboard shows the yearly average salary per experience level, reinforcing the earlier finding that experience plays a critical role in 
    determining salary. Across all experience levels, there is an upward trend in compensation, particularly for senior and executive roles, which saw the most significant growth. This 
    suggests that as the demand for leadership in data development increases, so too does the willingness of companies to offer competitive salaries to attract top talent.

- **Project 2: Employee Performance Dashboard**

   This project provides a detailed analysis of employee performance by combining data from monthly sales, attendance, and a performance dashboard. The focus is on evaluating how 
   employees across different roles and departments perform relative to sales targets, attendance, and their total contributions to overall sales.

   In terms of sales achievements, John Smith, the Sales Manager, leads with a total of $105,000, consistently exceeding his monthly targets with achievements of 111% in January and 
   115% in February. Michael Brown, the Marketing Executive, also shows strong performance, with $82,000 in total sales, surpassing his targets both months with 103% and 105%. In 
   contrast, the two Sales Executives, Emily Davis and Sara Johnson, performed below expectations. Emily achieved 86% of her target in January but improved to 95% in February. Sara 
   Johnson's sales were consistently below target, achieving 89% in January and 90% in February. Their performance is reflected in the total sales per employee, with Emily contributing 
   $65,000 and Sara $52,000.

   Attendance data plays a key role in explaining these outcomes. John Smith worked all his available days in January and February, correlating with his exceptional sales performance. 
   Michael Brown also had good attendance, working 21 days in January and 22 in February. In contrast, Sara Johnson had the lowest attendance, with 19 days worked in January, which may 
   have contributed to her lower sales performance. The daily sales per employee also show John Smith as the highest performer, generating $4,772.73 daily, while Sara lags behind at 
   $2,736.84 per day.

   The visual dashboard reinforces these findings, showing that the Sales department, which makes up 75% of the workforce, is the primary driver of revenue. Average sales per role 
   indicate that Sales Managers generate the highest average, $52,500, followed by Marketing Executives at $41,000, and Sales Executives at $29,250. The total sales per employee chart 
   further emphasizes John Smith’s outperformance compared to others.

   This project demonstrates how various factors such as attendance, role, and department contribute to individual and team performance. While the Sales department as a whole shows 
   strong results, there are clear areas where performance, particularly among Sales Executives, could be improved with targeted support. The Marketing Executive, despite being the sole 
   representative of the department, displays consistent achievement and adds significant value to the overall team performance.
  
- **Project 3: IMDb Dataset**
  
    I began my project by working with the raw data from the "messy_IMDB_dataset" sheet. This initial dataset was disorganized and required significant cleaning to make it usable. I 
    started by consolidating all the data into a single column. This was necessary because the information was scattered and needed to be aligned properly.

    Once I had all the data in one column, I copied it to a new sheet as values. This step was crucial for ensuring that no formatting issues or data links from the original source 
    would interfere with the cleaning process. I then used the "text to columns" feature, selecting the semicolon as the delimiter to split the data into separate columns. This 
    transformation allowed me to structure the data more effectively.

    With the data now divided into columns, I converted it into a table format with headers. This organization made it easier to manage and analyze the data. I addressed any null 
    values by filling them in as appropriate and corrected inaccuracies that I identified. This involved verifying the entries to ensure their correctness and completeness.

    To improve readability, I focused on refining text elements such as titles and director names. I standardized these fields to ensure consistency and clarity throughout the dataset. 
    Additionally, I formatted the columns to align with their respective data types, such as adjusting the date formats and standardizing the presentation of scores.

    The result of this meticulous process is the "clean_IMDB_dataset" sheet. The clean dataset is now well-structured and organized, making it much easier to work with and analyze. By 
    transforming the raw data into a more polished format, I ensured that it is both accurate and accessible for any subsequent analysis or use.

- **Project 4: Sports Teams Valuations**

    This dataset was personally scraped using a Python script I developed to gather data on sports teams and their valuations from various Wikipedia pages. The dataset includes key information such as the team name, country, territory, value, revenue, operating income, sport, and league.

    I used pivot tables to manipulate and explore the data, allowing for detailed insights, and created pivot charts for visualization and analysis. The final product was a Sports Teams Valuations Dashboard, featuring line charts that showcase the average team valuation by country and the average operating income by sport. Additionally, the dashboard includes a vertical bar chart illustrating the average team valuation per sport and a horizontal bar chart providing insights into the average revenue by sport. To enhance interactivity, I added slicers for league, country, and territory, allowing for improved filtering and deeper insights into the data.

- **Project 5: Top 100 Companies Analysis**
  
    In this project, I’ve compiled and analyzed data from various companies and industries to understand their financial performance and growth dynamics better. I started with a 
    comprehensive list of top companies, noting their revenue, revenue growth, employee count, and headquarters. For instance, Walmart tops the list with the highest revenue and the 
    largest workforce, reflecting its dominance in the retail sector. Amazon, another major player, also has substantial revenue and a significant number of employees, indicating its 
    strength in both retail and cloud computing. Notably, ExxonMobil and Chevron in the petroleum industry exhibit impressive revenue and growth rates, underscoring the sector's 
    financial clout.

    Next, I analyzed the data by industry, summarizing total revenue, total employees, the number of companies, and average revenue growth for each industry. This part of the analysis 
    revealed that the retail and petroleum industries are the largest in terms of revenue. The retail sector not only generates significant revenue but also employs the most people. On 
    the other hand, the infotech sector stands out with its extraordinary growth rate, suggesting rapid expansion and innovation in this area. By looking at the overall industry data, I 
    could see how different sectors compare in terms of revenue and workforce size, with some like automotive and energy showing high growth but lower overall revenue.

    Finally, I used VLOOKUP to extract detailed information about specific companies, such as Apple, Tesla, and JPMorgan Chase. By examining these companies individually, I observed a 
    range of revenue figures and growth rates that reflect their respective industries’ performance. For example, Tesla’s high revenue growth contrasts with Apple’s more moderate growth 
    despite its high revenue. Intel’s performance in the technology sector and AIG’s results in insurance further highlight the varied dynamics across different industries.

    Overall, this project has given me a well-rounded view of how top companies and industries perform. By combining detailed company data with broader industry trends, I can see the 
    key factors driving success and growth in different sectors. This analysis not only helps me understand the financial landscape but also provides insights into how specific 
    companies compare within their industries.

- **Project 6:** Under construction, coming shortly!

## Each project contains the following:

- **.xlsx File:** The main Excel workbook with data, analysis, and visualizations.
- **Data Source:** The underlying raw data (if applicable) used for analysis into the xlsx File.

If you have any questions or feedback, feel free to reach out!
