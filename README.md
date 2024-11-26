## Project Summary: Customer Segmentation Using K-Means Clustering

**Project Goal:**

To segment customers of an online retail store using K-Means clustering to better understand their behavior and identify potential target markets.

**Data:**

- **Online Retail Dataset:** Contains transaction data from a UK-based online retail store from 2009 to 2011.
  - [Dataset URL](https://archive.ics.uci.edu/dataset/502/online+retail+ii)
- **Key Features:** Recency (time since last purchase), Frequency (total purchases), Monetary Value (total spending).

**Methodology:**

1. **Data Exploration and Cleaning:**

   - Analyzed data for missing values, outliers, and inconsistencies.
   - Identified and addressed issues such as negative quantities, invalid stock codes, and cancelled orders.
   - Dropped unnecessary or irrelevant data.

2. **Feature Engineering:**

   - Calculated RFM scores for each customer based on recency, frequency, and monetary value.

3. **K-Means Clustering:**

   - Applied K-Means clustering to the RFM scores to identify distinct customer segments.
   - Determined the optimal number of clusters using techniques like the elbow method.

4. **Cluster Analysis:**
   - Analyzed the characteristics of each cluster to understand customer behavior patterns.
   - Identified key differences between clusters in terms of purchase frequency, spending habits, and engagement levels.

**Results:**

- Successfully segmented customers into distinct groups based on their purchasing behavior.
- Identified high-value customers, frequent buyers, and customers with lapsed engagement.
- Provided insights for targeted marketing campaigns and customer retention strategies.

**Conclusion:**

K-Means clustering proved to be a valuable tool for customer segmentation in this project. The results can be used to tailor marketing efforts, improve customer satisfaction, and drive business growth.
