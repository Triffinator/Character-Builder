Character-Builder
=================

This project is designed as a character building tool for text based adventures.

It allows the user to enter their name manually. 

It then gives them a menu of titles they have unlocked. Users start with three titles, but it has some opportunity for more, as they become available in game.

At this point, it checks that the inputted value for title is numeric, and then if it is unlocked (default is between 1 and 3).

After this, it displays a menu of races, along with a description of each.

At this point, it checks that the inputted value for race is numeric, and then if it is between 1 and 3.

It randomly assigns integer values (3 inclusive to 19 exclusive) to each "spec" (stat).

The code then assesses the first lowest stat, then (if user allows) re-rolls an int. This int is assigned back to that stat.

The "finished" character's information is displayed.
