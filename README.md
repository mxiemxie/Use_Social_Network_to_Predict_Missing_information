# Use_Social_Network_to_Predict_Missing_information
Developed a semantic annotation technique for location-based social networks to automatically annotate all places with
category tags, which are missed in the location attribute of the Yelp dataset

Built a binary Support Vector Machine (SVM) classifier for each tag to support multi-label classification

Utilized the check-in behavior of users, the extract features of places from explicit patterns of individual places, and the
implicit relatedness of similar places

Created an innovative Network of Related Places (NRP), linking similar places by virtual edges, and explored the
relatedness of places using a random walk algorithm, to determine the probability of a category tag for each place

Compared the performance of the SVM and NRP methods by utilizing them on the Yelp Dataset
