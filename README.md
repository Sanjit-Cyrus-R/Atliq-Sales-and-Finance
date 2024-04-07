# Atliq-Sales-and-Finance
## Problem Statement
Atliq Hardware is a computer hardware manufacturing company that manufactures hardware products like Keyboard, Mouse, Monitor Etc. Their business model is to manufacture the goods in their manufacturing unit and sell it to various types of customers. Atilq is now a developing company and there is a lot of data in the company. The company is moving towards data analysis in order to make sense of the data. This project aims to use excel to create a sales and Finance report in order to make data driven decisions. 

## Atliq Business Model
All throughout the world, Atliq sells its goods to various clients. They sell their goods to both online retailers like Amazon and Flipkart as well as offline distributors with real stores like Croma and so on. Customers of **Brick and Mortar** stores are those who shop in physical stores, while those who shop online are classified as **E-Commerce**. These two businesses—Brick and Motor and E-Commerce—fall under the larger **retail** category. **Direct** is the revenue channel that Atliq uses for their own E-Commerce and retail store. Additionally, there is an additional customer channel known as **Distributor**. This is because Atliq is unable to sell directly in some countries, such as China, instead they sell via the distributor. 

The products are divided into various divisions based on their usage 
+ **N & S** - Networking and Services
+ **P & A** - Peripherals and Accessories
+ **PC** - Personal Computers

## Information about the Dataset and Brief Execution Methology 
The Data is there in dimension tables and Fact tables. The fact tables tell us the current running data and it is time based. The Dimension Tables are the tables which have more information on the fact tables

### Fact tables
+ Fact_Sales_monthly

### Dimension tables
+ dim_market
+ dim_customer
+ dim_date (created during Data Transformation)
+ dim_product
+ ns_target (Net sales target)

### Execution Methodlogy
Initailly the all the data is transformed using the power query option in Excel. Then a new table called dim_date is created so that we can display data according to the fiscal year. Atliq Fiscal year is from Sep to Aug. After Data has been transformed we move into Power pivot where we build a data model using the existing fact tables and dimension tables. The data model starts off like a star schema but eventually ends up as a snowflake schema. After this we create new measures in power pivot so that we can make these reports to our requirement. Then we open pivot tables in excel and drag and drop measures as and when needed to get the actual reports. We also use conditional formatting so that the stakeholders see the necessary data first and also the KPI - Key Process Indicators are hilighted. 


## Reports Explanation
Both Sales and Finance reports are there in the file. 
+ **Sales Report** - A sales report is a document that analyzes a company's sales activity over a specific period. It's a deep dive into how business is going and helps inform future decisions.
+ **Finance Report** - A financial report is document that summarizes a company's financial activities and health over a specific period. It's like a financial checkup for the business. 

## List of Reports
### Sales and Finance reports (With page number)
1. Customer Net Sales Performance (Page 1)
2. Market Performance vs target (Page 2)
3. Top 10 Products (Page 3)
4. Product Divison wise report (Page 4)
5. Top 5 products (Page 5)
6. Bottom 5 Products (Page 5)
7. New Products 2021 (Page 6)
8. Top 5 countries sales (Page 7)
9. P & L fiscal year (Page 8)
10. P & L By Fiscal year and Quarter (Page 9)

## Acknowledgements
I Thank Dhaval Patel and Hemmanand Vadivel for their amazing excel course through their codebasics website
