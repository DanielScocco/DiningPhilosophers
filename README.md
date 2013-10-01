DiningPhilosophers
==================

Summary: Java implementation of the Dining Philosophers problem with graphic animations,
made as a course project for MC504 - Unicamp (2013, 2nd Semester).

Author: danielscocco@gmail.com

Description: The main goal of this program is to explore the eficiency and level of
concurrency of various algorithms that try to solve the Dining Philosophers problem.

Results: Please refer to the PDF inside the repository for an explanation of the algorithms,
tests and results (PDF in portuguese).

How to Run: Once you have the DiningPhilosophers directory on your machine simply compile it
from outside the directory with "javac DiningPhilosophers/Philosophers" and then
run it with "java DiningPhilosophers.Philosophers".

Code Details: Notice that inside the main Phisolophers class you'll find 5 different algorithms
for getting and releasing the forks (e.g., getForks1(), putForks1(), getForks2, putForks2(), etc.). 
You must use the same algorithm number on both getForks() and putForks(). You can
specify this inside the run() method of the Philosophers class.
