# PolishClustersData

This repository hosts the data used in my paper, in lieu of an appendix. Here, I will describe the contents of each file and what model they were used is.

1.	**acceptability\_master\_PWN** includes every cluster, a column designating with an 'x' if a cluster does NOT occur in the PWN dictionary (or a note if there is very limited use), and then the acceptability scores from the survey. Note that, for the survey, 0 means that a cluster was unacceptable for its given ending (endings have been removed). 
2.	**pol\_bigrams** is a collation of all **bigrams** in acceptability\_master\_PWN, appended with a boundary symbol \# at the beginning and end of each cluster.
3.	**illegal\_clusters**, which lists the average acceptability score for all the clusters in acceptability\_master\_PWN, as well as counting the number of illegal bigrams in each cluster.
4.	The folder **MaxEntInput** has files used to run with the Maximum Entropy learner - further details in that folder.  
