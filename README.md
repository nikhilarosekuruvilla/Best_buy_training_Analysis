# Best_buy_training_Analysis
Analysis of salesperson training in Best Buy

## Background
* Companies like Best Buy sell bundled products to increase profits. 
* Best Buy focuses on warranty sales i.e. the Geek Squad protection plan

## Research Question
* Identify customers who have high propensity to purchase the protection plan , so we can provide a data driven proposal for a potential marketing strategy 


## Key Variables & Control Variables
* Dependent variable : Warranty
* Key Independent Variable : PriceCategory*appliances,hisp,hhincome,familysize
* Control variables : age, newcustomer, weekend , MyBestBuy

## Theoretical Model 
* Warranty ~ β0 + β1PriceCategory*Appliances + β2Age + β3Hispanic + β4MyBestBuy + β5Income + β6FamilySize + β7Weekend + β8NewCustomer+β9 Pricecategory + β10 Appliances

## Insights
> * Home appliance products have 35 percentage points higher likelihood of buying warranty in lower price category compared to higher price category. 
> * Non- home appliance products have 49 percentage points higher likelihood of buying warranty in higher price category compared to lower      price category.
![figure1](https://github.com/nikhilarosekuruvilla/Best_buy_training_Analysis/blob/master/Images/Insight_1.png)

> * A customer with a family of 3 - 4  members has 21 percentage points higher likelihood of buying warranty compared to a customer with a  family of 1-2 members.
![figure1](https://github.com/nikhilarosekuruvilla/Best_buy_training_Analysis/blob/master/Images/Insight_2.png)

> * The higher the income of a customer , the higher the likelihood of purchasing warranty.
![figure1](https://github.com/nikhilarosekuruvilla/Best_buy_training_Analysis/blob/master/Images/Insight_3.png)

## Recommendations

#### Customers centric strategy:
* High income 
* Family size 3 and 4 

#### Product centric strategy :
* Home appliances that have low prices
* Non-home appliances that have high prices. 		

## Limitations
* Biased data 
    1. Relatively small sample size.
    0. Only includes customers between the ages 52 and 86.
    0. Family size only goes up to 4 .
    0. There are many other variables that could strengthen our model (yearly data , holiday data, additional data, etc.)
