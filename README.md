# RFM & K-Means Implementation for e-Commerce Data
RFM analysis is a technique used to identify existing customers who are most likely to respond to a new offer. This technique is commonly used in direct marketing. RFM analysis is based on the following simple theory:
- The most important factor in identifying customers who are likely to respond to a new offer is recency. Customers who purchased more recently are more likely to purchase again than are customers who purchased further in the past.
- The second most important factor is frequency. Customers who have made more purchases in the past are more likely to respond than are those who have made fewer purchases.
- The third most important factor is total amount spent, which is referred to as monetary. Customers who have spent more (in total for all purchases) in the past are more likely to respond than those who have spent less.

#### How RFM Analysis Works
- Customers are assigned a recency score based on date of most recent purchase or time interval since most recent purchase. This score is based on a simple ranking of recency values into a small number of categories. For example, if you use five categories, the customers with the most recent purchase dates receive a recency ranking of 5, and those with purchase dates furthest in the past receive a recency ranking of 1.
- In a similar fashion, customers are then assigned a frequency ranking, with higher values representing a higher frequency of purchases. For example, in a five category ranking scheme, customers who purchase most often receive a frequency ranking of 5.
- Finally, customers are ranked by monetary value, with the highest monetary values receiving the highest ranking. Continuing the five-category example, customers who have spent the most would receive a monetary ranking of 5.

The result is four scores for each customer: recency, frequency, monetary, and combined RFM score, which is simply the three individual scores concatenated into a single value. The "best" customers (those most likely to respond to an offer) are those with the highest combined RFM scores. For example, in a five-category ranking, there is a total of 125 possible combined RFM scores, and the highest combined RFM score is 555.

RFM analysis looks at all of the bookings and transactions in your customer database during a specific time period, usually the last 2-3 years. The purpose of the database analysis is to determine the value of your guests based on how much they spend, how often they made a purchasing, and how recently they’ve made a purchasing.<br><br>

#### Case Study
This task is carried out with the aim to apply RFM analysis to sample data relating to transaction data from an e-Commerce.<br>
I will use Quintiles Method which is RFM scoring will be from 1 to 5 to Recency, Frequency and Monetary. 5 is the best/highest value, and 1 is the lowest/worst value. A final RFM score is calculated simply by combining individual RFM score numbers.<br>
