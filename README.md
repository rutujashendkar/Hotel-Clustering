
<img src="https://user-images.githubusercontent.com/92499217/167298453-a18ef566-3c63-47d4-977b-9c1a029580db.png" width="1000" height="300" />

# Introduction

The online search for travel and stay has become a highly competitive space where several hotel brands try to attract the customer by recommending and matching. However, an introspection within the hotel industry is essential in order to have a competitive edge.

The repository aims at building a recommendation system for the dataset ‘Hotel Recommender’. The target audience for this research is primarily the hotel managers and the stakeholders. This recommendation system will enable the stakeholders to understand the rank of their hotel as compared to others. 
Moreover, the study looks at various clustering techniques such as K-Means, Agglomerative etc. while look at dimensionality reduction techniques such as PCA and MCA.

# Dataset

Three CSVs have been merged to form the final dataset. The data contains information such as hotel name, hotel code, address, zip code, ratings, room amenities, pricing information, room type etc. Overall, the data has 176906 rows and 31 columns.

The datasets can be found here:

- [Hotel_Details.csv](https://www.kaggle.com/code/keshavramaiah/hotel-recommender/data?select=Hotel_details.csv)
- [Hotel_Price_Min_Max - Formula.csv](https://www.kaggle.com/code/keshavramaiah/hotel-recommender/data?select=hotel_price_min_max+-+Formula.csv)
- [Hotels_Room_Price.csv](https://www.kaggle.com/code/keshavramaiah/hotel-recommender/data?select=hotels_RoomPrice.csv)

# Project Lifecycle

![Project_Lifecycle_HotelClustering](https://user-images.githubusercontent.com/92499217/167298315-bf9ee509-35d2-4f07-95cd-506efd3447d0.PNG)

# Models Developed

-	Flat Clustering
-	KMeans Clustering
-	Agglomerative Clustering
-	Density Based Clustering
-	Recommendation System

# Conclusion

Flat Clustering, KMeans Clustering, Agglomerative Clustering and Density Based Clustering were compared. In KMeans Clustering the appropriate number of clusters was found to be 9. In Agglomerative Clustering, ward linked was found to be the best one with 3 clusters. Density Based Clustering did not suit this data as all the points were put into one cluster whereas other clusters received none to very less datapoints. 

