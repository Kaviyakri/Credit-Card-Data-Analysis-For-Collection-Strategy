# Credit-Card-Data-Analysis-For-Collection-Strategy
**Project : Credit Card Data Analysis for Collection Strategy Data Source:**
•	The credit card data dump is provided in Excel. BI Tool Used:
•	Power BI is used for data analysis, visualization, and reporting.
**Objective**:
**The goal of this analysis is to extract meaningful insights from the credit card data dump, such as:
•	Total number of cases (active and old).
•	Identification of unique customers and old customers per month.
•	Case distribution by location to identify geographical trends.
•	Categorization of cases based on outstanding balance buckets.
•	Calculation of EMI-to-current balance ratio to understand payment obligations.
•	Prioritization of cases for agents based on outstanding amounts to optimize collection efforts.
The insights generated will be used to allocate agents efficiently for amount collection and help achieve collection targets.

**Step 1: Data Exploration s Cleaning**
•	Review field names and remove unwanted columns that are not relevant to the analysis.
•	Handle missing values by either:
o	Removing blank records.
o	Imputing missing data where necessary.
o	Converting fields to the correct data types (e.g., dates, numbers, text).
•	Import cleaned data into Power BI for further processing.

**Step 2: Data Modeling**
•	Create a Date Table to enable time-based analysis.
•	Establish relationships between tables:
o	Connect the main credit card dataset with the Date Table using a one-to-many relationship on the date field.
 
o	Ensure proper relationships between other necessary tables for accurate reporting.

**Step 3: DAX Measures s Calculations**
•	EMI to Current Balance Percentage:
o	A DAX measure to calculate Total EMI / Current Balance, which helps understand the proportion of installment payments relative to the outstanding balance.
•	Old Customer Identification:
o	A DAX measure to find customers who have been present for multiple months.
•	Unique Customer Count by Month:
o	A DAX measure to track the number of unique customers in each month, helping in trend analysis.

**Step 4: Insights s Business Impact**
•	Overview of Cases: Provides a high-level summary of total cases and their distribution.
•	Prioritization Based on Amounts: Identifies high-value and low-value cases, enabling efficient agent allocation.
•	Geographical Analysis: Helps in understanding which locations have the most outstanding cases, guiding regional collection strategies.
•	Customer Segmentation: Identifies new vs. old customers, allowing for different collection approaches.
•	Collection Strategy Optimization: Insights enable management to allocate agents more effectively and set realistic collection targets based on case distribution.

**Conclusion**
This analysis provides a comprehensive view of the credit card outstanding cases, helping management prioritize collection efforts and optimize agent allocation based on factors like case count, amount buckets, and location-wise distribution. The insights will drive better
decision-making and improve collection efficiency to meet targets effectively.
