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
https://app.powerbi.com/view?r=eyJrIjoiNDZjZDZiYzctZDUzYS00ZTI3LTg2NDktMDFlZGFmZmE0MzYxIiwidCI6IjdlNTIyZTlmLTE0MTAtNDI2My1iOTM2LTkxNTJhNTkyNTY3MSJ9

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
- The Executive View is for the senior Stakeholders like CEO, CTO, Managers who wants to see the quick insights on every aspects of the business on every departments.
- The Executive consists 4 KPI's NS, GM %, Net Profit %, Forecast Accuracy %, Revenue by Channel and Division, key insights by division.
- It also has Year over Year trend by NS, Net Profit %, GM %, Market Share.
- Is shows PC Market share for AtliQ and competitors.
- The View shows Top 5 Customers and Products by Revenue.

## Tools Used
- MySQL
- Power BI Desktop
- MS. Excel
- DAX Studio
- Power BI Service

## Power BI Features Learned
- Power Query M Language
- DAX Formulas
- Data Modeling
- Table Creation
- Creating Tool Tips
- Creating Switch using Bookmark
- Learnt using conditional formatting for the blank results after applying filters
- Creating Dynamic Last Refresh Date
- Creation Of Different Views in a single report for different departments
- Deploying the fully working Dashboard in Cloud.

## Project based Learnings
- Power BI
- Data Modelling
- Dashboard Creation & Designing
- Project Charter
- Stakeholder Mapping
- Going through P&L Statements
- Working on business transactions like creating Profit %, Gross Margin %, Forecast %, comparison in sales from previous periods etc.
- The learning from this project was not limited to Power BI. The project has a business scenario where one has to go through the P & L statements where we needed to compare the performance of the products, product categories, markets, customers etc.
- From providing the stats of finance to the performance of products in different markets among different customers is measured and displayed on the dashboards.
- Understanding Financial terms like
    - Gross Price
    - Pre-Invoice deductions
    - Net Invoice Sales
    - Post-Invoice deductions
    - Net Sales (NS)
    - Cost of Goods Sold (COGS)
    - Gross Margin (GM)
    - Operational Expense
    - Net Profit (NP)
 
## Measures Created using DAX Formula
1. **ABS Error** = SUMX(DISTINCT(dim_date[date]),                   
               SUMX(DISTINCT(dim_product[product_code]), ABS([Net Error])))                                       
