# binary_search_example_on_c-
This code realize of idea binary search on C++

At first we include 5 header files: <cstdlib> is need for get random number that we will need in building our example of vector, <algorithm> help us to sort our vector that has just int data type values. 
  
I build string function called binary_search that has to get two arguments: list of values; number for search. It sorts the list at first, to realize binary search. 
At first i want to check that the num for search does lie in our interval of smallest in biggest value. If answer is "YES" we continue.
In every cycle it just change one of the borders due to the value of list in this index bigger or smaller then the number for search. If number for search is in our list, it must find this num for log(2) n cycles!
  
