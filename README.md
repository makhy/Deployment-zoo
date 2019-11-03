# Zoo Animal Prediction

This machine learning repository uses Kaggle's [Zoo Animal Classification Dataset](https://www.kaggle.com/uciml/zoo-animal-classification).

In this dataset, 101 animals from a zoo are classified to 7 class types: Mammal, Bird, Reptile, Fish, Amphibian, Bug and Invertebrate. There are 16 variables with various traits to describe the animals. 

To start with, this project uses K Nearest Neighbor to identify patterns of various animal traits.  The model learns how these patterns indiciate the class types of the unknown animals. 

This machine learning model is deployed with a Flask app that enables prediction on a website.  Users can fill in the traits of an animal and get a prediction of what this animal actually is.

This webapp has been successfully deployed on the Google Cloud Platform (GCP).