<p style="text-align:center">
    <a href="https://nick9303.github.io/" target="_blank">
        <img src="https://nick9303.github.io/imgs/logo.png" width="200" alt="NBC">
    </a>
</p>

# Customer-and-Cluster-Analysis-Project
This database was extracted from a Kaggle page [Consumer Behavior: Cluster Analysis | KMeans](https://www.kaggle.com/code/annastasy/consumer-behavior-cluster-analysis-kmeans/notebook#-3.-Loading-and-Understanding-Data-). From this page, codes will be used from the import of the required libraries up to data cleaning. However, some small corrections were added to improve the data analysis like incorporate age, which is an important factor to consider within the demographic analysis.

At the end, the database is also replaced with a augmented database to conduct a different cluster analysis and also to compare the model obtained from this scaled database with the original version done in the original Kaggle project.

For this project, I have conducted a data analysis in which I demonstrate different insights that help to understand how the business operates, how customers behave, and also how the campaigns and offers around the business perform. This way, I aim to add something additional to this project that has been done on Kaggle. I have also conducted an analysis of the niche, which would be the ideal customer that the company should focus on to increase its profits and to analyze patterns that could lead to more potential customers.

**Attributes**

People

* ID: Customer's unique identifier
* Year_Birth: Customer's birth year
* Education: Customer's education level
* Marital_Status: Customer's marital status
* Income: Customer's yearly household income
* Kidhome: Number of children in customer's household
* Teenhome: Number of teenagers in customer's household
* Dt_Customer: Date of customer's enrollment with the company
* Recency: Number of days since customer's last purchase
* Complain: 1 if the customer complained in the last 2 years, 0 otherwise

Products
* MntWines: Amount spent on wine in last 2 years
* MntFruits: Amount spent on fruits in last 2 years
* MntMeatProducts: Amount spent on meat in last 2 years
* MntFishProducts: Amount spent on fish in last 2 years
* MntSweetProducts: Amount spent on sweets in last 2 years
* MntGoldProds: Amount spent on gold in last 2 years

Promotion
* NumDealsPurchases: Number of purchases made with a discount
* AcceptedCmp1: 1 if customer accepted the offer in the 1st campaign, 0 otherwise
* AcceptedCmp2: 1 if customer accepted the offer in the 2nd campaign, 0 otherwise
* AcceptedCmp3: 1 if customer accepted the offer in the 3rd campaign, 0 otherwise
* AcceptedCmp4: 1 if customer accepted the offer in the 4th campaign, 0 otherwise
* AcceptedCmp5: 1 if customer accepted the offer in the 5th campaign, 0 otherwise
* Response: 1 if customer accepted the offer in the last campaign, 0 otherwise
Place
* NumWebPurchases: Number of purchases made through the company’s website
* NumCatalogPurchases: Number of purchases made using a catalogue
* NumStorePurchases: Number of purchases made directly in stores
* NumWebVisitsMonth: Number of visits to company’s website in the last month


