Problem Statement: To  create and analyse the data set for relevant logical patterns

Feature Descriptions:

Feature 	          				Description

Entity_ID	                 	 	Unique Entity ID

Gender	                 	 		Male/ Female

Marital Status                	 		Entity married (Y/N)

Dependents	          			Number of dependents of an Entity

Education	          			Entity  Education ( Ph.d / PG / UG / Not educated )

Entity’s Income		          		Entity income in INR per month

Entity’s Family Income  			Entity Family Income per month includes Entity’s 
                                                                        Income

City Type          				Type of City [A,B,C,D]

Average Expenditure per 
Entity per Month				Amount in INR


Note: Depending on the city type the average expenses per entity per month is as given below

City Type	Average_Expenses in INR
A		15,000 
B		10,000 
C		5,000 
D		2,500 


Dataset size: 50,000 rows (minimum)  with above features as mandatory and other additional features desired and derived as you feel deemed fit

Note: Training data : 80%
          Test Data: 20%


 
Random Technique to be applied:

1.	To choose an option to enter data for a feature is  by tossing the coin

2.	If the Coin turns out to be head, then roll a dice with number of faces equal to the number of options a feature can take as given above; In case of a tail enter a predefined option

3.	Task _1: To create a dataset by applying random techniques as mentioned  above

4.	Task_2: To apply appropriate method to analyse the data set and build a model typically supported by visualisation if any

5.	Task_3: To indicate various metrics to measure the performance of the model


 
Tasks and Questions to be answered using python notebooks

1.	Create the Data Set
		
Perform Data analysis by answering all the questions by handling possible exceptions and constraints that may occur

a.	What is the typical shape of the training and testing data ?

b.	Number of Families countif the number of dependents are >0

c.	Number of Single and Married Entities

d.	Entity: Average Income

e.	Entity: Average Family Income

f.	How many Entities are Single and Married ?

g.	How many entities are Educated and Uneducated ?

h.	How many Entities at the end of the year can make savings financially ?

i.	How many Entities at the end of the year are break even financially ?

j.	How many Entities at the end of the year may need loan financially ?

k.	How many Entities can afford  car loans ?

l.	How many Entities can afford Home Loans ?

m.	How many Entities can be advised on Savings and Loans ?

n.	Categorize every entity_id economic status as 
[ Excellent, Good, Moderate, Average, Poor ]

o.	Build a prediction model to find the new entity’s Economic status  

p.	Perform metric level analysis of the model
