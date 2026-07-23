BUILDING A DATA MODEL FOR POWWER BI

Project Clean Model PB

Objective: To create data model from 23 data tables of a business process of a Sales Business Process. 

To achieve the following steps and techniques were followed 
1.	Cleaning of data in a table for blank space, duplicate, date and other number formatting, following naming convention snake_case. 
2.	Identification of a group of potential dimension tables and club them by using keys. In this process merger and append steps were used. 
3.	Identification of table with business events and refine them to fact_table. Extract the elements which can be send to a fact_table and connect all by keys. This shall reduce the size of the model and more manageable. 
4.	Identify the columns and table which are either garbage or not required at all for the business intelligence requirements of the user. 
5.	Progressively create dimension table and fact table for a better understanding and efficiency. 
6.	Built a date dimension and connect the fact tables. This shall keep all the date function under one date table. 
7.	Built security function for restricted access of the data form the fact tables. Row Level Security policy is applied. A dynamic security policy was implemented using DAX function. 
8.	The data model was extensively tested to test all relationship. 

The final data model view is given below. The Power BI file and excel file is attached for deeper understanding of the work. 

It took around 8 hours to build and test the data model. 
In this directory POWER BI work file and the data file in EXCEL for mat is included. 

<img width="1256" height="638" alt="data_model" src="https://github.com/user-attachments/assets/e75cc2ab-68b5-4935-81b0-58b446fc4573" />
