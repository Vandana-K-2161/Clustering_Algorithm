# Iris Clustering Project  

## Overview  
This project explores clustering techniques using the Iris dataset, a classic dataset in machine learning. The goal is to apply KMeans and Hierarchical clustering algorithms to identify the natural groupings of iris flowers based on their features.  

## Dataset  
The Iris dataset consists of 150 samples of iris flowers with four features:  
- **Sepal Length** (cm)  
- **Sepal Width** (cm)  
- **Petal Length** (cm)  
- **Petal Width** (cm)  

## Objectives  
- Load and preprocess the Iris dataset.  
- Implement KMeans clustering to identify groups in the data.  
- Implement Hierarchical clustering to visualize the relationships between samples.  
- Visualize the clustering results.  

## Methodology  

### Loading and Preprocessing  
- The dataset is loaded using the `load_iris()` function from the `sklearn.datasets` module.  
- A DataFrame is created using pandas to organize the feature data.  

### KMeans Clustering  
- The KMeans algorithm is applied with `n_clusters=3`, corresponding to the three species of iris flowers.  
- Clusters are assigned based on the proximity of feature measurements.  

### Hierarchical Clustering  
- Hierarchical clustering is carried out using the Agglomerative method to explore the data's structure.  
- A dendrogram is generated to visualize the hierarchy of clusters.  

## Visualization  
- **KMeans Results**: A scatter plot is produced showing clusters based on sepal length and width.  
- **Hierarchical Results**: A dendrogram illustrates the nested relationships among different clusters.  

## Outcomes  
- The KMeans algorithm effectively identified clusters associated with different iris species, demonstrating its capability to uncover hidden patterns in the data.  
- The Hierarchical clustering approach provided a comprehensive view of the relationships between species, showcasing how closely related they are based on measured features.  

## Requirements  
To run this project, ensure you have the following Python libraries installed:  
```bash  
pip install pandas matplotlib seaborn scikit-learn
