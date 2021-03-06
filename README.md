# Python for Data Analysis: Pandas, Seaborn, Matplotlib, ETC!
![Pandas](https://user-images.githubusercontent.com/23710841/34076744-25597a40-e2be-11e7-9749-68dea8a29589.png)

## Getting Started
I recommend downloading [Anaconda](https://www.anaconda.com/what-is-anaconda/). It is the best platform for using python as it comes pre-loaded with all the necessary libraries and it has IPython, Jupyter Notebooks, Spyder IDE, and RStudio! It's amazing.

_________________________________________________________________________
### File: pandas.py
This is time series data about people getting coffee from a machine.
Despite the file being about coffee, this is a very great way to see how pandas can be used and it gets very in-depth. 
__________________________________________________________________________
### Filtering and selecting data
File: filter.py

This covers many basic operations for filtering and selecting data!

### How to treat missing values
File: Missing.py

This covers how to treat missing values!

### How to remove duplicates
File: Remove.py

This covers how to remove duplicates!

### Concatenate and Transformations
File: concatANDtransform.py

This covers how to concatenate different dataframes and transform data!

### Group and Aggregate Data
File: group.py

This covers how to create subsets of data for more specific analysis!

# Data Visualization!
![Plot](https://user-images.githubusercontent.com/23710841/34332245-a74878be-e8fc-11e7-823b-523b91820c78.png)
We need to see how things look for better understanding.

### Standard plots
File: standard.py

### Define Plot elements
File: define.py

### Formatting
File: format.py

### Labels 
File: labels.py

### Time Series
File: timeseries.py

### Histograms, boxes, scatters with some Seaborn!
File: HBS.py
![Seaborn](https://user-images.githubusercontent.com/23710841/34332253-b96e9e92-e8fc-11e7-9c06-7cf5c067abc4.png)

# Math and Statistics

### Numpy 
File: numpy.py

### Summary Stats
File: Summary.py

Mean, Median, Standard Deviation, Variance!

### Categorical Data
File: categorical.py

### Parametric Methods
File: parametric.py

Pearson Coefficient.

### Non-Parametric
File: nonpam.py

Spearmans rank and chi-squared tests.

### Transform Distributions   -- Scikit-learn --
File: distribution.py

You scale variables so that differences in magnitudes don't produce erroneous and misleading results. There are two ways to scale data.
One is normalization and the other is standardization. Normalization creates a value between 0 and 1 and standardization creates 0 mean and unit variance. 

# Dimensionality Reduction 
### Factor Analysis
File: factor.py

Used to find root causes that explain what causes data to act a certain way, for lack of a better expression. Factors are latent variables that are meaningful but are not directly observable. You regress on feautures in order to discover factors that you can use as variables to represent original data set. These are usually synthetic representations with extra dimensionality.

Factor Analysis assumes your features are continuous or ordinal. That you have correlation coefficient greater than .3, more than 100 observations present and more than 5 observations per features, which in minimial case is 20 features. Sample must also be homogenous.
### Principal Component Analysis
File: pca.py

# Outlier Analysis 
### Outlier Analysis in univariate methods
File: outliers.py

### Outlier Analysis in multivariate method
File: mvoutliers.py

### DBSCAN for Outlier Detection --scikit-learn--
File: linearprojection.py

# Cluster Analysis
### K-Means WHAT?!
File: Kmeans.py

![Kmeans](https://user-images.githubusercontent.com/23710841/34398178-927f58bc-eb4a-11e7-922f-1435f36ce45e.png)

This allows you to parititon your data into K clusters with each data point being appointed to a cluster with the nearest mean. The space will then look like [Voronoi cells](https://en.wikipedia.org/wiki/K-means_clustering). This is known as [unsupervised learning](https://en.wikipedia.org/wiki/Unsupervised_learning) which means our data isn't labeled. We will need to scale our variables and look at a scatterplot or the data table to estimate the number of centroids, or cluster centers, to set for the k parameters in the model.

### Hierarchical Clustering 
File: hcluster.py

Hierarchical clustering is considered unsupervised learning as well. This allows you to predict subgroups within data by finding distance between each data point and its nearest neighbor **linking** the most nearby neighbors. We find number of subgroups by looking at a [dendrogram](https://en.wikipedia.org/wiki/Dendrogram).

### Instance based learning: K-Nearest Neighbors
File: knn.py

Okay, this is [supervised learning](https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm)! 
It basically learns from observations and tries to predict classification for new observations. Data set must be labeled, and be small. Avoid using this algorithm on large datasets. 

# Regression Time!
### Linear Regression
File: linreg.py

Simple use case would be: Let's predict the price of a home given its: kitchen size, square footage, bedrooms, yard size, and crime rate in the area. These have to be in a numeric-linear relationship with out target value, price.

Assumptions: 
- Our variables must be numerical, not categorical, however I will get into how you could still use categorical values. 
- Data is free of missing values & outliers.
- linear relationship between feature variables and target variable.
- All predictors are independent of each other!
- Residuals (error variable) is normally distributed with unit variance. 

### Naive-Bayes Classifier
File: nbc.py
###### Creating a spam filter

![NBC](https://user-images.githubusercontent.com/23710841/34399577-9a99f5be-eb56-11e7-86f9-2ba75a380a28.png)

Three Types:
- Multi-nomial: When features (numeric/categorical) describe discrete frequency, like counts. 
- Bernoulli: When features are binary (0 or 1).
- Guassian: When feautures are normally-distributed. 

Assumptions:
- Features are independent of each other.
- A priori assumption: past conditions still hold true. When we make predictions from historical values, we will get incorrect results if present circumstances have changed!

# Web Scraping with Beautiful Soup (Coming Soon!)


