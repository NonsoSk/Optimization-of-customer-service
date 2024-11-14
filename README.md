# Optimization-of-customer-service

![optim main](https://github.com/user-attachments/assets/97b80ff1-3d06-4931-acde-b5498483aedd)

## Overview

After successfully completing my excel course on data analysis, I decided to challenge myself with a project to show extensively all that I’ve learnt.
Thus the project is an excel based analysis of the data gotten from a superstore in the United States.
This store seeks to focus more on production of desired goods to her targeted customers; optimizing the most accessible means of shipping; and generally improving her services to her customers.
For the sake of this analysis, we consider this year to be 2017. Thus the dataset is up to date as it contains information from 2014 to this “present” year (2017). 

## Introduction
This is a sales and performance analysis of a superstore. The problems to be addressed by this analysis are:
1)	Determine the category of product that has the highest sales record and show how this product has been sold over the years.
2)	Find out the year it recorded its least performance and trace its profit trend through the months.
3)	Find out the best shipping mode for the company
4)	What is the most demanded product in 2017 and what category of product is it?
5)	What customer segment contribute more to the total revenue of the company? (To help us know who to channel our products to)
6)	On average, how long does it take products to be delivered from their ordered date?

These are the basic questions that would be addressed in this analysis. However, in the course of the analysis, we shall show different KPIs for proper understanding of this project.
The reason for this project is to have an extensive and comprehensive view of the performance of the store, so as to recommend the best ways and strategies for the optimization of  the services rendered by the company to her customers. 


**I demostrated the following skills in this project**

1) Data Cleaning.
2) Pivot Tables.
3) Pivot Chart.
4) Data Visualization.
5) Critical Thinking.
6) Problem Solving

## Data sourcing
I obtained the data by downloading the csv file from my drive and then imported and converted into an excel file. The data is a sample data of The US superstore.
After the conversion, I cleaned the data, performed my analysis and created visualizations to help answer my questions.

