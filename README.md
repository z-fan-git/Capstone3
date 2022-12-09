## Introduction

The transnational data has been collected from 2009-12-01 to 2011-12-09 for a UK-based and registered non-store online retail. The 1044848 records of customer ID, price, quantity, invoice date, description, and country are included in the data set. The manager is interested in targeting customers for developing business development strategies. This project will use various features, e.g., Recency, Frequency, and Monetary Value (RFM), for customer segmentation and explore the difference among customer groups.

## Procedure
This project is implemented by following the procedure below.
* a. Problem Identification 
* b. Data Wrangling
  * Check data integrity 
  * Clean data: missing values, duplicates, etc. 
* c. Exploratory Data Analysis
  * Identify important features
  * Statistical property analysis
  * Visualize data
  * Identify trends and patterns
* d. Pre-Processing & Clustering
  * Recency (R) calculation and clustering
  * Frequency (F) calculation and clustering
  * Monetary (M) calculation and clustering
  * RFM value calculation and clustering
  * RFM+Price+Quantity clustering

## Examples of custmoer clusters
* Three clusters based on <font color=blue>RMV values</font>
<img src="https://user-images.githubusercontent.com/44271543/206778886-3aef85ca-d93a-42eb-acfe-2d7524cf38a7.png" alt="clusters" width="800"/>

* Two clusters based on <font color=blue>RMV values, price, and quantity</font>
<img src="https://user-images.githubusercontent.com/44271543/206778354-ec486ab4-b7a6-4497-ba1a-bc3a27fe4c93.png" alt="clusters" width="800"/>

* Three clusters based on <font color=blue>RMV values, price, and quantity</font>
<img src="https://user-images.githubusercontent.com/44271543/206778216-5ea4ef90-fb2f-400d-a03e-3b62115c4610.png" alt="clusters" width="800"/>
