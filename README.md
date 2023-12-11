# BI 360 Project
**The Business Insights 360 Project is a part of the Codebasics *Get Job Ready: Power BI Data Analytics for All Levels 2.0* Certification.**

## Problem Statement
AtliQ Technologies, a swiftly expanding electronics company, incurred significant losses in Latin America attributed to their reliance on Excel files and decisions made based on intuition in the Annual Strategic Meeting. Also, The rising competition in the consumer electronics sector prompted the company to embrace data analytics and adopt decision-making based on data insights.

## About AtliQ Technologies
- AtliQ Technologies is a computer and perepherals manufacturing company across the world which manufactures PC, Laptops, Mouse, Keyboard, etc.
- AtliQ's customers are companies like Croma, Best Buy, Staples, Flipkart, Amazon, Neptune.
- AtliQ's has customers on two Platforms
    - Brick and Mortar (Physical)
    - E-Commerce
 - AtliQ sells products to their customers through three Channels
    - Retailer (Both Physical and E-Commerce customers)
    - Direct (AtliQ's own Physical and Ecommerce store i.e., AtliQ e-store and AtliQ executive)
    - Distributer (Neptune in China)

## Stakeholders Requirements for Report
- **Finance View** - Show Profit and Loss statement to understand financial performances across Markets, Products, Customers etc.
- **Sales View** - Show Top/Bottom Customers along Key Metrics. A matrix would be preferable to understand their performance.
- **Marketing View** - Show Top/Bottom Products along Key Metrics.
- **Supply Chain View** - Reliability, Forecast Accuracy in a view to understand Supply Chain performance.
- **Executive View** - Integrated view of key insights for executives.

## Steps for Project Execution
1. Creating a Project Charter incorporating the project objective, hopes & fears, success measures, stakeholders involvement, and claearing the dashboards design concepts.
2. Streamlining the process of incorporating the real-time data into Power BI by connecting with MySQL server.
3. Using Power Query for cleaning, modifying, merging tables in Power BI.
4. Review and deleted the Database relationship created by Power BI by default.Also, creating the required additional dimension table in Power Query.
5. Data validation using some tables in Power BI and matching the values with the data provided.
6. Data modelling is done by connecting different tables using a foreign key and primary key. In this project, Snowflake Schema is used for Data Modelling where all the dimension tables were connected with Fact tables and some of the dimension table were further splitted to granular dimension tables for overcoming redundancy of data.
7. Then, Creating calculated columns using more Power Query and DAX formulas (Formulas listed at the bottom). After the columns were created, verified them in either MySQL or Excel file.
8. This was the last step before start creating the design work and building the dashboards. This step was to optimize the report to reduce the report/file size. This is an important step which helps in reducing the file size so that is easy to share and access by users.
9. Publishing the fully working dashboard to the Power BI service, providing access to pertinent teams to acquire critical business insights.
10. Worked closely with stakeholders to validate the functionality and precision of the dashboards, making enhancements based on their feedback.
11. Actively integrated suggestions and modifications from end-users to improve the dashboards' usefulness.
  
## Dashboard Live here
https://app.powerbi.com/view?r=eyJrIjoiMjk0ZDQwOTctMzkzNi00ZGVmLWFmZGUtMjI3YTA1NmVmYzkwIiwidCI6Ijc5OWU3OTRjLTllYWMtNGUxZi05ZjY0LTE0ODhjYjMyMjRlNiJ9&pageName=ReportSectionacc5f42f533380d008e0

## Created Dashboard
- The created Dashboard basically contains 5 Views - Finance View, Sales View, Marketing View, Supply Chain View and Executive View for serving several stakeholders requirements
- The Dashboard has two more additional views, i.e., Home View, for providing the summary of all the 5 Views along with page navigation to a particular View and Support View for raising issues and feedback.
  
### Finance View
![financeView](https://github.com/guddushah/BI-360-project-AtliQ-Technologies-PowerBI/assets/40028193/6ca4e301-3f95-4548-9ae3-88be61b2e861)
- The Finance View shows Profit & Loss Statement, Net Sales performances over time, Top/Bottom 5 Products in different segments and Top/Bottom 5 Customers in different regions.
- The Profit & Loss Statement shows the performance of products Year over Year.
- This View also has 3 KPI's (Key Performance Index) showing the Net Sales, Gross Margin %, Net Profit % comparison with BenchMark.
- The Benchmark is a slicer in the View which provides Net Sales Performance Vs Last Year and Net Sales Performance Vs Target.
- This metric helps Stakeholders in comparing the performance with the Last Year and targets to be achieved in the future.

### Sales View
![salesView](https://github.com/guddushah/BI-360-project-AtliQ-Technologies-PowerBI/assets/40028193/54d8f68e-69de-46f7-8b3a-321dead3b10b)
- The Sales View helps to drill down the performances of Customers in different regions for Sales Department.
- This View provides the in-depth information about the Pre-Invoice Deductions, Post-Invoice Deductions, Net Sales, Gross Margin, GM % incurred from all the customers.
- It also provides product wise performance in different segements.
- This Benchmark metric in the View helps Stakeholders in comparing the performance of Customers with the Last Year and targets to be achieved in the future.
- This View helps in finding out the potential customers in different regions and helping them to grow the business further.

### Marketing View
![marketingView](https://github.com/guddushah/BI-360-project-AtliQ-Technologies-PowerBI/assets/40028193/f55cce32-4848-48f4-bec9-8121a6d295a6)
- The Marketing View helps to drill down the performances of Products in different segments for Marketing Department.
- This View provides the in-depth information about the Net Sales, COGS, Gross Margin, GM %, Net Profit, Net Profit % incurred from all the products.
- It provides performance metric of the products with different divisions of the segments.
- It provides customer wise performance in different regions and markets.
- This View is helpful for the stakeholders in budgeting for the products and figuring out the potential customers and markets for business growth.
  
### Supply Chain View
![supplyChainView](https://github.com/guddushah/BI-360-project-AtliQ-Technologies-PowerBI/assets/40028193/7aa0e201-3e76-4cba-b662-585dfaefe48f)
- The Supply Chain View is used by the Supply Chain Team to meet the customer demands to avoid excessive or insufficient production.
- Supply Chain is one of the most important department of the business which helps in maintaining the operational cost.
- If excess inventory is produced, then there is cost associated with that inventory for storing and maintaining in the warehouse and not having enough inventory during the demand, the there will be out of stock situation which is not healthy for the business. Therefore, the SC team should always be aware of overproduction and underproduction.
- The SC View has 3 KPI's comparing Forecast Accuracy, Net Error and ABS Error with last year.
- It also shows the Net Error Trend by month compared with the last year.
- From the dashboard we can visualize the Forecast accuracy of 2021 was better than 2020. 

### Executive View
![executiveView](https://github.com/guddushah/BI-360-project-AtliQ-Technologies-PowerBI/assets/40028193/7c20b20b-0562-4436-8998-4b058cc84dcb)

### Tools Used
- MySQL
- Power BI Desktop
- MS. Excel
- DAX Studio
- Power BI Service

### Domain related terms understanding
- Gross Price
- Pre-Invoice deductions
- Net Invoice Sales
- Post-Invoice deductions
- Net Sales
- COGs (Cost of Goods Sold)
- Gross Margin
- Operational Expense
- Net Profit



