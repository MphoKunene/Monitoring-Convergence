# Monitoring-Convergence
In your main iteration loop, for each data point, calculate the squared  distance between each point and the cluster mean to which it belongs,  and sum all of these squared distance

# Create a text file called ‘interpretation.txt’ and fill in your answers to the questions below. 
# Run k-means using 3 clusters on the 1953 and 2008 datasets separately. 
# What do you see? Take note of how the clusters change from 1953 to 2008. 
# You will need to pay attention not only to which countries are in clusters together but 
# also to the Life
 Expectancy and BirthRates for those clusters. 
# Next, run the algorithm with 4 clusters on dataBoth.csv. 
# Note any observations in your text file. Which countries are moving up
# clusters? 
# How does (2008)South Africa” compare to “(1953)United States”? 
# Are there any 2008 countries that are in a cluster that is made up mostly of 1953 countries? 
# Try and
 explain why.
# Are there any 1953 countries that are in a cluster that is made up of mostly 2008 countries? 
# Try and explain why in your text file. 

	

Answer:

Three clusters for 1953 file and 2008 file:

From 1953 to 2008, the clusters changed from 88, 
60 and 40 countries per cluster, to 85, 65 and 46 countries per cluster respectively. 
The changes in the clusters’ birth rates and life expectancies were:


cluster 1
Birth 47.368170 -> 37.843717 — birth rate dropped by approx. 10 per 1000
Life 39.417949 -> 53.559500 — 
life expectancy increased by approx. 14 years

cluster 2
Birth    41.223667 -> 23.678662 — birth rate dropped by approx. 
18 per 1000
Life     55.359633 -> 70.122754 — life expectancy increased by approx. 15 years

cluster 3
Birth    22.017625 -> 12.650824 — 
birth rate dropped by approx. 9 per 1000
Life     65.890771 -> 76.709341 — life expectancy increased by approx. 11 years. 


Cluster 1 has the highest birth rate and the lowest life expectancy in both 1953 and 2008, whereas cluster 3 constistantly
has the lowest birth rate and the highest life expectancy. 

The following 5 countries will be looked at to see whether 
they moved clusters or stayed in the same cluster over time: Afghanistan, Azerbaijan, United Kingdom, Western Sahara and Zimbabwe. 


Afghanistan and Zimbabwe stayed in the first cluster (economically developing), Azerbaijan remained in cluster 2, 
United Kingdom remained in cluster 3 (economically developed) and Western Sahara moved from cluster 1 to cluster 2.
 
Four clusters for both file:

The four clusters contain 95, 98, 88 and 11 countries respectively. 


The clusters’ birth rates and life expectancies are:
cluster 1
Birth 47.417141
Life 39.135594

cluster 
2
Birth 14.617579
Life 75.339041

cluster 3
Birth 41.058240
Life 53.619833

cluster 4
Birth 25.701489
Life 65.611900


Cluster 1 
contains exclusively 1953 data from economically developing countries including Ethiopia, South Africa and Zambia. 
This is because cluster 1 has the highest birth rate and lowest life expectancy. In 1953, economically developing 
countries did not have the education or the resources  (medical, economical, etc.) to control birth rates and increase 
how long the populations lived. 

Cluster 2 contains majority 2008 data from economically  developed countries, including 
Canada and Sweden. The minority of the data are 1953 data from economically developed countries, including United Kingdom, 
Luxembourg and Denmark. UK, Denmark and Australia stayed in cluster 2 for both data sets. This cluster has the lowest birth 
rate and the highest life expectancy. This is because, since 1953, these developed countries have had the education and the 
resources to teach the population the benefits of having fewer children and to give them the medical care needed to increase life 
expectancy. 

Cluster 3 contains a distribution of 1953 and 2008 data. Many economically developing countries moved from cluster 1 to 
cluster 3 between 1953 and 2008, including Eritrea, Ethiopia, Rwanda and Somalia. These countries have the second highest birth rate 
and the second lowest life expectancy. This shows how some economically developed countries have improved between 1953 and 2008 through 
adequate education and medical services.

Cluster 4 contains majority 2008 data from economically developing countries, 
including Botswana and Haiti, and 1953 data from currently economically developed countries, including Italy and the Netherlands. 
United States were in cluster 4 in 1953 and moved to cluster 2 in 2008. Cluster 4 has the second lowest birth rate and 
the second highest life expectancy. This data could represent developing countries that have had a significant improvement in standard 
of living since 1953, or economically developed countries that have somewhat improved their standard of living since 1953 — such that 
their 2008 data is now in cluster 2 e.g. Spain.  





