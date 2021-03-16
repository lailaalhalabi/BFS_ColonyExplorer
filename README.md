# ColonyExplorer


The purpose of ColonyExplorer program is finding colonies using DFS (Depth-first search) by finding neighbors of each cell containing '1' and labeling them.

First, the grid will be passed through ExploreColony() which will find the 1's inside the grid.
Secondly, each time ExploreColony() finds a 1, it calls the method ExploreAndLabelColony() to explore its neighbors. 
All the found coordinates will be assigned to 0's to mark them as visited, so they do not be checked be again.

The program's 1st version was done using recursion, and the 2nd one was done using iteration.

------------------------------------------------------------------------------------------------------------------------------------------------------------------

TIME COMPLEXITY
The time complexity at best case in O(n), where n is the number of 1's, while the time complexity at worst case when all neighbors equal ‘1’ is O(ROWS*COLUMNS).


