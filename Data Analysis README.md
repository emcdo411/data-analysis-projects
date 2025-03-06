Data/Example:
Project Title: Customer Segmentation for Marketing Campaigns

Data Used:

Customer demographic data (age, gender, location).
Purchase history (total amount spent, frequency, preferred products).
Analysis Performed:



Clustering (K-Means):
python
Copy
Edit
from sklearn.cluster import KMeans
kmeans = KMeans(n_clusters=3)
data['customer_segment'] = kmeans.fit_predict(data[['purchase_amount', 'frequency']])


Insights:

Segment 1: High spenders, frequent purchases (Target with premium products).
Segment 2: Occasional shoppers, low spend (Target with discount campaigns).
Segment 3: New customers (Target with welcome offers).
