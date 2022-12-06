# CMPE297_Assignment2

## PART A
### graph level prediction using GAT/GCN
### Old colab link
#### https://colab.research.google.com/drive/1TwLhK565kG9XsSTLOJMCyUd9UcerYjQY

### Updated colab link
#### https://colab.research.google.com/drive/1lLff5Uu8_5d9EHJRpgcrYZzdYyMY3uQ8?usp=sharing
### dataset used : CORA

### Solution 
#### Here GCN's are used for prediction which rely on message passing methods, which means that vertices exchange information with the neighbors, and send “messages” to each other. Here we have simply divided the summed messages by the number of neighbors afterward. Additionally, we have replaced the weight matrix with a linear layer, which additionally allows us to add a bias.

## PART B
### Node classification using GAT/GCN
#### https://colab.research.google.com/drive/1-Fz5a5dlLvqkarfJa6GoFwLly57Y6IE7
### dataset used : CORA

### Solution 
#### The dataset consists of academic publications as the nodes and the citations between them as the links: if publication A cites publication B, then the graph has an edge from A to B. The nodes are classified into one of seven subjects, and our model will learn to predict this subject.

## PART C
### link  prediction of graph
#### https://colab.research.google.com/drive/1UGhJTKKhDHS8ZNcBePbNwj_zf1UJ2Jkd#scrollTo=NTCV4H3T01DI
### dataset used : Planetoid(citeseer)

### Solution 
#### The dataset consists of Citation links between the documents. Here in this colab, the function performs the prediction of these links of the citations
