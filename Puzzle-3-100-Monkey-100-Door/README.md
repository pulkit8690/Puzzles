# Puzzle-3-100-Monkey-100-Door


There are 100 closed doors. A cage holding 100 monkeys is placed nearby. Every monkey that visits a door either opens a closed door or closes an open door. The first monkey that is let out of the cage visits and opens all the hundred doors. The second monkey that is released visits doors of the order 2, 4, 6, 8, 10…. . The third monkey released visits doors 3, 6, 9,12, 15……, and so on.

After all the monkeys from the cage are released and have opened or closed at least one door, how many doors are left open?

Answer:
The first monkey opens all 100 doors.
The second monkey closes all even-numbered doors, leaving only the odd-numbered doors open.
The third monkey closes all doors that are multiples of 3, leaving only the doors that are multiples of 3 but not multiples of 2 open.
The fourth monkey closes all doors that are multiples of 4 but not multiples of 2 or 3.
And so on.


After all 100 monkeys have finished, only the doors that are perfect squares will remain open.

1, 4, 9, 16, 25, 36, 49, 64, 81, and 100.



Shortcut:
If Door is Touch even time(i.e even factor) then it is close
If Door is Touch odd time(i.e odd factor) then it is Open

Shotcut:
take sqaureroot of total number of monkey
