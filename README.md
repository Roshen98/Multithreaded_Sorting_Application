# Multithreaded_Sorting_Application

This program is to perform a multithreaded sorting algorithm. Details are as follow:

A list of integers is divided into two smaller lists of equal size. Two separate threads (which we will term sorting threads) sort each sub-list using a sorting algorithm of your choice. The two sub-lists are then merged by a third thread—a merging thread —which merges the two sub-lists into a single sorted list.

NOTE : Because global data are shared cross all threads, perhaps the easiest way to set up the data is to create a global array. Each sorting thread will work on one half of this array. A second global array of the same size as the unsorted integer array will also be established. The merging thread will then merge the two sub-lists into this second array. Graphically, this program is structured as follow:

This programming project will require passing parameters to each of the sorting threads. In particular, it will be necessary to identify the starting index from which each thread is to begin sorting.

COMPILATION: g++ multiThread.cpp ./a.out


[multiThreadReport.pdf](https://github.com/Roshen98/Multithreaded_Sorting_Application/files/8456191/multiThreadReport.pdf)
