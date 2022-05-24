# Customer-Personality-Analysis

### Problem Statement:
- Customer Personality Analysis is a detailed analysis of a company’s ideal customers.
- It helps a business to better understand its customers and makes it easier for them to modify products according to the specific needs, behaviors and concerns of different types of customers. 
- Customer personality analysis helps a business to modify its product based on its target customers from different types of customer segments. For example, instead of spending money to market a new product to every customer in the company’s database, a company can analyze which customer segment is most likely to buy the product and then market the product only on that particular segment.

### The main objective here is -
- What people say about your product: what gives customers’ attitude towards the product.
- What people do: which reveals what people are doing rather than what they are saying about your product.

### Data cleaning:
  - Removing outliers
  - null values, duplicates

### Deriving important features from the existing features:
  - Total Spending : Adding all the individual amounts spent on wines, fruits, meat products, etc.
  - Total Purchases : in different platforms such as store, website, catalog

### EDA:
  - more customers are in the age group of 40 to 60
  - income rises as age increases
  - basic educated people spend less on gold

### Clustering similar customers:
  - KMeans Clustering algorithm
  - 4 : optimum number of clusters

### Analysis of Clustering Results:
  - Composition of clusters:
    - cluster 1 & 2 - has maximum number of customers
    - cluster 4 has least
  - total Purchase vs clusters:
    - Cluster 1: High amount of purchases ; Cluster 2: Average amount of purchases
    - Cluster 3: High amount of purchases ; Cluster 4: Low amount of purchases
  - Income vs clusters:
    - Cluster 1: High income ; Cluster 2: Average Income
    - Cluster 3: Very High income ; Cluster 4: Low income
  - Education vs clusters:
    - Graduation: Cluster 1 & 2 has more customers ; PhD Scholars: Cluster 1 & 2 has more customers ; Masters Holders: Cluster 2 has more customers
    - Basic Education: Cluster 4 has more customers ; 2nd Cycle (European Masters): Cluster 4 has more customers
  - Shopping source proportions vs clusters:
    - All clusters make the maximum purchases at the store.

### Finally Segmenting Customers into 4 buckets based on the above inferences:

- Platinum Customers: (Cluster 1)
    - Highly educated, very high income --- buy from the store(45%), from website(30%)
- Diamond Customers: (Cluster 2)
    - highly educated, average income --- buy from the store(50%), website(40%)
- Gold Customers: (Cluster 3)
    - average Educated, very high income --- buy from catalog (30%), store (40%)
- Silver Customers: (Cluster 4)
    - average education, low income --- highest store purchases

