### Objective:
The project aimed to analyze the Q4 data of Skyline Plaza to identify the trends and purchase behaviour of the customer so that they can meet the need of customer expectation and also increase their overall sale.

### Dataset
I have analyzed sales data of Q4 (Diwali Season). The dataset consisted of demographic, economic, such as:
- Id, Name, Age, Gender, Marital Status, Occupation, Zone, State, Orders, Amount, Product_Category, Status, and unnamed
#### Data Cleaning
 - I have to drop two complete null column "Status", "Unnamed" .
 - Amount column containes NaN value so I have dropped those rows.
 - Convereted the Amount column from Object to Integer.

#### Data Pre-Processing
- I have created age_group from age column in order to do some age related analysis.

### EDA
- I have performed exploratory data analysis and come up with some important findings which was useful for buisiness.

### Insights
- Women Shops almost twice than to a Man.
- Women with age group of 25-45 contribute total of 43% of sale on Diwali.
- Top 3 State that contributes most are: UP, Maharastra, Karnataka
- Top 3 Category that contribute most are: Food, Apparel, Footwear
- Top 3 Category that generate most revenue are: Footwear, Apparel, Food
- Top 3 Occupation that spend most on diwali are: IT, Aviation, Healthcare.

## Recommendation
Skyline can give promotional offer, discount and Buy 1 Get 1 kind of thing to WOMEN of age_group 26-45 of state UP, Maharastra, Karnataka. They can run this offers
on top 3 selling category Food, Apparel, Footwear. Skyline can even run online ads to attract more customer whose occupations are IT, Healthcare, Aviation because these the the person who the spending most of the money on diwali.
 
