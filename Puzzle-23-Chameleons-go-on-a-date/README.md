# Chameleons-go-on-a-date

Question: 

13 purple, 15 yellow, and 17 maroon chameleons are found on an island. When two different-coloured chameleons come together, they both turn into the third colour. Do all chameleons eventually have the same hue after a certain number of pairwise meetings?

Solution:

As per the question, whenever 2 chameleons of different colours meet, both of them get converted into the third colour chameleon, which means that the number of Chameleons of the two colours (which met) decreases by 1, whereas the number of chameleons of the third colour (they converted into after meeting) increases by 2. 
Let us denote the chameleons of different colours purple, yellow and maroon by p, y and y, respectively, and then the initial state is (13, 15, 17). 
Now, let us suppose that initially, a purple and maroon meet. The vector changes to (12, 17, 16) and after continuing, we would get to this state (0, 41,4). 
When Yellow and Maroon meet first : (15, 14, 16) and after continuing, the end state is (43, 0, 2).
When Purple and Yellow meet first: (12, 14, 19)and after continuing, the end state is (0, 2, 43).
Therefore, we observe that the difference between the Chameleons of two different colours is never going to be 0, and in the absence of such a scenario we can’t get all the Chameleons to turn into one single colour.
