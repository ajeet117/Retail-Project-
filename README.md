# Retail-Project-



## Business Requirement 
1) Top/Bottom 5 product by Sales/Profit/Quantity Sold.
2) How do sales trends vary over time monthly?
3) Show relationship between sales & profit.
4) Compare sales/profit/quantity sold between any two periods selected by the user.
5) Discount offered in each discount category.
6) Total number of orders.
7) Show Sales/Profit/Discount/Net Sales/All remaining fields for each order that could be filtered using visual filters. (Product,Quater,Promotion Name,State)
## Problem Statement

This dashboard helps the retail to understand their sales,profit and quantity sold. It helps the reatil to know about their most selling product and the least selling product with the quanity sold for each and profit generate from them over the time. 

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a excel file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that there were all together 4 worksheet name dim customer, dim products, dim promotion, fact table. Found that the fact table have a null data. 
- Step 5 : With the help of the merge queries, related information were gather for the available table and all null values were removed. 
- Step 6 : In the report view, under the view tab, theme was selected.
- Step 7 : After Cleaning the data column chart was used to achieve the requirment 1
  <img width="897" height="465" alt="Requirement1" src="https://github.com/user-attachments/assets/24f3b647-a8d2-4987-9dc6-eac3cb5a7263" />
- Step 8: Line chart was used to achieve the requirement 2 with the slicer Year and Products
  <img width="889" height="465" alt="Requirement2" src="https://github.com/user-attachments/assets/60ec6d47-264a-4bfe-819a-5590aef66479" />
- Step 9: Scatter plot was used to achieve the requriement 3
  <img width="429" height="328" alt="Requirement3" src="https://github.com/user-attachments/assets/738c64a0-1c2e-496e-9f51-09b4eb5e28aa" />
- Step 10: Card visualize was used to achieve Requriement 6
  <img width="433" height="308" alt="Requirement6" src="https://github.com/user-attachments/assets/8bf86059-250c-412a-950b-035be6b6043f" />
- Step 11: Funnel Chart was used to achieve Requriment 5
  <img width="726" height="354" alt="Requiremnt5" src="https://github.com/user-attachments/assets/ab118bc6-8401-4745-b8b6-5d73433c0f43" />
- Step 12: Column Chart was used to achieve Requriement 7 with various slicer Product, Quater, Promotion Name, State
   DAX was used to make each slicer interactive with each other
  <img width="859" height="479" alt="Requirement7" src="https://github.com/user-attachments/assets/925c4ad5-d1d5-435f-8d5d-9f8281fe568d" />
- Step 13: Column chart was used to achieve Requirement 4 with two date slicer. To make chart and date slicer interact with each other DAX and table relationship were used
  <img width="886" height="470" alt="Requiremnt4" src="https://github.com/user-attachments/assets/92651f8b-b9bb-4a90-85eb-08f923465dfc" />






  