## Data Transformation and cleaning
The US superstore dataset did not really require much cleaning, I checked for spelling error and found none except for local cities or names that weren`t registered in the dictionary. Since they were not errors, I had to ignore it.  I also searched for duplicates, but found none and so after formatting the headers and making my data neat, I proceeded to the next step.


## Analysis and visualization
I analyzed the data step by step according to the questions and aim of my analysis. The visuals I created were very easy-to-understand. I used the colors: blue, green, red, Faded-blue, which all meant different things at different points of my analysis.
All seven visuals passed different messages all related to the analysis.
Some of the information represented in the visuals are:
- sum total of products over the years
- Total number of ships per shipping mode
- Highest contributing  segment to profit
- Average processing time for each category

In the first visual, we set out to determine the category of product that has the highest sales record and to show how this product has been sold over the years.

We began by finding the highest sold category of product over the years.
Considering the fact that they are three (3) categories of product, I used the “sum if” function to calculate the total quantity sold for all three (3) products. Example, to calculate the quantity of “office supplies” sold, I used the formula below: **=SUMIF(O2:O9995,"office supplies",S2:S9995)**. This I did for all other categories only changing the criteria required by the formula.
I thus represented this in a pivot table and created a visual from here.
Below is the result of the pivot and visuals we created:

![visual 1 of 1](https://github.com/NonsoSk/Optimization-of-customer-service/assets/147613828/ca1ba322-3a39-447e-a79f-ed3cfb669d21)



From the above, we can see that the highest sold product over the years is the “office supplies” which records “22906” quantities sold. 

Moving further, we traced how this “office supplies” have been sold from 2014 to 2017.

![visual 2 of 1](https://github.com/NonsoSk/Optimization-of-customer-service/assets/147613828/9b372a03-2e2a-4b01-b8bf-174f3fe7a126)

We noticed that the sales of office supply products increased as the years went by, which is an indication that the company has been consistent in improving the quality of the service it renders.

Having made evident how the sales of office supplies went through the years, it was easy to identify the year it had its least sales, which from our analysis is “2014”.
This thus helped in our analysis and problem solving of the second question which requested that we Find out the year it recorded its least performance and trace its profit trend through the months.
We created a second pivot table and visual to represent this:

![visual 2](https://github.com/NonsoSk/Optimization-of-customer-service/assets/147613828/40688879-e74a-4125-84d5-ceef9a0c682d)


Very noticeable is the fact that in 2014, the company recorded a negative profit in July which happens to be the middle of the year, and then picked up afterwards. 
Positively, it means that the company evaluates herself once (the mid-year) every year.



In the third visual, we showed the best shipping mode by evaluating the number of times each shipping mode was used.
There are four (4) ship mode and so, we used the COUNTIF function to determine this. E.g. for the “standard class”, I used the formula:  **=COUNTIF (E2:E9995,"standard class")**, where E2:E9995 stands for the range, I.e. the column where the “standard class” is. I applied same formular in finding the number of times other modes of shipping were used.

Having established this fact, I created a pivot table to aid  understanding and then a visual to help us understand even better.

![visual 3](https://github.com/NonsoSk/Optimization-of-customer-service/assets/147613828/2230832a-81b9-4584-aa76-466ffabd4f31)


from the above, we see that the highest used means of shipping or delivering products is the "standard class". However, the number of times the "same day" delivery was used as a means of shipping is very minimal and this is something of great concern.
This is an indication that the company is not so close to her customers and that is why it finds it difficult to deliver products on same day of order.


To analyse and solve the problem posed by the fourth question about finding the most demanded product in 2017 (Remember we are working with 2017 as our current year) and what category of product it is, we had to use the pivot table and below is the result:

![visual 4](https://github.com/NonsoSk/Optimization-of-customer-service/assets/147613828/2f5bf1b6-3475-4c00-872b-ee74e5ac8bac)

The highest demanded product is "Binders". To know the category where it falls, we used the **VLOOKUP** fuction. Thus, we used the formula **=VLOOKUP(O15,O2:P9995,2,"false")**
and discovered that "Binders" is a sub-category of "office supplies". 
This goes on to confirm that office supplies is the highest demanded cum sold product in the store.


All along, we have had wonderful analyses on the products of the store, our concern now is on the customer segment that contributes more to the total profit of the store.
Already, we had calculated our total profit as **$286,397.02**, using the **SUM** function, and then noted also that the profit margin is 12% ( we achieved this by dividing total profit total revenue and then conerting to percentage) we then created a pivot table which preceeded our visualization.


![visual 5](https://github.com/NonsoSk/Optimization-of-customer-service/assets/147613828/b88454c3-c9f1-418b-938f-bd670000ae6c)

From the above, we see that the highest contributing segment to the total revenue of the company is the "consumer" and the least is the "home office".


The last visuals, displayed the processing order time per product category. That is to say, we tried to show how long it takes for products to be delivered from the time of their order to the time of delivery.  to achieve this, we added a column to our original data that showed the order processing time, then we proceeded to creating our pivot table which showed the average time for all three categories of products.

![visual 2 of 6](https://github.com/NonsoSk/Optimization-of-customer-service/assets/147613828/0b0567e1-b848-49bd-b4ee-7655ccd7606a)


On average, it takes 3 to 4 days for products to be delivered. However, our concern is drawn to the fact that despite "office supplies" being the most demanded product, it takes the longest time to be delivered.


## Recommendations and Conclusions

- From our analysis, it is clear that the highest sold products are those under the office supplies category. Thus the company should improve the quality in every angle of the products that fall under this category. 
- we noticed that the sales of office products increaesed drastically every year. The company should thus endeavor to evaluate herself more than once every year, so as to be able to grow and produce maximal satisfaction to her customers and not just a once in a year analysis as suggested by the analysis carried out and shown in our second visual above.
- I noticed that the "standard class" is the most preffered means of shipping by the customers. I recommend then that the company should, without neglecting other means of shipping, put more effort to seeing that it improves the "standard means" of shipping so as to reduce the order processing time.
- I also noticed that very few times have goods been delivered on same day of delivery. This says a whole lot about the proximity of the company to her custommers. I recommend that the company expands by building branches which would be nearer to her customers to meet the needs of these customers.
- The minimal number of times the "same day" ship mode is used, suggests also that the fee attached to same day delivery must be very high as to have scared customers from adopting such means. I recommend then that the fee be subsidized to eneble customers use this means of shipping, as this would go a long way to add to the credit of the company because customers would be naturally impressed if what they ordered for gets to them as quick as possible. Thus, with same day delivery, customers would be able to order and buy much more products, trusting and knowing that they would always get them immediately.
- In 2017, we discovered that the highest demanded and invariably the most sold product is the binders which is still a sub-category of office supplies. Thus evident enough is the fact that office supplies is of great importance in the market and so would be of great demand in the market at large. I recommend then that the company increases the quality of her office supply products so as to stand out in the market community.
- I noticed also that the greatest contributor to the total revenue is the consumer. This means that the products that generate the greatest profit are products used for personal and individual purposes. Thus since we have a target customer. I recommend that the company makes her products more **"user-friendly"** so as to meet the needs of consumers who mostly use the products for personal and individual purposes. Generally, all products should be more user-friendly.
- Lastly, I noticed that the average time it takes for goods to be delivered is 3 to 4 days. This might seem as a very appropriate time. However the concern is with the most demanded products (office supplies), taking the longest time to be delivered. I recommend that the company improves her shipping mode to enable faster deliverance of products especially office products. If the company must stand out amongst her competitors, then it must work on reducing the order processing time of office products.





### Thanks for reading through.
