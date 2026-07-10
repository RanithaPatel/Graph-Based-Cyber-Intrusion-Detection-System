## Graph-Based Network Intrusion Detection Using Machine Learning
## Project Overview:
This project presents a Graph-Based Network Intrusion Detection System developed as part of my M.Tech mini project. The system converts network communication records into a graph structure and extracts graph structural features to identify whether network behaviour is Normal or Intrusion using a Random Forest classifier.

## Dataset:
UNSW-NB15 (University of New South Wales Network Behaviour 2015)

## Technologies Used:
Python

NetworkX
Scikit-learn
Pandas
NumPy
Streamlit
Pickle

## Methodology:
Load the UNSW-NB15 dataset.
Construct a communication graph.

## Extract graph structural features:
Degree
Clustering Coefficient
Neighbour Count
Train a Random Forest classifier.
Save the trained model.
Deploy the model using Streamlit.

## Features:
Graph-based feature extraction
Random Forest classification
Streamlit prediction interface
Real-time prediction demonstration

## Future Enhancements
Automatic live network traffic capture
Automatic graph construction
Integration with Graph Neural Networks (GNNs)
Real-time network monitoring

## How to Run
pip install -r requirements.txt
streamlit run app.py

