# machine_learning_project-unsupervised-learning

## Project Goals
The objective of this project was to extract meaningful patterns and group similar data points together within the Wholesale dataset, which comprises information about a wide range of products sold by a grocery store. This was achieved through the application of unsupervised machine learning techniques aimed at gaining valuable insights from the data.

## Process
Initially, the dataset underwent an importation process, followed by essential data cleaning and exploratory data analysis (EDA). This encompassed tasks such as identifying and addressing null values, outlier detection, and creating visual charts and graphs to gain preliminary insights into the data.

Subsequently, the cleaned data underwent preprocessing and feature engineering steps to prepare it for machine learning models. This involved managing missing values, addressing outliers, partitioning the dataset into training and testing subsets, and standardizing predictor variables.

Finally, The unsupervised machine learning techniques employed included Kmeans Clustering and Hierarchical Clustering. Additionally, Principal Component Analysis (PCA) was utilized to derive insights from the wholesale customer data, helping identify the most effective combinations of features that describe customer behavior.

##Results
	Hierarchical clustering demonstrated superior performance in grouping customers.
	Hierarchical clustering provided a more streamlined outcome, yielding two clusters as opposed to eleven in the K-means clustering model.
	Visualization of K-means clustering was not very informative due to the two-dimensional nature of the data.
	Determining the optimal number of clusters in the K-means clustering model was challenging, as the elbow method did not exhibit a clear elbow point.
	PCA analysis revealed that only three components were necessary to effectively describe customers, as these components maximized the variance.
	For future analyses, one option is to explore alternative methods for handling outliers, as the current IQR-based approach resulted in the removal of a significant number of rows. Subsequently, the models can be reevaluated with this revised dataset.
	Another potential avenue for future analysis is to experiment with different ways of segregating the data, such as further column removal or the addition of dummy columns, to potentially yield more insights.
