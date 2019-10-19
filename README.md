# Decision-Tree

Decision Tree is a non linear model,where the tree is formed based on conditions.At each Node we take a decision and at each leaf we classify.We split the data based on the feature which gives max Information gain. To calculate the Information Gain we need to find the Entrophy ot Gini impurity when we split the data of feature and catagories in that feature .

Entrophy and Gini impurity varies in same manner but with different ratio.

Entrophy varies between 0 and 1

Gini Impurity Varies Betwee 0 and 0.5

when entrophy is high it indicates that the resulting nodes does not have unique class .
ex1: 

      positive class :50 %
      Negarive class :50%
      then entrophy will be 1
     
ex2:

      positive class :100 %
      Negarive class :0%
      then entrophy will be 0

Information Gaine = parent node Entrophy - sum(child node Entrophy)


Decision Tree applied on DonorsChoose Dataset

# Facing error while loading IPYNB "Sorry, something went wrong. Reload?"

please click the following link https://nbviewer.jupyter.org/github/prassena/Support-Vector-Classification/blob/master/Support%20Vector%20Classifier.ipynb
