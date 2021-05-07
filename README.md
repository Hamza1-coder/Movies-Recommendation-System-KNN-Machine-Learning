# Movies-Recommendation-System-KNN-Machine-Learning

Using Nearest Neighbors

# Introduction
Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.

# Installation:
This project requires python 3.x and the following libraries:
- Pandas
- Seaborn
- matplotlib
- Scipy
- NearestNeighbors
- fuzzywuzzy
- You will also need to have software installed to run and execute an iPython Notebook

We recommend students install Anaconda, a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.

# RoadMap
- Above libraries are loaded and read.
- Making data useable with respect to fit our model
- Changing data into sparse matrix
- Concept of Cosine Similarity is used in recommondation (1 - distance)
- Function which perfrom on data and recommond 10 similar movies

# Conclusin:
- take a movie name and gives us 10 similar movies according to similar rating.
