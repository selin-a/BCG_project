# BCG Data Science project
This is a day-in-a-life Data Science project at BCG. It covers all the steps in a client project from business understanding and hypothesis framing, exploratory data analysis, feature engineering and modeling with an executive summary of findings and recommendations.

### Business Case

Our customer PC is a major gas and electricity utility company who is concerned about losing customers. We see that new players have entered the market in the recent years offering a variety of choice options to consumers. We want to investigate whether churn 
is driven by the customers’ price sensitivity. 

For this, we will build a predictive model to indicate the churn probabilities of customers and derive the effect of prices on churn rates, using two datasets: 
-	Client_data.csv that includes characteristics of each customer such as historical electricity consumption, date joined as customer, churn that indicates if customer has churned.
-	Price_data.csv that includes historical price data the client charges to each customer for electricity and gas at granular time intervals.

##### What is price sensitivity and how to calculate it?

Price sensitivity is the degree to which demand changes when the cost of a product or service changes. In the context of our client, the “demand” refers to the demand for energy consumption.Price sensitivity is commonly measured using the price elasticity of demand, a measurement of the change in consumption of a product relative to the change in its price. It states that some consumers won't pay more if a lower-priced option is available.


##### Steps in analysis:

•	Use frameworks to conduct exploratory data analysis

•	Data visualizations to interpret key trends

•	Prepare the data and engineer features that can be used to test hypothesis

•	Test our hypothesis using a binary classification model (e.g. Logistic Regression, Random Forest, Gradient Boosted Machines to name a few)

•	Choose a model from one of the tested algorithms based on the model complexity, the explainability, and the accuracy of the models.

•	With the trained model, we will be able to extrapolate the extent to which price sensitivity influences churn.

