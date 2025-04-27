# auto-control-system-sim

## Description
A program that manages multiple scheduled trains and outputs the train's status periodically using multi-threading principles.
There is a main track that will only accept one train at a time. Program implementation emphasizes mutual exclusion specifically mutexes to maintain 
critical section criteria and avoid race conditions.

## Program Output
The program will output the following...
* The time the train is doing this action represented in 'hour:minute:second:millisecond' format.
* When the train is ready to deployed onto the track.
* When the train is on the main track.
* When the train is off the main track.
