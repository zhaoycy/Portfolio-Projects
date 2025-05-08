# Lanbing Zhao-Data-Analyst
## About
Hi, I'm Lanbing, a data analyst with a background in macroeconomic analysis. <br>

After four years as an Economist at the People’s Bank of China and completing a data analysis bootcamp, I transitioned into a Junior Data Analyst role at Fortray Global Services Ltd. In this position, I have worked extensively with large datasets, developed interactive dashboards, and contributed to data-driven decision-making. My expertise in Python, SQL, and data visualization tools such as Power BI and Tableau has enabled me to enhance reporting accuracy and streamline analytics processes.<br> 

My CV in [pdf](https://github.com/zhaoycy/Portfolio-Projects/blob/main/Lanbing%20Zhao%20-%20CV%20-%20Data%20Analyst.pdf).<br>

This is a repository to showcase skills, share projects and track my progress in Data Analytics and Data Science.<br>

## Table of Contents
- [About](#about)
- [Data Analysis Projects](#data-analysis-projects)
  - [Python]
    - [App Rating Prediction](#app-rating-prediction-using-python)
  - [SQL]
    - [Employee Performance Mapping](#Tech-Start-up-Employee-Performance-Mapping-using-SQL)
  - [R]
    - [Flight Delay EDA](#Flight-Delay-EDA-using-R)
  - [Tableau]
    - [Regional Sales Comparison](#Sales-Comparison-for-2-Selected-Regions-using-Tableau)
  - [Power BI]
    - [Data Professional Survey Breakdown](#Data-Professional-Survey-Breakdown-using-Power-BI)
- [Certifications](#certifications)
- [Contact](#contact)

## Data Analysis Projects
 In this section I will list data analytics projects briefly describing the technology stack used to solve cases.

### App Rating Prediction using python
**Code**:[App Rating Prediction.ipynb](https://github.com/zhaoycy/Data-Analysis/blob/main/App_Rating_Prediction.ipynb)

**Goal**: To predict the ratings of mobile apps based on various features such as app size, reviews, installs, price, category, and content rating.

**Description**: The project aimed to predict the ratings of apps in a play store, with the objective of identifying high-potential apps that could be boosted for greater visibility. The dataset contained information about app size, reviews, installs, price, category, and content rating, etc. The steps involved data cleaning, feature engineering, exploratory data analysis (EDA), and building a regression model to predict app ratings. The model used Linear Regression to predict ratings based on various features, and its performance was evaluated using the R² score.

**Skills**: Data cleaning, create and apply function, exploratory data analysis (EDA), linear regression, log transform, data visualization, Pandas, Numpy, Seaborn, Matplotlib, Scikit-learn.

**Results**: After cleaning and preprocessing the data (including handling missing values and removing outliers), the model achieved an R² score on the training set, indicating its ability to predict app ratings. The feature engineering steps included applying logarithmic transformations to reduce skewness and one-hot encoding categorical variables. This project provides a predictive model that can help identify apps with high potential ratings.

### Tech Start-up Employee Performance Mapping using SQL
**Code**: [Employee Performance Mapping.sql](https://github.com/zhaoycy/Data-Analysis/blob/main/Tech_Start-up_Employee_Performance_Mapping.sql)

**Goal**:To analyse employee performance data and facilitate the employee performance mapping for a tech company, including employee ratings analysis, promotions & training recommendations, and bonus calculations.

**Description**: This project aimed to analyse employee data at a tech satrt-up to support the HR department in decision-making regarding promotions, training, and bonus. The dataset contained employee information such as ID, role, experience years, salary, and performance ratings across different continents. Key tasks included filtering employees based on their performance ratings, calculating bonuses based on ratings and salary, and identifying employees who require training or promotion. The project also involved creating stored rocedure and index to streamline data retrieval and improve efficiency in HR processes.

**Skills**: Database management, CONCAT, JOIN, UNION, Group By, ORDER BY CASE， Window Function, Nested Query, VIEW, Stored Procedure, Stored Function, Index.

**Results**: By creating optimized SQL queries, views, and stored procedures, the project provided a clear framework for evaluating employee performance based on ratings, experience, and salary. The calculated bonuses helped HR determine extra costs, and the distribution of ratings across departments assisted in identifying top performers and those needing improvement. The project also improved efficiency in retrieving employee data, making it easier for HR to process and make timely decisions for bonus, promotions and training.

### Flight Delay EDA using R
**Code**:[Flight Delay EDA.txt](https://github.com/zhaoycy/Data-Analysis/blob/main/Flight%20Delay%20EDA.txt)

**Goal**: To visualise the effect of various factors like scheduled time, carrier, destination, weather, and day of the week on flight delays, using a variety of plots.

**Description**: Flight delays are influenced by several factors such as scheduled times, weather conditions, and the carrier. This analysis seeks to explore and visualise how these factors correlate with delays, particularly focusing on understanding the number of delayed flights, how weather impacts delays, and the distribution of delays across different times, days, and carriers.

**Skills**: Lubridate library, Difftime, Aggregate, Missing values handling, Histogram plot, Barplot, Scatter plot, and Box plot.

**Results**: After thoroughly cleaning and preprocessing the data, including handling missing values and converting relevant variables, insightful visualisations were created to understand the relationships between flight delays and key factors such as scheduled time, carrier, weather, and origin/destination. 

### Sales Comparison for 2 Selected Regions using Tableau
**Dashboard**:[Regional Sales Comparison.png](https://github.com/zhaoycy/Data-Analysis/blob/main/Sales%20Comparison%20for%202%20Selected%20Regions.png)

**Goal**: To create an interactive dashboard to visualise and compare sales performance between two dynamically selected regions.

**Description**: The project aimed to build a comparative sales performance dashboard for upper management to analyse and assess the differences between two selected regions. The goal was to provide data-driven insights for targeted improvements in regional sales strategy. The dashboard was developed in Tableau and incorporated interactive Primary Region and Secondary Region parameters to allow users to dynamically select and compare any two regions from the dataset. Calculated fields were created to capture First Order Date, Total Sales, Average Sales per Order, Number of Customers, Number of Orders, and Number of Products in Sale for each region. 

**Skills**: Hierarchy, Calculated fields, Parameters, filled map, text table.

**Results**: The final dashboard provided a dynamic, side-by-side view of regional sales performance, with drill-down capabilities for each key metric. The use of parameters allowed flexible comparisons between any two regions without manual filtering, significantly improving the decision-making process. By visualising sales KPIs such as first order date, average order value, and product diversity, stakeholders could identify patterns like delayed market entry or underperforming product mixes. 

### Data Professional Survey Breakdown using Power BI
**Dashboard**:[Data Professional Survey Breakdown.png](https://github.com/zhaoycy/Data-Analysis/blob/main/Data%20Professional%20Survey%20Breakdown.png)

**Goal**: To build an interactive report that provides an in-depth analysis of survey data collected from a data professional survey conducted by Alex the Analyst, visualising key metrics and various breakdowns.

**Description**: This project aimed to clean and standardise the survey data to ensure accurate analysis and representation. The survey dataset included fields such as job title, gender, salary, industry, country, and favorite programming language. Using Power Query in Excel, columns were split and values were replaced to standardize fields like job titles, industries, and salary. The goal was to produce a comprehensive dashboard with insights into the data professional community's demographic and salary trends.

**Skills**: Power Query, Data Standardisation & Transformation (Splitting Columns, Replacing Values), DAX (Calculated Columns, Calculated Measures), Visualisations (Card Visuals, Clustered Bar Charts, Treemaps, Donut Charts, Stacked Column Charts).

**Results**: The Power BI report provided a dynamic overview of the survey results. The card visuals allowed for quick insights into the survey's scale, while the clustered bar chart and donut chart gave clear comparisons of salary by job title and gender. The treemap highlighted regional distibution in survey responses, and the stacked column chart effectively visualised the popularity of various programming languages. This comprehensive analysis helped uncover key trends, such as salary disparities between genders and variations in salary across different job titles. 

### Certifications
- [Tableau Certified Data Analyst ](https://github.com/zhaoycy/Data-Analysis/blob/main/Tableau%20Certified%20Data%20Analyst%20Certificate%20from%20Tableau.pdf)(Tableau, Mar 2025))
- [Certified SQL Developer (Advanced Level)](https://verify.w3schools.com/1PUOVYI5N0)(W3Schools, Apr 2025) 
- [Data Analyst Master(Excel, Python, Tableau, SQL, Power BI, R)](https://fortraynetworks.lms.simplilearn.com/dashboard/certificate) (Simplilearn, Dec 2024)

### Contact
- LinkedIn: [@LanbingZhao](https://www.linkedin.com/in/lanbing-zhao-306603264/)
- Email: lanbingfortray@gmail.com

