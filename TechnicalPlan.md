
## Aproach to the problem

The problem is to identify stereotypes. We can approach this problem in two ways:

- Top down: Use data-driven (unsupervised ML) approach to uncover stereotypes (topics) using Topic Modelling. We will use semantic structures in text to understand unstructured data without predefined tags or training data
  
- Bottom up: Use predefined stereotypes to build a model that can be used to predict the stereotype of a given video. For this we need labelled data.

## Technical approach
Use bipartite networks to infer stereotypes (topics).This can be done through community detection in the network.
