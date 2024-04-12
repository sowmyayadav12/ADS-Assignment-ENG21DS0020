# ADS-Assignment-ENG21DS0020
#1.Named Entity Recognition (NER):
Named Entity Recognition (NER) is a crucial Natural Language Processing (NLP) technique designed to identify and categorize named entities within text into predefined categories, such as people, places, organizations, dates, quantities, monetary values, and percentages. The primary aim of NER is to extract structured information from unstructured text by recognizing entities and their types. It plays a vital role in various NLP applications, including document summarization, information retrieval, and dialogue systems. The typical steps in NER involve tokenizing the input text into words or phrases and then classifying each token into predefined entity categories. NER employs a range of techniques, including deep learning methods like Bidirectional Long Short-Term Memory (LSTM) networks, statistical models like Conditional Random Fields (CRF), and rule-based approaches.

#2.Analysis of Zachary's Karate Club Network using NetworkX:
This Python script analyzes the network of Zachary's karate club, which is represented in the "karate.gml" file, using NetworkX, a library for graph analysis. The script performs the following tasks:

i. Creates a graph from the "karate.gml" file and provides basic information about the network.

ii. Stores metadata of actors within the network.

iii. Computes various centrality measures (degree, betweenness, closeness, eigenvector, and pagerank centrality) and offers insights based on these centrality values.

iv. Identifies possible k-components of the network and calculates the clustering coefficient.

v. Detects communities within the network using algorithms such as Girvan-Newman and Louvain method.

To run the script, ensure that NetworkX is installed (using pip install networkx) and provide the correct file path for the "karate.gml" file.
