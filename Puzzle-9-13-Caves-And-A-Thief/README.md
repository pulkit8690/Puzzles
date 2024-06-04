# 13-Caves-And-A-Thief

There are 13 caves arranged in a circle. There is a thief  in one of the caves. Each day the the thief can move to any one of adjacent cave or can stay in smae cave in which he was staying the previous day. And each day, cops are allowed to enter any two caves of their choice.

What is the minimum number of days to guarantee in which cops can catch the thief?



![image](https://github.com/pulkit8690/Puzzle-9-13-Caves-And-A-Thief/assets/103959073/30a6772c-6113-42e4-a322-398e873cad37)

Note:
Thief may or may not move to adjacent cave.
Cops can check any two caves, not necessarily be adjacent.


Answer: 12 days 

Explanation:
Lets assume the thief is in cave C1 and going clockwise and cops start searching from cave C13 and C12 on your first day.
Cave C13 and C11 on second day,
C13 and C10 on third day and so on till C13 and C1 on 12th day.
So basically the aim is to check C13 everyday so that if thief tries to go anti clockwise you immediately catch it and if goes clockwise cops will catch him in maximum 12 days (this include the case where he remains in Cave C1).
