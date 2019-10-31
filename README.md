# Locality-sensitive-hashing-using-Spark

LSH: the problem of finding approximate nearest neighbors. 

Average search time for LSH and linear search.
Runtime comparison between linear search and LSH based search of top 10 nearest neigh-bors.
The LSH based search is much faster than the linear search which is bit strange as I thought Linear search will faster but it took 12.48 for single iteration where as LSH took 11.05

error value vs. K
I have taken K values from 14 to 24 with 2 point increment for better visualization and pattern finding.
Inference:
1.  While increasing K value with 2points total number of buckets increases
2.  Chances of falling all True neighbours in a bucket decreases as query point is also decreases.
3.  Due to the above reasons the error may be increasing
