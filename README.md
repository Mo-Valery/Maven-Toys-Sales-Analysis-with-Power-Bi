# Maven Toys Store Sales Analysis

### Introduction

This Data Analysis Project was birthed in course of my work with the Digitaley Drive Team. The dataset was provided by the Team and I have been saddled with the interesting task of cleaning, visualing and analysing it.
Kindly follow along for a wonderful experience as I explore the data visualization world of Power Bi Desktop and Micrsosoft PowerPoint to analyze the data.

### Project Overview

This Project delves into the Maven Toys Store dataset over the period of January 2022 to September 2023 to analyse various areas of their sales performance during the said period. This would enable us identify trends, gain deep understanding of the Store's performance and make data-driven recommendations.

### Data Source

This analysis comprises of 4 Tables :

1. Calendar with 1 column and 638 rows; 
2. Products with 5 columns and 35 rows;
3. Sales with 9 columns and 829,262 rows; and
4. Stores with 5 columns and 50 rows.

The 'sales' table is the primary dataset used for this analysis in the "sales.csv" file, containing detailed information about all sales made by all Maven Toys Stores.

### Software Used and Version

- Microsoft Power Bi - Version: 2.142.928.0 64-bit (April 2025)
- Microsoft PowerPoint 2016 MSO (16.0.4266.1001) 64-bit

### Data Transformation

The datasets were efficiently cleaned and transformed in the Power Query Editor of my Power Bi Desktop with the performed tasks outlined seriatim :

1. Including 2 more columns in my "caledar.csv" being `Start of Month` and `Start of Week` from the 'Date' dropdown of the 'Add Column' tab. This is to enable me easily draw visual analysis during data visualization. See uploaded picture "mts_power_query_editor.png".
2. Changed the datatypes of all the columns with dates to reflect the right datatype, that is, from 'Number' to 'Date'.
3. 'Close & Apply' to have my transformation inputted and return to the Power Bi Desktop.

### Data Modelling

The 'Model View' of my Power Bi already connected my "products.csv" and "stores.csv" to my "sales.csv". I however had to connect "calendar.csv" to the "sales.csv" as shown in the uploaded image "mts_model_view.png". 

![Maven Toys Data Modelling](mts_model_view.png)
