# SelCheapy-Stores Profitability

![](SelCheapy_Stores.jpg)

## Introduction:
This is a PowerBI Project that Analysis the Profitability of **SelCheapy Stores**, a fictitious topmost Store that sells Bike and Accessories through Resellers that are spread across Europe, North America and Pacifics. Also, through direct Online Order by Customers.

## Problem Statement:
Over time, the Store decides to review its business model of using Resellers vis a vis direct online Order by Customers, as well as its Profitability over Four (4) Business Years cycle. This information will help them to rejig their business modelin order to enhance their profitability.

## DataSet:
The Raw DataSet is the Excel Sales file of  AdentureWorks 2019 provided by Oyinbooke.

It contains Seven (7) Tables,namely:
1.  Sales Order Data
2.  Sales Territory Data
3.  Sales Data
4.  Reseller Data
5.  Date Data
6.  Product Data
7.  Customer Data

## Skills Demonstrated:
Data Cleaning,Data Exploratory and Joining Skills was brought to the fore to create a Consolidated Table called **_Sales Table_** base on Primary and Foreign Key relationship of the other Six (6) Tables.

## Data Transformation/Modelling:
Columns with missing values and wrong entry were identified. For example, The Reseller and Customer Table with missing values were Normalized and Standardized in line with other entries in the respective Table.
The Reseller ID Column (Primary Key) in the Reseller Table, with value of [Not Applicable] was normalized to AW00000000 and other Columns with [Not Applicable] were normalized to “Online Order”.

Reseller(Dirty) 

![](Reseller_Table_Dirty.png)

Reseller(Clean)

![](Reseller_Table_cleaned.png)

Also  CustomerID Column  in the Customer Table(Primary Key) with value [Not Applicable] was normalized to AW00010000 and other Columns with [Not Applicable] were
normalized to “Online Order”.


