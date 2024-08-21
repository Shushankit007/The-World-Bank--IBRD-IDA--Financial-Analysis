# **World Bank(IBRD-IDA) Financial Analysis**

## **Project Overview**
The World Bank IBRD and IDA Financial Analysis project offers a comprehensive examination of the loans, credits, net flows, and commitments extended by the International Bank for Reconstruction and Development (IBRD) and the International Development Association (IDA) from 2010 to 2025. Utilizing Excel for data cleaning and analysis, and Tableau for visualization, the project focuses on key financial metrics such as loan distribution, repayment performance, interest rates, and credit risk exposure. The inclusion of net flows and commitments analysis provides additional insights into the allocation and management of financial resources, supporting informed decision-making and policy formulation at a global level.

## **Objectives:**
### IBRD Loans Analysis
1. **Data Cleaning and Validation**: Ensure the IBRD dataset is accurate, complete, and formatted correctly for analysis.
2. **Key Performance Indicators (KPIs)**: Identify and calculate essential KPIs related to loan amounts, disbursements, repayments, and interest rates.
3. **Regional and Sectoral Analysis**: Examine the distribution of loans across different regions and sectors to identify trends and key areas of focus.
4. **Loan Type and Status Analysis**: Analyze different types of loans and their current status to understand the portfolio composition and performance.
5. **Visualizations**: Create clear and informative visualizations to present the findings effectively.

### IDA Credit and Grants Analysis
1. **Credit Risk Analysis**: Assess credit risk exposure across different borrowers and regions.
2. **Time Series Analysis**: Analyze the time series of credit amounts and repayment patterns.
3. **Principal Amount by Borrowers**: Identify the top borrowers and their associated principal amounts.
4. **Global Distribution**: Map the global distribution of amounts due and other relevant metrics.
5. **Credit Portfolio Analysis**: Evaluate the credit utilization ratio, repayment efficiency, and other critical metrics.

### IBRD-IDA Net Flows and Commitments Analysis
- **Data Aggregation**: Combine IBRD and IDA data to analyze net flows and commitments from 2010 to 2025.
- **Trend Analysis**: Identify patterns and changes in net financial flows over time.
- **Commitment Distribution**: Analyze commitments by type and sector.
- **Geographical Mapping**: Visualize global distribution of net flows and commitments.
- **Comparative Analysis**: Compare financial activities across regions and time periods.

## **Methodology**
### IBRD Data Cleaning and Validation
- **End of Period**: Cleaned using text-to-column function and changed its data type.
- **Borrower**: Filled missing values with "unavailable data."
- **Guarantor Country Code and Country**: Used formulas to fill in missing values.
- **Interest Rate**: Replaced null values with 0 and added a % suffix using custom format.
- **Currency of Commitment**: Assumed USD and filled missing values.
- **Amount Columns**: Converted to number data type.
- **Date Columns**: Formatted to dd-mm-yyyy.
- **Original Principal Amount**: Filled missing values using a custom formula.
- **Net Loan Amount**: Created by subtracting the "Cancelled Amount" from the "Original Principal Amount."
- **Sector Column**: Created using relevant keywords in the project name.

### IDA Credit and Grants Data Cleaning and Validation
- **Language Translation**: Translated columns with different languages into English.
- **Date Column Cleaning**: Standardized the format across all date columns.
- **Currency Conversion**: Standardized all amounts to a single currency where applicable.
- **Amount Columns**: Filled missing values and converted them to the appropriate data type.

### IBRD-IDA Net Flows and Commitments Data Cleaning and Validation
- **Data Connection**: Connected to the World Bank OData service to access the latest net flows and commitments data.
- **Date Formatting**: Standardized all date columns to dd-mm-yyyy format.
- **Currency Standardization**: Ensured all financial amounts were in a consistent currency (USD).
- **Data Aggregation**: Combined IBRD and IDA data for comprehensive analysis.


## **Key Insights**
### IBRD Loans
1. **Performance Indicators**
   - Total Principal Amount: Comprehensive view of the original loan amounts.
   - Total Disbursed Amount: Amounts actually disbursed to borrowers.
   - Total Undisbursed Amount: Funds yet to be disbursed.
   - Total Repaid Amount: Amounts repaid by borrowers to date.
   - Total Amount Due: Outstanding amounts yet to be repaid.
   - Average Interest Rate: Insights into the cost of borrowing.
   - Number of Active Loans: Loans currently active and not fully repaid.
