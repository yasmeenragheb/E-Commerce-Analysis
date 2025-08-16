# E-commerce Logistics Operations Project

This project is based on a case study I completed during a technical assessment as part of a job application process.

## Overview:
This case study simulates real-world e-commerce logistics operations using three interconnected datasets: Orders, Deliveries, and Products. The goal is to analyze the data and uncover insights that can help improve efficiency and customer satisfaction.

## Steps:
### 1. Data Cleaning & Transformation:
  * Create a *Date table* using DAX
  * Deliveries Table :
    * Add a Status Column to classify each order as either "Late" or "On Time" based on the actual delivery date compared to the expected delivery date.


### 2. Data Modeling
*Fact Table*: Orders

*Dimension Tables*: 
Products 
Date 
Deliveries 
### This is how the star schema looks:
<img width="1289" height="784" alt="Model" src="https://github.com/user-attachments/assets/2b0bf627-4560-41cc-b8a9-93e9e163de3c" />

### 3. Power BI
#### Create some measures like:
 Order Confirmation, Rate Ship, Rate Delivery Rate, Delivery On Time%, Average Delivery Delay (days), Late Orders, and so on.. 


#### Create a  report of two pages

### 1. Overview:
<img width="1399" height="779" alt="Overview" src="https://github.com/user-attachments/assets/3f8d509a-9fc4-4791-a406-0bef395901b3" />

### 2. Late/on-time Orders:
<img width="1396" height="783" alt="Orders" src="https://github.com/user-attachments/assets/0ccdf3c4-a088-4446-b84f-db0bfa712599" />




