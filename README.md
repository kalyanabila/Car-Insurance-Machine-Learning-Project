# Car-Insurance-Machine-Learning-Project
Car Insurance Machine Learning Project


# Intro
Car insurance is a policy purchased by vehicle owners to mitigate costs associated with getting into an auto accident. The global auto insurance market size was valued at $ 739.30 billion in 2019, and is projected to reach $ 1.06 trillion by 2027, growing at a CAGR of 8.5% from 2020 to 2027. Auto insurance provides financial protection to customers against physical damage, resulting from traffic collision and theft of vehicles. In addition, it covers the cost associated with injuries, death, or property damage caused by insured owner of the vehicle to another driver, vehicle, or property such as fence, building, or utility pole. Although auto insurance requirements vary from state to state, bodily injury liability and property damage liability coverage  has been mandated to in many jurisdictions before using or keeping a vehicle on public roads. The auto insurance market exhibits high growth potential, as the number of road accidents is increasing in most of the countries across the globe.
(https://www.investopedia.com/terms/a/auto-insurance.asp)
(https://www.alliedmarketresearch.com/auto-insurance-market)


# Problem
- to predict customers to join car insurance from a US bank through telemarketing

# Goals
- Focus on targeting to sell Car Insurance using attributes that were known before the telemarketing was executed
- Find a solution for under a growing pressure to increase profits and reduce costs in Banks

# DataSet
Dataset from US Bank with :
- 4000 rows
- 17 columns

# Insight for EDA
1. In this dataset, we have customers with `age average of 41 years old`, while `the youngest is 18 years old` and `the eldest is 95 years old`. Most of customers don't have credit default. Customers have an average of 1,534 in their balance
2. Almost 60% customers have not secured their car, so we have 60% potential customers. Furthermore, based on their education, Customers with secondary education has the highest result on how they already have car insurance and not.
3. Group of customers who subscribed and therefore are most likely to subscribe to the Car Insurance. Regarding their characteristics, one observes that this cluster is made of persons in managerial positions. Clients who already have car insurance is having a management job, then technician and the least housemaid and entrepreneur. However, blue-collar, management, technician and admin are the potential market for the company to execute the marketing strategy.
4. There is 1590 customer that has car insurance and no credit default
5. Bank rushes to contact clients in May which leads to a successful closing the sales, but also facing other unsuccessful. Moreover, they could push clients a little more in February and April where there's a little gap between those who interested and not interested in joinning car insurance.
6. Married status has the most result on insuring their car

# Conclusion

#### Logistic Regression has the best recall score among all algorithm that we tried in this notebook
    - from all the algorithm we tried (Logistic Regression, KNN, and Decision Tree) Logistic regression has the best recall score (62.3%)

#### Scalling has an effect on Logistic Regression

