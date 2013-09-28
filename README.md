DiningPhilosophers
==================

Description: Java implementation of the Dining Philosophers problem with graphic animations.
Author: danielscocco@gmail.com

Notice that inside the main Phisolophers class you'll find 5 different algorithms
for getting and releasing the forks (e.g., getForks1(), putForks1(), getForks2, putForks2()). 
You must use the same algorithm number on both getForks() and putForks(). You can
specify this inside the run() method of the Philosophers class.

Algorithms 3 and 4 are the only ones that guarantee mutual exclusion, no deadlock and no starvation. 
The others have one of more of these problems.
