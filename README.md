# K-Means-Cricket_players
Introduction
This project focuses on applying the K-Means clustering algorithm to a dataset to group similar data points into clusters. The dataset used is related to cricket players' statistics.

Table of Contents
Introduction About the Dataset Data Preprocessing Removing Outliers Implementing K-Means Clustering Cluster Analysis Conclusion

About the Dataset
The dataset contains information about cricket players and their performance statistics. The key features include: Player: Name of the player Span: Span of the player's career Matches: Number of matches played Innings: Number of innings played NO: Number of not-outs Runs: Number of runs scored HS: Highest score Ave: Batting average BF: Balls faced SR: Strike rate 100: Number of centuries 50: Number of half-centuries

Data Preprocessing
Loading Data:
The dataset was loaded into a pandas DataFrame for inspection.

Handling Missing Values:
Checked for null values in the dataset and handled them appropriately.

Converting Span to Years of Experience:
Split the Span column into start and end years and calculated the years of experience.

Removing Outliers
Outlier Detection: Checked for outliers in the dataset using statistical methods.

Outlier Removal: Removed identified outliers to ensure a clean dataset for clustering.

Implementing K-Means Clustering
Feature Selection and Scaling:
Selected relevant features for clustering. Scaled the numerical features to standardize the data.

Elbow Method for Optimal Clusters:
Used the Elbow Method to determine the optimal number of clusters by plotting Within-Cluster Sum of Squares (WCSS).

K-Means Clustering:
Applied the K-Means algorithm to cluster the data into the optimal number of clusters. Added cluster labels to the original dataset. Cluster Analysis

Cluster Distribution:
Analyzed the distribution of players across different clusters.

Top Players in Each Cluster:
Identified the top players in each cluster based on their performance statistics (e.g., batting average, strike rate).

Conclusion
The analysis demonstrated the application of the K-Means clustering algorithm to group similar data points in the cricket players' dataset. Key findings include:

The optimal number of clusters was determined using the Elbow Method. Players were grouped into clusters based on their performance statistics. The top players in each cluster were identified, providing insights into player performance. These insights highlight the utility of clustering algorithms in grouping similar data points and identifying patterns within the data. This can be useful for various applications, such as player performance analysis and talent identification in sports.
