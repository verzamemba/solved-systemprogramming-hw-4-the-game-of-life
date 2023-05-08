Download Link: https://assignmentchef.com/product/solved-systemprogramming-hw-4-the-game-of-life
<br>
The Game of Life is a cellular automaton devised by the British mathematician John Horton Conway in 1970. It is the best-known  example of a cellular automaton. The “game” is actually a zero-player game, meaning that its evolution is determined by its initial state, needing no input from human players. One interacts with the Game of Life by creating an initial configuration and observing how it evolves.

Goal

Implement Conway’s game of life with multithreading to accelerate

computation.

Understand the impact of the number of threads on system performance.

Understand the impact of threads and processes on system

performance. Any e

d ad cell with exactly three live neighbours becomes

a live cell Sample input and output

1. The input and output file will be a .txt file. Sample input and output

input.txt

.o.o.

first line: [row] [co’] [epoch]

O (big-O, not zero) : live cell

. : dead cell Sample input and output

input.txt

.o.o.

output.txt xe ution

T e following commands will be run when testing.

make

./main [multithread or multiprocess] [quantity] [input file] [output file]

0

ex.

./main -p 2 ./infilel .txt ./output.txt

./main -t 20 ./infile2.txt ./output.txt

Note:

0

o

Your output file should be in the same directory as the main executable file.

Your executable file name should be main.

About the second parameter, -p means using the multiprocessing to do this task, and -t

means using the multithreading.




Reminders

When you do multiprocessing tasks, if you create multiple threads for

each process, you will get 0 points.

This assignment is not allowed to be submitted late, so please finish it as

soon as possible.

If you have any questions, feel free to contact us via N TU COOL forum or

be [Programming hw41.

Your files are compiled on the CSIE workstation, so make sure it can work

smoothly on the workstation.