# Sales-Sorting-Formatting-and-Filtering-using-Data-Science
This is a project that focuses on performing data cleaning, sorting, and prediction using Microsoft Excel to analyze and extract meaningful insights from raw sales data.
In real-world scenarios, datasets are rarely perfect; they
are often incomplete, inconsistent, and unorganized [1]. Such issues may include missing values, duplicate
records, inconsistent text entries (such as variations in naming), and improper formatting of dates and
numerical values [2]. These problems can lead to inaccurate analysis and poor decision-making if not
addressed properly [1]. Therefore, the first stage of this project emphasizes data cleaning techniques, which
involve removing duplicate entries, handling missing data through suitable methods (such as replacing with
averages or estimated values), correcting inconsistent text formats using functions, and standardizing date
formats [2]. These steps ensure that the dataset becomes accurate, consistent, and reliable for further
analysis.
Once the data is cleaned and prepared, the next stage involves organizing it through sorting and filtering
techniques. Sorting allows the data to be arranged in a meaningful order, such as by highest or lowest sales,
chronological order of dates, or region-wise grouping. Filtering helps in extracting specific subsets of data
based on given conditions [5]. These operations make it easier to explore the dataset and identify patterns,
trends, and key performance indicators. Furthermore, advanced Excel tools such as conditional formatting
are used to highlight important data points, while pivot tables are utilized to summarize large datasets
efficiently [5]. Visual elements like charts and graphs are also incorporated to present the data in an easy-to-
understand and visually appealing manner.
The final stage of the project focuses on prediction and forecasting, which is a crucial aspect of data
analysis. Using Excel’s built-in features such as trendlines and forecasting functions, future sales values are
estimated based on historical data trends. By applying methods like linear regression, Excel is able to
identify relationships between variables (such as time and sales) and generate predictive models [4]. These
predictions can help businesses anticipate future demand, plan inventory, allocate resources, and make
strategic decisions [3]. The use of forecasting tools demonstrates how even basic analytical techniques can
provide valuable insights when applied correctly.
Overall, this project highlights the importance of data preprocessing, organization, and analysis in the field
of data science [6]. It demonstrates that Microsoft Excel, despite being a simple and widely available tool, is
highly effective for performing essential data analysis tasks. By transforming raw and unstructured data into
meaningful information and actionable insights, this project showcases how data-driven approaches can
support better decision-making and improve overall business performance.
INTRODUCTION
1.1 Identification of Client /Need / Relevant Contemporary issue
• Small business owners and sales managers
• Retail store operators
• Data analysts or students working with sales data
• To organize messy and unstructured sales data
• To improve accuracy by removing errors and duplicates
• To analyze sales performance across regions and products
• To make informed business decisions using data insights
• To predict future sales for planning and growth
1.2 Identification of Problem
In many organizations, sales data is often stored in an unorganized and inconsistent format, containing errors
such as missing values, duplicate entries, and incorrect data formats. This makes it difficult to analyze the
data accurately and extract meaningful insights. Without proper organization and analysis, businesses may
struggle to understand their performance and make informed decisions. Therefore, there is a need to clean,
structure, and analyze the data effectively, as well as predict future trends to support better planning and
decision-making.
1.3 Identification of Tasks
• Collect or create raw sales dataset
• Perform data cleaning (remove duplicates, handle missing values, fix formats)
• Organize data using sorting and filtering techniques
• Analyze data using pivot tables and charts
• Apply conditional formatting to highlight key insights
• Perform prediction using trendlines and forecasting functions
• Interpret results and draw conclusions
1.4 Organization of the Report
• Introduction – Overview of the project and its objectives
• Problem Identification – Description of the issue being addressed
• Methodology – Steps and techniques used (data cleaning, sorting, analysis, prediction)
• Data Analysis & Results – Presentation of findings using tables, charts, and pivot tables
• Prediction & Forecasting – Explanation of future trends using Excel tools
• Conclusion – Summary of insights and outcomes of the project
• References – Sources of data and tools used
LITERATURE REVIEW/BACKGROUND STUDY
1.5 Timeline of the reported problem
• Initial Stage: Raw sales data is collected, which is unorganized and contains errors.
• Problem Identification: Issues like missing values, duplicates, and inconsistent formats are observed.
• Analysis Stage: Data cleaning and organization are performed to make the dataset usable.
• Solution Implementation: Sorting, filtering, and analysis tools are applied to extract insights.
• Final Stage: Prediction and forecasting are conducted to address the problem and support decision-
making.
1.6 Existing solutions
• Use of spreadsheet tools like Microsoft Excel for basic data cleaning and analysis
• Database management systems (DBMS) to store and organize large datasets
• Data analysis tools like Python, R, and specialized software (e.g., Power BI, Tableau)
• Manual data processing methods used in small businesses
• Built-in Excel features such as sorting, filtering, pivot tables, and charts
1.7 Bibliometric analysis
Key Features:
• Data cleaning, sorting, and filtering
• Charts, pivot tables, and forecasting tools
Effectiveness:
• Improves data accuracy
• Helps identify trends and supports decision-making
Drawbacks:
• Limited for large datasets
• Less advanced than tools like Python/R
• Depends on data quality and manual effort
1.8 Review Summary
This project demonstrates how raw sales data can be transformed into meaningful insights using Microsoft
Excel. It highlights the importance of data cleaning, sorting, and analysis to improve accuracy and
reliability. Using tools like pivot tables, charts, and forecasting functions, the project effectively identifies
trends, patterns, and future sales predictions. While Excel is user-friendly and efficient for small to medium
datasets, its limitations include handling very large data and performing advanced analytics. Overall, the
project shows that proper data management and analysis can support informed decision-making and
business planning.
1.9 Problem Definition
Many businesses collect large amounts of sales data, but it is often incomplete, inconsistent, and
unorganized. Issues such as missing values, duplicate entries, and incorrect formatting make it difficult to
analyze the data accurately. Without proper cleaning and organization, extracting meaningful insights and
predicting future trends becomes challenging, leading to poor decision-making. This project addresses these
issues by using Excel to clean, organize, analyze, and forecast sales data effectively.
1.10 Goals/Objectives
• To clean and organize raw sales data for accuracy and consistency
• To sort, filter, and visualize data for better analysis
• To identify trends, patterns, and high-performing products or regions
• To predict future sales using Excel’s forecasting tools
• To demonstrate how data-driven insights support informed decision-making
DESIGN FLOW/PROCESS
2.1 Evaluation & Selection of Specifications/Features
Evaluation of Existing Features
• Data Cleaning Tools: Remove duplicates, handle missing values, standardize formats → effective
but may require manual effort for large datasets
• Sorting & Filtering: Useful for organizing data and extracting insights → simple, but limited for
complex analysis
• Pivot Tables & Charts: Excellent for summarizing and visualizing data → highly effective, widely
used in Excel
• Forecasting & Trendlines: Supports basic prediction using historical data → effective for small
datasets but less accurate for large or highly variable datasets
• Conditional Formatting: Highlights important data points → good for visual insights but does not
perform analysis
Selected Features for the Solution
Based on evaluation, the following features are ideally required for the project:
1. 2. 3. 4. 5. Data Cleaning Tools – to ensure accurate and consistent data
Sorting and Filtering – to organize and explore the dataset
Pivot Tables & Charts – to summarize data and visualize trends
Forecasting Functions & Trendlines – to predict future sales
Conditional Formatting – to highlight key metrics and insights
These features collectively provide a complete, user-friendly solution for analyzing, visualizing, and
forecasting sales data in Excel.
2.2 Design Constraints
• Limited to Microsoft Excel as the analysis tool
• Dataset size should be manageable for Excel performance
• Accuracy of predictions depends on data quality
• Manual effort required for data cleaning and preparation
• Forecasting is limited to linear trends and may not capture complex patterns
2.4 Analysis of Features and finalization subject to constraints
The project features were analyzed based on their usefulness, effectiveness, and limitations within the
constraints of Microsoft Excel. Data cleaning, sorting, and filtering were selected as essential for ensuring
accuracy and organizing the dataset. Pivot tables and charts were chosen for effective summarization and
visualization of insights. Forecasting functions and trendlines were included for predicting future sales,
keeping in mind that Excel handles mainly linear trends and small to medium datasets. Conditional
formatting was added to highlight key metrics. All selected features balance functionality with Excel’s
performance limitations and ease of use, providing a practical and efficient solution for sales data analysis
and prediction.
RESULTS ANALYSIS AND VALIDATION
3.1 Implementation of solution
To clean raw sales data, organize it using sorting/filtering, and predict future sales using Excel tools.
Intentionally add:
• Missing values
• Duplicate rows
• Inconsistent formats (like “north”, “North”, “NORTH”)
Figure 1.1
Step 1: Data Cleaning
✔ Tasks to Perform:
1. Remove Duplicates
a. Go to → Data → Remove Duplicates
2. Handle Missing Values
a. Replace blanks with:
i. Average (for Sales)
ii. 0 or estimated values
3. Fix Text Formatting
a. Use formulas:
b. =UPPER(A2) or =PROPER(A2)
4. Convert Date Format
a. Ensure all dates are in proper format
5. Trim Extra Spaces
a. =TRIM(A2)
Figure 2.1
Figure 3.1
Step 2: Sorting & Filtering
Tasks:
1. Sort Data
a. Sort by:
i. Highest Sales
ii. Region
iii. Date (latest first)
2. Apply Filters
a. Filter:
i. Sales > 1000
ii. Specific region (e.g., North)
3. Conditional Formatting
a. Highlight:
i. Top 10 sales
ii. Low profit values
Figure 4.1
Step 3: Data Analysis
✔ Use:
• Pivot Table
o Total sales by region
o Profit by product
• Charts
o Bar chart → Sales per region
o Line chart → Sales over time
Figure 5.1
Step 4: Prediction
✔ Method 1: Trendline
1. Select Date vs Sales
2. Insert → Line Chart
3. Add Trendline → Linear
4. Check:
a. “Display Equation”
b. “Display R² value”
Figure 6.1
Predictions & Insights
1. Sales Trend (Future Prediction)
• The date vs sales graph shows an overall upward trend despite fluctuations.
• The trendline indicates that sales are expected to continue increasing over time.
• However, the low R² value (~0.21) suggests:
• The prediction is not highly accurate
• Sales are highly volatile (irregular spikes)
Prediction: Sales will grow, but with uncertain fluctuations.
2. Regional Performance
• The “sales per region” chart shows WEST region dominating with the highest sales values.
• NORTH, EAST, and SOUTH contribute less comparatively.
Prediction:
• WEST region will continue to generate the highest sales
• Future business strategies should focus more on WEST for maximum profit
3. Sales vs Profit Relationship
• The sales-to-profit graph shows a strong positive relationship
• As sales increase, profit also increases proportionally
Prediction:
• Increasing sales will directly increase profit
• High sales periods will lead to significant profit growth
4. Growth Pattern
• Early data shows slow growth, but later entries show sharp increases (spikes)
Prediction:
• Business may be entering a rapid growth phase
• Future sales could see more sudden jumps rather than steady growth
Final Output
• Clean dataset
• Sorted & filtered data
• Pivot table + charts
• Forecast graph with trendline
• Explanation of prediction
Figure 7.1
CONCLUSION AND FUTURE WORK
5.1 Conclusion
This project successfully demonstrated how raw and unorganized sales data can be transformed into
meaningful insights using Microsoft Excel [5]. The expected outcome was to clean the dataset,
organize it effectively, analyze trends, and predict future sales. The results showed an overall
increasing trend in sales, with the WEST region performing the best and profit increasing
proportionally with sales [3].
However, there were some deviations from the expected results. The prediction accuracy was
limited, as indicated by fluctuations in the data and a relatively low reliability of the trendline. This
occurred due to irregular spikes in sales, inconsistent data patterns, and possible external factors not
included in the dataset [4]. Additionally, manual data cleaning may have introduced minor errors [2].
Overall, the project achieved its objective of demonstrating data cleaning, analysis, and basic
forecasting, while also highlighting the importance of data quality for accurate predictions [1][6].
5.2 Future Work
• Improve data quality by collecting more consistent and larger datasets
• Use advanced tools such as Python or Power BI for better analysis and prediction
• Apply more accurate forecasting techniques beyond linear trendlines
• Automate data cleaning processes to reduce manual effort and errors
• Include additional factors (e.g., seasonality, customer behavior) to improve predictions
• Develop an interactive dashboard for better visualization and decision-making
References
[1] Data Science for Business, Foster Provost and Tom Fawcett, O’Reilly Media, 2013.
[2] Data Mining: Concepts and Techniques, Jiawei Han, Micheline Kamber, and Jian Pei, 3rd ed.,
Morgan Kaufmann, 2011.
[3] Business Analytics, James R. Evans, Pearson Education, 2017.
[4] Introduction to Linear Regression Analysis, Douglas C. Montgomery et al., 6th ed., Wiley, 2021.
[5] Microsoft Excel Documentation, Microsoft, Available: https://support.microsoft.com/excel
[6] IBM, “Data Science Concepts,” Available: https://www.ibm.com/topics/data-science
