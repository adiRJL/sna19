# Link Prediction on Facebook Social Graph

## Project Overview

This repository contains the code and documentation for the project "Link Prediction on Facebook Social Graph," which aims to solve the classical problem of link prediction in social networks. The project utilizes both implicit and explicit networks for recommendation, combining features such as user preferences, likes, dislikes (implicit network) and actual network topology (explicit network).

## Unique Features

- Utilizes both implicit and explicit networks for recommendation.
- Employs node2vec embeddings for obtaining low-dimensional node features.
- Explores a combination of features, including common metrics and structural attributes.
- Dataset obtained from the [Facebook Social Circle Dataset](https://snap.stanford.edu/data/egonets-Facebook.html) from Stanford Network Analysis Project (SNAP).

## Implementation

1. **Data Collection**
   - Obtaining the dataset from SNAP.

2. **Data Preprocessing**
   - Dataframe operations to tailor the data for analysis.

3. **Constructing Features**
   - Node embedding and implicit features.

4. **Feature Engineering**
   - Building feature vectors for model training.

5. **Training**
   - Using various models such as SGD, SVC, Logistic Regression, Neural Net.

6. **Accuracy Metrics**
   - Evaluation of model performance with accuracy metrics.

## Top Three Learnings

1. Node embeddings and implicit features yield a promising combination for link prediction (81% accuracy).
2. Similar modeling approach can be applied to recommendation problems.
3. Efficient techniques for tackling Social Network Analysis Problems.

## Results

- **Before Link Prediction**
  - Original state of the network.

- **After Link Prediction**
  - Network state after link prediction.

- **Comparison of Networks**
  - Evaluation of the predicted network against the original.
