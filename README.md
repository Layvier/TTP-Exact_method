# TTP-Exact_method
An exact method for the Travelling Tournament Problem

This algorythm finds the solution to the TTP (http://en.wikipedia.org/wiki/Traveling_tournament_problem) problem using branch and bound.
The "genererCalendrier()" method in the ttp class is a recursive method exploring the tree of solutions, 
which stops evaluating a branch when the partial solution built is unvalid or have a higher cost than the best cost found so far.