2. **ABS Error %** = DIVIDE([ABS Error], [Forecast Qty], 0)
3. **ABS Error LY** = CALCULATE([ABS Error],SAMEPERIODLASTYEAR(dim_date[date]))
4. **Ads & Promotions $** = SUM(‘fact_actuals_estimates'[ads_promotions])
5. **Atliq MS %** = CALCULATE([Market Share %], marketshare[manufacturer]=”atliq”)
6. **BM Message** = IF([NS BM $] = BLANK() || [GM % BM] = BLANK() || [NP % BM] = BLANK(), “BM Target is not available for the selected filters”, “”)
7. **Customer / Product Filter Check** = ISCROSSFILTERED(dim_product[product]) || ISFILTERED(dim_customer[customer])
8. **Forecast Accuracy %** = IF([ABS Error %]<>BLANK(), 1 – [ABS Error %], BLANK())
9. **Forecast Accuracy % LY** = CALCULATE([Forecast Accuracy %], SAMEPERIODLASTYEAR(dim_date[date]))
10. **Forecast Qty** =                              
var lsalesdate = MAX(LastSalesMonth[LastSalesMonth])                                
return                                                                                          
CALCULATE(SUM(fact_forecast_monthly[forecast_quantity]), fact_forecast_monthly[date]<=lsalesdate
11. **Freight Cost $** = SUM(fact_actuals_estimates[Freight_cost])
12. **GM / Unit** = ([GM $]/[Quantity])
13. **GM %** = DIVIDE([GM $],[NS $],0)
14. **GM % BM** =                              
SWITCH(TRUE(),                             
SELECTEDVALUE('Set BM'[ID])=1,[GM % LY],                             
SELECTEDVALUE('Set BM'[ID])=2,[GM % Target])                       
16. **GM % Filter** =                            
var res = SELECTEDVALUE('Target Gap Tolerance'[Target Gap Tolerance])                            
return                        
IF([GM % Variance]>=res,1,0)                   
17. **GM % LY** = CALCULATE([GM %], SAMEPERIODLASTYEAR(dim_date[date]))
18. **GM % Target** = DIVIDE([GM Target $],SUM(NsGmTarget[ns_target]),0)
19. **GM % Variance** = [GM % BM] - [GM %]
20. **GM $** = [NS $]-[Total COGS $]
21. **GM Target $** = SUM(NsGmTarget[gm_target])
22. **GS $** = SUM(fact_actuals_estimates[gross_sales_amount])                              
23. **Last Sales Month Footer** =                           
“Sales Data Loaded Until : ” & FORMAT(MAX(LastSalesMonth[LastSalesMonth]), “MMM YY”)                             
24. **Manufacturing Cost $** = SUM(fact_actuals_estimates[manufacturing_cost])
25. **Market Share %** = DIVIDE(SUM(marketshare[sales_$]),SUM(marketshare[total_market_sales_$]), 0)
26. **Net Error** = [Forecast Qty]-[Sales Qty]
27. **Net Error %** = DIVIDE([Net Error],[Forecast Qty],0)
28. **Net Error LY** = CALCULATE([Net Error],SAMEPERIODLASTYEAR(dim_date[date]))
29. **Net Profit %** = DIVIDE([Net Profit $],[NS $],0)
30. **Net Profit % LY** = CALCULATE([Net Profit %], SAMEPERIODLASTYEAR(dim_date[date]))
31. **Net Profit % Target** = DIVIDE([NP Target $],SUM(NsGmTarget[ns_target]),0)
32. Net Profit $ = [GM $]+[Operational Expense $]
33. **NIS $** = SUM(fact_actuals_estimates[net_invoice_sales_amount])
34. **NP % BM** =                      
SWITCH(TRUE(),                         
SELECTEDVALUE(‘Set BM'[ID])=1, [Net Profit % LY],                      
SELECTEDVALUE(‘Set BM'[ID])=2, [NP Target %])                       
35. **NP Target %** = DIVIDE([NP Target $], SUM(NsGmTarget[np_target]), 0)
36. **NP Target $** = SUM(NsGmTarget[np_target])
37. **NS $** = SUM(fact_actuals_estimates[net_sales_amount])
38. **NS $ LY** = CALCULATE([NS $], SAMEPERIODLASTYEAR(dim_date[date]))
39. **NS Target $** =                           
var tgt = SUM(NsGmTarget[ns_target])                            
return IF([Customer / Product Filter Check], BLANK(), tgt)                                
40. **Operational Expense $** = ([Ads & Promotions $]+[Other Operational Expense $])*-1
41. **Other Cost $** = SUM(fact_actuals_estimates[other_cost])
42. **Other Operational Expense $** = SUM(‘fact_actuals_estimates'[other_operational_expense])
43. **P & L BM** =                       
SWITCH(TRUE(),                            
SELECTEDVALUE('Set BM'[ID])=1,[P & L LY],                          
SELECTEDVALUE('Set BM'[ID])=2,[P & L Val Target])                                                 
44. **P & L Chg** =                            
var res = [P & L Val]-[P & L BM]                           
return IF([P & L BM]=BLANK() || [P & L Val]=BLANK(),BLANK(),res)                            
45. **P & L Chg %** = DIVIDE([P & L Chg], [P & L BM], 0) * 100
46. **P & L Final Value** = SWITCH(TRUE(),                                     
SELECTEDVALUE(fiscal_year[fy_desc])=MAX('P & L Columns'[Col Header]),[P & L Val],                             
MAX('P & L Columns'[Col Header])="BM",[P & L BM],                        
MAX('P & L Columns'[Col Header])="Chg",[P & L Chg],                         
MAX('P & L Columns'[Col Header])="Chg %",[P & L Chg %]                           
)                           
47. **P & L LY** = CALCULATE([P & L Val], SAMEPERIODLASTYEAR(dim_date[date]))
48. **P & L Val** =                      
var res = SWITCH(TRUE(),                                
MAX('P & L Rowss'[Order])=1,[GS $]/1000000,                              
MAX('P & L Rowss'[Order])=2, [Pre Invoive Deduction $]/1000000,                         
MAX('P & L Rowss'[Order])=3, [NIS $]/1000000,                          
MAX('P & L Rowss'[Order])=4, [Post Invoive Deduction $]/1000000,                             
MAX('P & L Rowss'[Order])=5, [Post Invoive Other Deduction $]/1000000,                            
MAX('P & L Rowss'[Order])=6, [Post Invoive Total Deduction $]/1000000,                          
MAX('P & L Rowss'[Order])=7, [NS $]/1000000,                             
MAX('P & L Rowss'[Order])=8, [Manufacturing Cost $]/1000000,                               
MAX('P & L Rowss'[Order])=9, [Fright Cost $]/1000000,                             
MAX('P & L Rowss'[Order])=10, [Other Cost $]/1000000,                                 
MAX('P & L Rowss'[Order])=11, [Total COGS $]/1000000,                           
MAX('P & L Rowss'[Order])=12, [GM $]/1000000,                           
MAX('P & L Rowss'[Order])=13, [GM %]*100,                       
MAX('P & L Rowss'[Order])=14, [GM / Unit],                          
MAX('P & L Rowss'[Order]) =15, [Operational Expense $]/1000000,                             
MAX('P & L Rowss'[Order]) =16, [Net Profit]/1000000,                          
MAX('P & L Rowss'[Order]) =17, [Net Profit %]*100                              
)                              
return                                   
IF(HASONEVALUE('P & L Rowss'[Description]),res,[NS $]/1000000)                                      
49. **P & L Val Target** =                              
var res = SWITCH(TRUE(),                               
MAX('P & L Rowss'[Order])=7, [NS Target $]/1000000,                             
MAX('P & L Rowss'[Order])=12, [GM Target $]/1000000,                         
MAX('P & L Rowss'[Order])=13, [GM % Target]*100,                                
MAX('P & L Rowss'[Order]) =17, [Net Profit % Target]*100                          
)                         
return                                 
IF(HASONEVALUE('P & L Rowss'[Description]),res,[NS Target $]/1000000)                            
50. **Performance Visual Title** = [Selected P & L Row] & ” Performance Over Time”
51. **Post Invoice Deduction $** = SUM(fact_actuals_estimates[post_invoice_deductions_amount])
52. **Post Invoice Other Deduction $** = SUM(fact_actuals_estimates[post_invoice_other_deductions_amount])
53. **Pre Invoice Deduction $** = [GS $] – [NIS $]
54. **Quantity** = SUM(fact_actuals_estimates[Qty])
55. **RC %** = DIVIDE([NS $],CALCULATE([NS $],ALL(dim_market), ALL(dim_customer), ALL(dim_product)))
56. **Risk** = IF([Net Error]>0,”EI”, IF([Net Error]<0, “OOS”, BLANK()))
57. **Sales Qty** = CALCULATE([Quantity], fact_actuals_estimates[date]<=MAX(LastSalesMonth[LastSalesMonth]))
58. **Sales Trend Title** = “NS & GM % For ” & SELECTEDVALUE(dim_customer[customer])
59. **Selected P & L Row** = IF(HASONEVALUE(‘P & L Rows'[Description]), SELECTEDVALUE(‘P & L Rows'[Description]), “Net Sales”)
60. **Top / Bottom N Title** = “Top / Bottom Products & Customers By ” & [Selected P & L Row]
61. **Total COGS $** = ‘Key Measure'[Freight Cost $] + ‘Key Measure'[Manufacturing Cost $] + ‘Key Measure'[Other Cost $]
62. **Total Post Invoice Deduction** = ‘Key Measure'[Post Invoice Deduction $] + ‘Key Measure'[Post Invoice Other Deduction $]

#### This project taught me, creating a report is not enough for a Data Analyst. Technical Skills, Soft skills, being a good team player, a problem-solving mindset and get it done attitude are also needed to perform any task in this role.
