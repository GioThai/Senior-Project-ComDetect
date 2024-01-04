# Senior-Project-ComDetect
Cal Poly undergraduate senior project on using community detection algorithms on Twitter data.

The goal of this project was to use community detection algorithms and a sentiment analyzer on a mention-based Twitter network to investigate community structure in both the mention-based (graph structure) and semantic (attitude towards vaccination) sense.

The following python notebook files are attached to this repository:
+ The "Data_Cleaning_Final" file contains the original vaccination tweet data set, as obtained from Kaggle (link: https://www.kaggle.com/datasets/keplaxo/twitter-vaccination-dataset), as well as all necessary functions to take a subset of the data (2015-2019) and clean it to keep relevant information in both forming the network and coloring each user (node) with its corresponding average sentiment values.
+ The "ComDetect_Final" file contains all functions and libraries needed to analyze community structure in these networks. The investigations center on running the Louvain Algorithm to create communities and looking for a link between degree centrality and sentiment profile. That is to say, are highly-connected users within their respective communities able to sway or control the opinions of their mentionees?
