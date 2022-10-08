# Cryptocurrencies

There was no known output for what we were looking for, so we used unsupervised learning.
We preprocessed the data to fit our machine learning models, by removing Null values and categorizing specific fields.
Using Principal Component Analysis (PCA) algorithm, we reduced the dimensions of the DataFrame to three principal components.
To group the cryptocurrencies, we used K-means. To determine the number of clusters we should utilize we created an elbow curve.

![image_name](/Resources/elbow_curve.png)

We visualized the data using both Plotly Express scatter_3d() and a hvplot scatter plot.

![image_name](/Resources/plot_3d.png)

![image_name](/Resources/hvplot_scatter.png)


