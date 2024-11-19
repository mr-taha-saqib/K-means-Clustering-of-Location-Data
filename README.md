# User Activity Clustering and Analysis

This repository contains the implementation of clustering user activity data based on location using the **K-means clustering algorithm** and analyzing the user’s activity in the clustered locations. 

---

## **Objective**
1. **Cluster User Data**: Group user data based on location using **K-means clustering** (preferably 3 clusters).
2. **Activity Analysis**: Identify the activity performed by the user at each clustered location and plot activity percentages in a pie chart.

---

## **Dataset Information**
- The dataset contains **250+ columns** with various user activity data.
- Relevant columns for clustering:
  - `Location:log_latitude_range`
  - `Location:log_longitude_range`

### **Activities to Analyze**
The following activities are considered:
- **Sitting**
- **Lying_down**
- **Fix_running**
- **Fix_walking**
- **OR_standing**

---

## **Steps to Perform**
### **1. Clustering the Data**
- Apply **K-means clustering** to group user data based on location.
- Use the `Location:log_latitude_range` and `Location:log_longitude_range` columns for clustering.
- **Output**: A scatter plot visualizing the clusters.

### **2. Activity Analysis**
- Identify the predominant activity performed by the user in each cluster.
- Calculate the percentage of each activity (Sitting, Lying_down, Fix_running, Fix_walking, OR_standing) in the clustered locations.
- **Output**: A pie chart representing the distribution of activities.

---
