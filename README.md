# MLNS-Final-Project
Repository for the final project of Machine Leaning for Network Science.

## Authors
- Victor MAILLOT
- Marina PELLET
- Emma RIGUIDEL
- Emma SERFATY


## Description of the task
The aim of this project was to do an exploratory and predictive analysis on a worldwide airports network. Our network is a weighted graph, with nodes representing airports, edges representing connections between airports, and edge weights representing the number of flights between them. We had to transform a csv file into a graph format to do so, before deep-diving into the analysis of the network through centrality measures, community detection and link prediction. 

## Data
- routes.csv is the raw tabular data. It is the data used in the notebook called airport_importance_analysis. It was downloaded from Kaggle, here: https://www.kaggle.com/datasets/open-flights/flight-route-database/code?resource=download
- flights_network.graphml is the data under the graph format. It is the file that was used in the notebook called clustering_and_link_prediction.

## Code
The code is divided into two notebook:
- airport_importance_analysis. It mainly contains the work done on understanding the importance and place of each airport in the network using centrality measures. 
- clustering_and_link_prediction. It contains the work done on detecting the groups of airports inside the network and on link prediction for unconnected airports. 
