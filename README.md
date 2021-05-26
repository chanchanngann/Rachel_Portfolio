# Rachel_Portfolio

# [Project 1: Netflix - Movie Recommender and EDA with Plotly](https://github.com/chanchanngann/netflix_recommender/tree/master)
* Created a movie recommender to suggest 10 movies on Netflix that are similar to the movie-in-interest.
* Used Plotly to do the EDA to explore the TV shows and Movie data on Netflix, answering some inspiring questions:

   1. What are the target audience in different countries?

   2. Understanding what content is available in different countries (the US vs. Korea)

   3. Is Netflix has increasingly focusing on TV rather than movies in recent years?

![](/images/3_target_audience_rev.png)

# [Project 2: E-Commerce Platform (Wish) - Sales Prediction](https://github.com/chanchanngann/ecommerce_sales/tree/master)

* Objective to answer the business crucial question "how well a product is going to sell?" by developing 4 regression models to predict number of units sold for each product. Random Forest performed the best after features and hyperparameters tuning, scoring 0.77, i.e. 77% variations could be explained by the prediction model.
 
* Also, I tried to look for patterns regarding various components vs. number of units sold and answered some inspiring questions while visualizing the dataset:

   1. How is human sensitiveness to price drops? (impact of discount on number of units sold)

   2. What are the top categories of products which sell best?

   3. Do bad products sell? How is the relationship between the quality of a product and its success? Does the price factor into this?
   
   4. Do seller's fame factor into top products? 
   
   5. Does ad-boosting help to sell more?
   
   6. Do the number of tags (making a product more discoverable) factor into the success of a product ?

![](/images/20_heatmap.png)

# [Project 3: Customer Segmentation by RFM Analysis w/ K-Means Clustering](https://github.com/chanchanngann/RFM)

* From the Pareto Principle, 80% of sales come from 20% of customers. The objective of this project is to identify the best customers by performing RFM analysis with K-means clustering. 
 
* Idea behind RFM: 
  > - Recency (R) : Customers who have purchased from your store recently are more likely to convert again than those who haven't visit your store for a while
  > - Frequency (F) : Customers who buy from your store more often are more likely to buy again than those who buy infrequenctly
  > - Monetary (M) : Customers who spend more are more likely to buy again than those who spend less

* **Customer Segmentation by RFM scores:**
      we can group the customers into different segments based on the combination of RFM scores assigned to each customer. This will help us sharpen the understanding of the    target market and be more precise in communicating with actual and potential customers.

    > - **Champions: the best customers!**
    > - Loyalists
    > - New Customers
    > - Can’t Lose Them
    > - Slipping

![](/images/11_RFM_3Dplot1.png)

# [Project 4: Customer LTV forecast with classification models](https://github.com/chanchanngann/LTV_cluster)

* The objective of this project is to identify the most profitable customer segment in the future among existing customers who have a known transaction history.
* Similar to project 3, I will continue with the RFM approach but also apply multiclass classification models to predict the LTV clusters. 
* The LTV forecast could help us pinpoint the potential profitable customers so that we could direct marketing dollars to the right customers.

![](/images/04_LTV_cluster.png)


