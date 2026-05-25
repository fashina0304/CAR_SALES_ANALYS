# CAR_SALES_ANALYS
THIS IS A CAR SALES REPORT ANALYS IT BRINGS AN INSIGHT TO HOW THE SEALS WAS CARRIED OUT BY REGION ETC
## CAR SALES DATA ANALYS 
>THIS IS A CAR SALES

>IT COVER ALL COMPANY ETC.
---
## PROJECT OVERVIEW
__In this project, I worked with a car sales dataset to analyze sales performance, customer behavior, and revenue trends using Excel, Power BI, SQL, and Python. The goal of the project was to turn raw sales data into meaningful insights that can help a car company make smarter business decisions.__

## DATA SOURCES: KAGGLE.COM
## Data Outlay
|Car_id|	Date|	Customer Name|	Gender| Annual Income|	Dealer_Name|	Company|	Model|	Engine|	Transmission|	Color|	Price ($)|	  Dealer_No| 	Body Style| Phone|	Dealer_Region|
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
|C_CND_000001|	1/2/2022|	Geraldine|	Male|	1350|	Buddy Storbeck's Diesel Service Inc|	Ford| Expedition|	DoubleÃ‚Â Overhead Camshaft|	Auto|	Black|	26000|	06457-3834| SUV|	8264678|	Middletown|
|C_CND_000002|	1/2/2022|	Gia|	Male|	1480000|	C & M Motors Inc|	Dodge| Durango|	DoubleÃ‚Â Overhead Camshaft|	Auto|Black|	19000|	60504-7114|	SUV|	6848189|	Aurora|
|C_CND_000003|	1/2/2022| Gianna|	Male|	1035000|	Capitol KIA|	Cadillac|	Eldorado|	Overhead Camshaft|	Manual|	Red|	31500|	38701-8047|	Passenger|	7298798|	Greenville|

## TOOLS USED
###  Excel Pivot Table:
+ _For summarizing the car sales data_
+ _For exploring trends across regions, companies and gender_
+ _For building an interactive dashboard to visualize the findings_
 ___
 
###  Power BI:
+ _For creating an interactive dashboard_
+ _For visualizing sales performance across different categories_
+ _For filtering data by year, region and company_
+ ___

### MySQL Workbench:
+ _For storing and querying the dataset_
+ _For retrieving and filtering specific car sales records_
+ _For aggregating data to find totals, averages and customer segments_
+ _For writing queries to identify top selling car models and most popular car colors_
+ _For segmenting customers into Gold, Silver and Bronze categories based on their annual income_
___

###  Python Jupyter Notebook:
+ _For loading the dataset using Pandas_
+ _For exploring the structure and content of the data_
+ _For displaying the top and bottom rows of the dataset_

  ```SQL
  select * from new_car_dataset2 where "price ($)">400000;
 ```

```SQL
SELECT * FROM new_car_dataset2 WHERE DEALER_REGION = 'AUSTIN';
```



























