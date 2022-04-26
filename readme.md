lab 1-
Simple Web Crawlers

lab 2-
a.Breadth-First-Search 
b.Depth-First-Search

lab 3-
Inverted Index Creation and Searching

lab 4-
Boolean and Vector Model, TF-IDF, Similarity Measures
i.Perform the text pre-processing of the given documents.
ii.Construct a Boolean Model for the vocabulary list by considering documents 1, 2, 3,4 and 5.
a.Retrieve the documents for the Boolean query  “Information Retrieval Synthesis” using simple match. 
b.Retrieve the documents for the Boolean query  “Database Retrieval Storage” using weighted match. (Rank the documents in the order of relevance)

iii.Construct a vector space model to build the term weights. Compute the TF-IDF and identify the most important terms across the documents. 
a.Rank all the documents in the collection for the query “Speech” AND “Systems”? (Rank the Top 3 documents in the order of relevance)
b.Rank all the documents in the collection for the query “Database” OR “Systems”? (Rank the Top N documents in the order of relevance)
c.Rank all the documents in the collection for the query contains “Systems” but NOT “Information” (Rank the documents in the order of relevance)

iv.Compute the cosine similarities between docs 1 and docs 2 
v.Compute Dice Co-efficient between docs 3 and docs 4.
vi.Compute the Jaccard co-efficient between docs 4 and docs 5.

lab 5-
 Index Compression Techniques
1.Apply run length encoding for the following string and compress it.
“eeeeeeerrrrrrrrrrrrrrrrttttttttttttttiiiiiiiifffffeft”
CODE:



2.Consider the following Inverted Index File with Terms, Occurrences and Posting List



i.Apply Binary coding for term “Mercury” (apply for all doc ids)
CODE:


ii.Apply Unary coding for term “Fiber”
CODE:

iii.Apply Elias Gamma Encoding for term “Airtel”

iv.Apply Elias Delta Decoding for “000010000”

v.Apply Elias Delta Encoding for term “Venus”

vi.Apply Elias Delta Decoding for “00101001”

vii.Apply Variable Byte Encoding for “Samsung”. (Use doc ids gap)

lab 6-
Web Documents Classification - Naïve Bayes Classifier
Write a Naïve Bayes Classifier in python without using any direct ML package for the following datasets (1) and (2).

lab 7-
HUBS AND AUTHORITY USING HITS ALGORITHM

lab 8-
CENTRALITY METRICS – SOCIAL NETWORK ANALYSIS


1.Find the degree centrality of all nodes
2.Find the neighbors of node 2.
3.Find the average degree of graph
4.Find the density of the graph
5.Find the closeness centrality of Node 10
6.Find all the paths to reach 4 from 6
7.Find the longest shortest path between any two nodes
8.Find the shortest path between any two nodes
9.Find the Betweenness centrality of Node 1.
10.Find the person who has maximum number of connections (friends)

lab 9-
PageRank algorithm using Python to display the rank of 8 pages.

lab 10-
 GIRVAN-NEWMAN ALGORITHM
a)NetworkX package Implementation 
b)Custom Implementation 

Implement the Girvan-Newman algorithm for the detection and analysis of community structure for the following network graph datasets (a) and (b).

lab 11-
Hierarchical Clustering 
1. Consider these data points. ([[5,3], [10,15], [15,12], [24,10], [30,30], [85,70], [71,80], [60,78], [70,55], [80,91],]) STEP 1 : Plot the data points STEP 2 : Apply Hierarchical Clustering with use of dendrograms to get output
STEP 3 : Show the output clusters 2. Randomly generate 100 datapoints (x,y) and cluster them using hierarchial clustering. 
3. The problem that we are going to solve in this section is to segment customers into different groups based on their shopping trends. The dataset for this problem can be downloaded from the file folder: shopping-data.csv. To cluster this data into groups we will follow the same steps that we performed in the previous section

lab 12-13
 Identify the frequency of most popular 50 items
Input is dataset file named 'dataset.csv'.

Task 2: Run aprior algorithm using Python for the following support and confidence