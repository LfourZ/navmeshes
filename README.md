How to create nav meshes:

bind <key> nav_mark_walkable

this, when pressed, will mark a surface as walkable. It will start at the point that
you were looking at when you used the command, and go outwards for a default of 1000
hU.

to change this, use nav_generate_incremental_range <number>

then, once you have done this, bind a key to nav_generate_incremental

this will generate a mesh from the points you marked earlier

the more marks you have placed and the bigger nav_generate_incremental_range 2000
you have, the longer your computer will be frozen.

this also means that your computer has a higher chance of crashing during this
time, in which case you can lose your progress so far