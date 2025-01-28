### Overview
Clustring on Iris dataset 
### Approach
From what I know Irish dataset has three classes of flowers. so First I used k=3
1. I first used K=3, PCA. so  I got silhouette score of 55%. Which is not bad but not good. so I thought maybe tsne would give better result.
2. So using tsne instead of PCA, didn't change the results. as I was assigned to use only one clustering method , I did't used any other method.
3. After that I looped code in which it takes K value from 1 to 20 and return the value of K which gives best silhouette score. In answer I got 2
4. So as I know that one cluster of Iris flower is quite larger than other two clusters. Considering those two clusters as one gives better result.
5. So as final I used K=2 and showed visual results of K-Means Clustering vs True Labels (t-SNE). And I was able to get silhouette score of 68%.


