# Clustering-RMF
A model which assigns a customer to a certain customer category based on the total value of orders they’ve placed. This would let the company target the most valuable customers with certain offers which promote a higher spend.
After understanding the data it was preprocessed. Missing values were checked and rows for missing customer id were removed. Duplicate data was also removed. orders which were cancelled were also removed. 
Then recency, frequency and monetary scores were calculated for each customere so that we could understand their value. Recency was calculated as the number of days before he or she has made a purchase from the online store.Frequency = number of invoice or no. of the transaction done by each CustomerID. Monetary = Sum of total amount purchased by each CustomerID. 
Based on these scores customers were divided into 4 categories viz. Diamond, Platinum , Gold and Silver. Then clustering algorithms were also used for doing customer segmentation.
kmeans and Agglomerative clustering were used. it was found that we got similar 4 clusters from both the techniques. Final clusters were visualised. 
