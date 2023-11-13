# CryptoClustering

# Best Value for K with Original Data

  To find the k value from the first set of data I created the list of k values from 1 to 11, and then made an empty list to store the values.  I then used a for loop to compute the intertia to find each possible value for k.  USing those values I created a dictionary and made it into a DataFrame to be able to plot the chart into an eblow curve to find the best value, which was 4.
  
# Cluster with K-means

  I started with making the model based on the best value for k and making the n-clusters = 4. I then used the predict method so I can make an array to have each k value.  I then made a new column to house the k values so that could be printed out into a scatter charts to accurately show the cluster of values by color which represents their k value.

# Optimize with PCA

  I frist started by creating the PCA model and then transformed it to reduce to the three principle components. After that I used the pca created model to get the explained variance ratio to see how much of the data is being used through the three components, which ended up being 87%.

# Best K-value for PCA

  I did the same thing as last time for finding the best k-value as the original but this time it was with the PCA data.  I created the empty lists and the for loop to compute the intertia and after plotting the data the best k-value remained unchanged from the orignal data at 4.

# Cluster PCA with K-menas

  In order to create the new scatter chart I used my PCA predicted data and created my new column names predicted clusters.  Then once I plotted my graph I can see the the plots as they are clustered by their k-means values.  

# Visualize and Compare

  At the end I plotted the graphs again but put them side by side using the + so they would both pull up.  I did this for the elbow graphs and the scatter plots. While the elbow graphs changed a little bit, you can see it was not significant enough to be able to change the n clusters.  Comparing the two scatter plots the dots are definitley a little more closer together and the outliers are less than the first graph. 
