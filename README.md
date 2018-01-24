# k-NN-Classifer-Algorithm

1) K is the no of neighnours that we can to classify. 

   so essentially we look at the nearest neighbour to the node that we select. 
   
   so example : we have a new node that we add, then we calculate the nearest neighbour to that node. And if that is near a
   particular node of a particular class then we classify that same as the nearest neighbour.
   
   a node near apple node - > will be assigned as apple 
   a node near lemon node - > will be assigned as lemon 
   
   accuracy - > No of correct predictions/total no of predictions !! 
   
2) The Nearest neighour Algo needs : 
   
   a) A distance metric 
      Typically Euclidean (Minkowski with p = 2)  
   b) How many 'nearest' neighbors to look at?
      e.g. five
   c) Optional weighting function on the neighbor points
      Ignored
   d) How to aggregate the classes of neighbor points - Simple majority vote
      (Class with the most representatives among nearest neighbors)
