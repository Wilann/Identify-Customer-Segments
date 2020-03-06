# Unsupervised Learning

## Project: Identify Customer Segments

### Source
Project 3 from Udacity's [Intro to Machine Learning Nanodegree](https://www.udacity.com/course/intro-to-machine-learning-nanodegree--nd229)

### Description
In this project, I apply unsupervised learning techniques to identify segments of the population that form the core 
customer base for a mail-order sales company in Germany. These segments can then be used to direct marketing campaigns 
towards audiences that will have the highest expected rate of returns. The data that I used has been provided by 
Udacity's partners at Bertelsmann Arvato Analytics, and represents a real-life data science task.

- Assessed missing data and converted missing value codes to NaNs 
- Identified, and dropped features/samples that were outliers (features missing more than 20% of data) 
- Performed data wrangling and re-encoded categorical (via One-hot Encoding) and mixed features 
- Used an Imputer to replace all missing values 
- Applied feature scaling (via StandardScaler) 
- Applied PCA to find vectors of maximal variance and reduce dimensionality 
- Analyzed the ratio of explained variance accounted for by each principal component and decided to retain 20 principal 
components for clustering
- Re-fitted a PCA instance on the determined transformation and reviewed the cumulative variance
- Interpreted principal components to determine the most prominent features
- Applied clustering (via KMeans) to the general population and used the Elbow Method to decide how many clusters to keep, 
then re-fit the k-means model with the selected number of clusters 
- Mapped the customer data to the clusters for the general population (pre-processed, transformed features, applied 
clustering via PCA and KMeans from the general population, and obtained cluster predictions for the customer demographic)
- Compared customer demographic to the general population to see where the strongest customer base for the company is 
- Discovered ~200 features of people that are a suitable target audience for the company (also discovered 4 groups/clusters 
of people that aren't a suitable target audience for the company)

### Install

This project requires **Python 3.x** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [Matplotlib](http://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org)
- [Scikit-Learn](https://scikit-learn.org/stable/)

You will also need to have software installed to run and execute an [iPython Notebook](https://jupyter.org)

It's recommended to install [Anaconda](https://www.anaconda.com), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project. 
