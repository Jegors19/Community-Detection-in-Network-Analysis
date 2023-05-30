Community Detection in Network Analysis

This repository contains code for detecting communities in network analysis using the Girvan Newman and Louvain algorithms. It includes two examples: one using the Karate Club dataset and another using the "Who talks to whom" dataset.
Dependencies

The code is written in Python and requires the following dependencies:

    NetworkX
    pandas
    math
    pprint
    matplotlib

You can install the dependencies using pip:

pip install networkx pandas matplotlib

Usage
Karate Club Dataset

    Make sure you have the dataset file zachary_karate_club.txt in the same directory as the code.
    Run the script karate_club_detection.py.
    The script will detect communities in the Karate Club network using the Girvan Newman algorithm and visualize the results.
    It will also apply the Louvain algorithm for community detection and provide a visual comparison between the two algorithms.
    The results will be displayed on the screen.

"Who talks to whom" Dataset

    Make sure you have the dataset file who_talks_to_whom.xlsx in the same directory as the code.
    Run the script communication_network_detection.py.
    The script will detect communities in the communication network using the Girvan Newman algorithm and visualize the results.
    It will also apply the Louvain algorithm for community detection and provide a visual comparison between the two algorithms.
    The results will be displayed on the screen.

Analysis and Insights

The ReadMe file provides an analysis of the results obtained from both datasets and offers insights into the detected communities. It discusses the similarities and differences between the algorithms' outputs and suggests possible interpretations of the community structures observed.

Feel free to explore the code, modify it to fit your specific needs, and experiment with other network datasets.

For any questions or issues, please contact [author's name] at [author's email].

Happy community detection in network analysis!