2. **Regional Distribution of Loans**: Breakdown of loans across different geographical regions.
3. **Top Borrowing Countries**: Countries with the highest loan amounts.
4. **Loan Distribution by Sector**: Allocation of loans across various sectors.
5. **Loan Type and Status Analysis**: Analysis of loan types and their current status.

### IDA Credit and Grants
1. **Credit Risk Exposure**: Analysis of exposure across different regions and borrowers.
2. **Time Series of Credit Amounts**: Insights into the trends of credit issuance and repayment over time.
3. **Principal Amount by Borrowers**: Highlights of top borrowers and their principal amounts.
4. **Global Distribution Map**: Visualization of amounts due and other relevant metrics.
5. **Credit Utilization Ratio**: Assessment of how effectively credit is utilized.
6. **Repayment Efficiency**: Evaluation of how efficiently borrowers repay their loans.



## **Visual Insights**
### IBRD Loans
1. **Total Principal Amount vs. Disbursed Amount**: Bar chart comparing original loan amounts with disbursed amounts.
2. **Regional Distribution of Loans**: Pie chart showing loan distribution across regions.
3. **Top Borrowing Countries**: Bar chart highlighting countries with the highest loan amounts.
4. **Loan Distribution by Sector**: Pie chart indicating loan allocation by sector.
5. **Interest Rate Analysis**: Line chart depicting average interest rates over time.

### IDA Credit and Grants
1. **Credit Risk Exposure**: Bar chart or heatmap showing exposure across regions.
2. **Time Series of Credit Amounts**: Line chart illustrating trends over time.
3. **Principal Amount by Borrowers**: Bar chart highlighting top borrowers.
4. **Global Distribution Map**: Map visualizing the global distribution of amounts due.
5. **Credit Utilization Ratio**: Bar chart showing the utilization ratio by borrower or region.
6. **Repayment Efficiency**: Line chart or bar chart evaluating repayment patterns.

## Tableau Dashboard - Net Flows and Commitments Analysis (2010-2025):
This interactive Tableau dashboard is dedicated to analyzing the net flows and commitments of the World Bank Group from 2010 to 2025. It offers a focused examination of financial activities through various visualizations, providing key insights into the following areas:
- **Geographical Distribution:** A dynamic map visualizes the distribution of net flows and commitments across different regions and countries, highlighting where the World Bank Group's financial resources are being allocated.
- **Commitment Types:** A bar chart categorizes commitments by type, offering a clear breakdown of how funds are committed across different sectors or projects.
- **Net Flows Over Time:** A time-series analysis is presented to track net financial flows year by year, allowing users to observe trends and fluctuations from 2010 to 2025.
- **Commitment Breakdown:** A pie chart provides a visual summary of the various commitment categories, giving users a quick overview of the proportionate distribution of funds.
- **Interactive Exploration:** Users can interact with the dashboard by filtering data by region, country, or year, enabling a tailored analysis that aligns with specific areas of interest.


## Visualizations
![IBRD Summary Dashboard Screenshot](https://github.com/Shushankit007/The-World-Bank--IBRD-IDA--Financial-Analysis/blob/main/Summary%20Dashboard.png)
![IBRD Overview Dashboard Screenshot](https://github.com/Shushankit007/The-World-Bank--IBRD-IDA--Financial-Analysis/blob/main/Overview%20Dashboard.png)
![IDA Dashboard Screenshot](https://github.com/Shushankit007/The-World-Bank--IBRD-IDA--Financial-Analysis/blob/main/IDA%20Dashboard%20Screenshot.png)
![IBRD-IDA Net Flows and Commitments Dashboard Screenshot](https://github.com/Shushankit007/World-Bank--IBRD-IDA--Financial-Analysis/blob/main/IBRD_IDA%20Dashboard(Tableau).png)


## Usage
1. Open the `World_Bank_IBRD Project.xlsx` and `World_Bank(IDA) Project.xlsx`file in Microsoft Excel.
2. Navigate through the various sheets to explore the data cleaning, analysis, and visualizations.
3. Interact with the pivot tables and charts to gain insights from the data.
4. For more details about dataset refer this file `Data_Dictionary IBRD and IDA Dataset Details.pdf`
5. Open `NetFlow&Commitments Analysis.twb` in Tableau
6. Visit Tableau Public: (https://public.tableau.com/views/Book1_17236680299730/Dashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Reference
- https://data.worldbank.org/
- https://finances.worldbank.org/ (open finance data of world bank)
  
