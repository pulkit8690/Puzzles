# Puzzle-4-2-Eggs-100-Floors


The following is a description of the instance of this famous puzzle involving 2 eggs and a building with 100 floors. 

Suppose that we wish to know which stories in a 100-storey building are safe to drop eggs from, and which will cause the eggs to break on landing. What strategy should be used to drop eggs such that a total number of drops in the worst case is minimized and we find the required floor 

We may make a few assumptions: 

An egg that survives a fall can be used again.
A broken egg must be discarded.
The effect of a fall is the same for all eggs.
If an egg breaks when dropped, then it would break if dropped from a higher floor.
If an egg survives a fall then it would survive a shorter fall.



Solution:
The problem is about finding the minimum floor from which an egg can be dropped without breaking, using two eggs and a building with 100 floors. The goal is to minimize the worst-case number of attempts.

The first solution suggested is a binary search approach. The first egg is dropped from the 50th floor, and if it doesn't break, it is tried from higher floors until it breaks. This narrows down the range for the second egg, which is used to find the exact break-even floor.

An alternative approach is proposed, where the first egg jumps 10 floors at a time. If it doesn't break, it is tried from higher floors in increments of 10. Once it breaks, the range for the second egg is narrowed down, and it is used linearly to find the exact break-even floor. This approach reduces the worst-case scenario to 19 attempts.

To optimize the approach further, it is important to minimize the number of attempts needed by the second egg. This can be achieved by reducing the range needed by the second egg by 1 at each step taken by the first egg. Through calculations, it is determined that starting the first egg from the 14th floor will result in the optimal solution with 14 attempts in the worst-case scenario.



