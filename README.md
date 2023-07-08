## Movie Rating Similarity Analysis.

This repository explores the concepts of Jaccard distance, min hashing, and LSH (Locality Sensitive Hashing) in the context of user similarity in a movie rating dataset.
To be more precise, we will explore the use of Jaccard distance, min hashing, and Locality Sensitive Hashing (LSH) in the context of user similarity in a movie rating dataset. The dataset used for this assignment contains 100,000 ratings from 943 users on 1,682 movies. We will perform various tasks to compute user similarity and evaluate the effectiveness of different techniques. The tasks include importing and pre-processing the dataset, computing the exact Jaccard similarity of users, computing similarity using Min-hash signatures, and locating similar users using LSH index.

While the current analysis will be done on Jupyter Notebook and in Python 3.10.0.

### Contents

This repository contains:

1. **Dataset**: The movieLens dataset that includes 100,000 ratings (1-5) from 943 users on 1682 movies. It consists of three files: `users.txt`, `movies.txt`, and `ratings.txt`. The dataset has been pre-processed to focus on the set of movies that each user has rated.

2. **Code & Documentation**: The implementation of various algorithms and techniques to compute user similarity and analyze movie ratings. The code is organized into different tasks outlined in the assignment.

### Instructions 

To reproduce the analysis or explore the code, follow the steps below:

1. Download the movieLens dataset from the provided compressed file and place the files in the appropriate directory.

2. Execute the code for each task, which are clearly organized and commented in the Jupyter Notebook.

3. Examine the generated output files to observe the results of each task.

4. Refer to the report for detailed explanations, observations, and insights gained from the analysis.

### Contributors

- [x] [Foteini Nefeli Nouskali](https://github.com/FoteiniNefeli)
- [x] [Dimitris Matsanganis](https://github.com/dmatsanganis)


![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
