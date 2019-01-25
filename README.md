# Customer-Segmentation-in-Python3

#### The most successful companies today are the ones that know their customers so well that they can anticipate their needs. Data analysts play a key role in unlocking these in-depth insights, and segmenting the customers to better serve them.
#### This Repository contains indepth analysis of Online Retail Customers based in United Kingdom on three metrics,

* Recency
* Frequency
* Monetary Value

The data used to for this projects is available on following link, https://archive.ics.uci.edu/ml/datasets/online+retail

---

### Defining Metrics

**Recency(R)**: How recently a customer has made a purchase

**Frequency(F)**: How often a customer makes a purchase

**Monetary Value(M)**: How much money a customer spends on purchases

---

**Dataset Attributes**

1. InvoiceNo
2. StockCode
3. Description
4. Quantity
5. InvoiceDate
6. UnitPrice
7. CustomerID
8. Country

---

**Sequence of Steps to be followed to Create and Analyze different Customer Segments**

1. Download Data from UCI Website, and load it in your Jupyter notebook.
2. Understand and Explore the Data.
3. Perform Data Wrangling if the data needs to be corrected.
4. Create and calcluate cohort metrics based on CustomerID and Quantity.
5. Calculate RFM metrics.
6. Build RFM Segment and RFM Score based on RFM Metrics.
7. Explore distribution of Recency, Frequency and Monetary Value.
8. Pre-process Data using below steps or use StandardScaler from scikit library.
    - Unskew the data -- Log Transformation
    - Standardize to the same average values
    - Scale to the separate standard deviation
    - Store as a separate array to be used for clustering
    - Visualize normalized data
9. Explore Data and decide on the number of Clusters, Follow either methods to identify the number of clusters to be used, I have used the 1st Method to identify clusters
     1. Visual Methods - elbow criterion
        - Plot the number of clusters against within-cluster sum of squared errors (SSE) - Sum of Squared distances from every data point to their cluster center.
         Identify the "elbow" in the plot.
        - Elbow- a point representing an "optimal" number of clusters.
    2. Mathematical Methods - Silhouette Coefficient.
    3. Experimentation and Interpretation.
10. Lastly, Profile and Interpret Segments using Snake Plot and calculate the relative importance of Segment Attributes.

---

###### Special Thanks to Karolis Urbonas
###### DataCamp Course https://www.datacamp.com/courses/customer-segmentation-in-python
**Author: Khushal Singh Rajawat**
    






