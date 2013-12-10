MEMORY
======

Interface
---------
Blue lines are for data to write.

Green lines are the ones to read data from.

Yellow lines are for selecting the low 5 bits of the memory address to write in.

Pink lines are for selecting the layer which to write in.
They also correspond to the high 3 bits of the memory address.
Controller must keep only one of theese high at the same time
and for time long enough for the data to be writen back to the memory cell.
