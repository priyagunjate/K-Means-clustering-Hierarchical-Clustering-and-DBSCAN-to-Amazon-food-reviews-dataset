# K-Means-clustering-Hierarchical-Clustering-and-DBSCAN-to-Amazon-food-reviews-dataset


Clustering algorithm is applied on amazon reviews datasets to cluster the reviews. 

Types of clustering : 

1.K-Means clustering 

2.Hierarchical Clustering

3.DBSCAN(Density Based spital clustering of application with noise).



Procedure to execute the above task is as follows:
1.K-Means clustering
• Step1: Take Reviews data of amazon reviews data-set. And Ignore polarity column
• Step2: Apply K-means++ cluster and K-medoids cluster algorithm.
• Step3: Apply Feature generation techniques(Bow,tfidf,avg w2v,tfidfw2v)
• Step4: Apply K-Means clustering algorithm using each technique.
• Step5: To find Best k using Elbow method
• Step6: Read the cluster reviews
2.Hierarchical Clustering
• Step1: Take 5k Reviews sample of amazon reviews data-set. And Ignore polarity column
• Step2: Apply Feature generation techniques(Bow,tfidf,avg w2v,tfidfw2v)
• Step3: Apply Hierarchical Clustering algorithm using each technique.
• Step4: To find Best k using Elbow method
• Step5: Read the cluster reviews
1
3.DBSCAN
• Step1: Take sample of Reviews data of amazon reviews data-set. And Ignore polarity
column
• Step2:consider min_pts = 2* dimension(consider 100 dimensions of data).
• Step3: Apply Feature generation techniques(avg w2v,tfidfw2v) BOW & TFIDF is high
dimesional thus DBSCAn does not work properly
• Step4: Apply DBSCAN algorithm using avg w2v & tfidfw2v technique.
• Step5: To find Best k using Elbow method
• Step6: Read the cluster reviews
• Step7: As DBSCAN is sensible towards eps value,check the sensitives for different value
of eps




0.2 Objective:
• To cluster Amazon reviews using K-Means clustering, Hierarchical Clustering, and DBSCAN
algorithm.Read & display the random reviews in given set of clusters using wordcloud.
