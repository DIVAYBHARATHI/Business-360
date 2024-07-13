# Business 360

**Project overview**

 AtliQ Hardware is growing rapidly in the recent year, they have decided to implement data analytics using Power BI is a strategic move. By leveraging Power BI, they can gain insights across various aspects like finance, sales, marketing and supply chain. This will empower stakeholders with data-driven answers, helping them make informed decisions. 
     
I worked on this project by following the Code basics Power Bi Course, Link to the course is here
https://codebasics.io/courses/bootcamp/1/power-bi-data-analysis-with-end-to-end-project/lecture/974

**Live Report Link**

https://app.powerbi.com/groups/me/reports/2f294fb7-96b5-43ee-ae3d-df18ecb3ba82/ReportSection0e765c0061580b067c73?experience=power-bi&clientSideAuth=0

**Tech stacks**

   - Excel
   
   - SQL
   
   - Power Bi Desktop
   
   - DAX language
   
   - DAX studio (for optimizing the report

**Power BI techniques Learnt**
   
  - What are all the questions should be asked before staring the project

  - Creating calculated columns

  - creating measure using DAX language

  -	Data modeling

  -	Using Bookmarks to switch between two visuals

  -	Page navigation with buttons

  -	Using divide function to prevent zero division errors

  -	creating date table using m language

  -	Dynamic titles based on the applied filters

  -	Using KPI indicators

  -	Conditional formatting the values in visuals using icons or background color

**Data validation techniques**

  -	PowerBi services
    
  -	Publishing reports to PowerBi services
  
  -	Setting up personal gateway to set up the auto refresh of data
  
  - PowerBi App creation
  
  -	Collaboration, workspace, access permissions in PowerBi services
    And even more.

**Business related terms**
  -	Gross price
  
  -	Pre-invoice deductions

  -	Post-Invoice deductions
  
  -	Net Invoice sale
  
  -	Gross Margin
  
  -	Net sales
  
  -	Net profit
  
  -	COGC - cost of goods sold
  
  -	YTD - Year to Date
  
  -	YTG - Year to Go
  
  -	Direct
  
  -	Retailer
  
  -	Distributors
  
  -	Consumer
  
  -	Company’s back ground

AltiQ Hardware, a rapidly growing company, has expanded its business globally. They specialize in selling computers and computer accessories through three primary medium / channels.

 -	Direct
   
 -	Retailers
 
 -	Distributors

**Dataset Understanding.**

   Understanding what data is available will be more helpful while doing analysis. Before diving into data analysis, Let’s get good understanding of what are data available.

 1.	Quantitative Data: This type of data consists of numerical values and can be measured. Examples include sales revenue, temperature, or the number of website visitors.
 
 2.	Qualitative Data: Qualitative data is descriptive and non-numeric. It includes categories or labels. For instance, customer feedback (positive, negative), product ratings (low, medium, high), or survey responses (yes, no).
 
 -	Fact table: It will have the data about the transactions
 
 -	Dimension table: It will have the static data like details of customer and products

**fact_forecast_monthly**

 -	This table is used to forecast the customer’s need in advance, which can help in
 
 -	Higher customer satisfaction
 
 -	Reduced cost in warehouses for storage purpose
 
 -	The table is denormalized by data engineering team, as it is a data warehouse which is aimed to be used for analytical work.
 
 -	All the date of the month will be replaced by the start date of the month
 
 -	It will have all the column names and in the end it will have the forecast quantity need of the customer

**fact_sales_monthly**
 
 -	This table is more or less is same as fact_forecase_monthly table, but the last column has the value of sold quantity instead of forecast value.

**gdb041:**

**dim_customer**
 
 -	27 distinct markets (ex-India, USA, Spain)
 
 -	75 distinct customers thorough out the market
 
 -	2 types of platforms
 
 -	Brick & Motors - Physical/offline store
 
 -	E-commerce - Online Store (Amazon, Flipkart)
 
 -	Three channels
 
 
 -	Retailer
 
 -	Direct
 
 -	Distributors
   
**dim_market**

 -	27 distinct markets (ex-India, USA, Spain)
 
 -	7 sub-zones
 
 -	4 regions
 
 -	APAC
 
 -	EU
 
 -	nan
 
 -	LATAM

**dim_product**

 -	Divisions
 
 -	P & A
 
 -	Peripherals 
 
 -	Accessories
 
 -	PC
 
 -	Notebook
 
 -	Desktop
 
 -	N & S
 
 -	Networking
 
 -	Storage

There are 14 different categories, Like Internal HDD, keyboard
There are different variants available for the same product

**gdb056**

 -	freight_cost
This table has details of travel cost and other cost for each market with fiscal year
 
 -	gross_price
Has the details of gross prices with product code
 
 -	manufacturing_cost
Has the details of manufacturing cost with product code with year
 
 -	Pre_invoice_dedutions
Has the details of pre invoice deductions percentage for each cutomer with year
 
 -	Post_invoice_deductions
Post invoice deductions and other deductions details
 
 -	Importing data into PowerBi
As the database is MySQL in this project, we need to import the datasets from Mysql database to PowerBi by providing the Database access credential
 
 -	Data Model
  -	Data modeling plays a vital role and is considered as the basement of report. All the visuals will be build upon the data model.
  -	Poor data modeling affects the over all performance of the report.
 
In this project, we have followed Snowfall data modeling method.

**Dashboard designing**

Based on the mock ups received as requirement, the team will start designing the visuals and create measure as and when required

**Home view**

In Home view, all the views button will be available. User will land on specific view page by clicking the button

  -	Info
  
  -	Finance View
  
  -	Sales View
  
  -	Marketing View
  
  -	Supply chain View
  
  -	Executive View
  
  -	Products
  
  -	Support

Overall Report


Info Page
![Info view](https://github.com/user-attachments/assets/c1ee6ea2-8a49-4598-8f73-97cb9e40fb37)



Finance View



Sales View

![Sales view](https://github.com/user-attachments/assets/56fb1260-2f11-435d-beb8-7286010a5012)

Marketing View

![Marketing view](https://github.com/user-attachments/assets/42b53e00-bf0c-4375-8f1a-b13267df8cd7)

Supply chain View

![Supply Chain View](https://github.com/user-attachments/assets/22888953-0f17-4c92-aa9f-11e6b7e7e24b)

Executive View

![Executive View](https://github.com/user-attachments/assets/e3f340ea-6b01-42b0-b34f-066d2a89499b)

Support View

![Support View](https://github.com/user-attachments/assets/318d0380-d8c0-4c34-93bc-3050cca3645a)




**Project Outcome**

 By using this report, decisions can be taken based on the data. Further it will help in answering n number of "why" questions based on the situations.

