# BI 360 Project

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
- The created Dashboard basically contains 5 Views - Finance View, Sales View, Marketing View, Supply Chain View and Executive View.
- The Dashboard has two more additional views, i.e., Home and Support View for providing the basic information about the Dashboard.
  
### Finance View
![financeView](https://github.com/guddushah/BI-360-project-AtliQ-Technologies-PowerBI/assets/40028193/6ca4e301-3f95-4548-9ae3-88be61b2e861)


### Sales View
![salesView](https://github.com/guddushah/BI-360-project-AtliQ-Technologies-PowerBI/assets/40028193/54d8f68e-69de-46f7-8b3a-321dead3b10b)


### Marketing View
![marketingView](https://github.com/guddushah/BI-360-project-AtliQ-Technologies-PowerBI/assets/40028193/f55cce32-4848-48f4-bec9-8121a6d295a6)


### Supply Chain View
![supplyChainView](https://github.com/guddushah/BI-360-project-AtliQ-Technologies-PowerBI/assets/40028193/7aa0e201-3e76-4cba-b662-585dfaefe48f)


### Executive View
![executiveView](https://github.com/guddushah/BI-360-project-AtliQ-Technologies-PowerBI/assets/40028193/7c20b20b-0562-4436-8998-4b058cc84dcb)


## Objective
The objective of this project is to build an enterpeise wide business intelligence and data driven decision making dashboard giving the insights about finance, sales, marketing and supply chanin sectors of the businesses happening globally.

### Dashboard Live at https://www.novypro.com/project/bi-360-dashboard
### Tools Used
- MySQL
- Power BI Desktop
- Power Query M formula language
- DAX language
- DAX Studio

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



### Report Views 
- Info View
- Finance View
- Sales View
- Marketing View
- Supply Chain View
- Executive View
- Support View


