# Cyrptocurrencies project overview
Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company has requested a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.
The data source provided by the Accountability Accounting Advisory Services Team is not ideal, so it will need to be processed to fit the machine learning models. Since there is no known output the client is looking for, unsupervised learning will be used to analysis the data. To group the cryptocurrencies, the client has decided on a clustering algorithm and plans to use data visualizations to share her findings with the board.

# Project technical analysis deliverables 
The project is broken into 4 deliverables to be supplied to the client.

- Deliverable 1: Preprocessing the Data for PCA using Pandas
 
- Deliverable 2: Reducing Data Dimensions Using PCA to three principal components and adding to a new DataFrame

- Deliverable 3: Clustering Cryptocurrencies Using K-means
  Using the K-means algorithm, an elbow curve is created using hvPlot to find the best value for K from the pcs_df DataFrame created in Deliverable 2. 
  The K-means algorithm is run to predict the K clusters for the cryptocurrencies’ data.

- Deliverable 4: Visualizing Cryptocurrencies Results
  Plotly Express and hvplot are used to create scatter plots to visualize the distinct groups that correspond to the three principal components created in Deliverable 2.
  A table is created with all the currently tradable cryptocurrencies using the hvplot.table() function.
