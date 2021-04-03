# AIFA-Assignment-1
Solution for Assignment 1, AIFA Spring 2021

## Table of Contents
1. Problem Description
2. Installation Guide
3. Contributors

## Problem Description
This assignment demonstrates the implementation of a basic heuristic algorithm to solve the first problem of Assignment - 1, that is Multi-Agent Path Finding. In this implementation, given the grid (or floor space of warehourse) dimensions, locations of the obstacles on the grid, initial and final positions of the robots and the objects to move, the algorithm returns the path that the robots should consider taking.

An in-depth explanation of the algorithm can be found in the file `AIFA Report.pdf`.

## Installation Guide
The code has been written and implemented in an Ipython (or Jupyter) Notebook and has been run using Python version 3. The code depends on four text files for the various kinds of inputs. It makes use of heapq package besides the base package provided by Python.

The steps for running the code are as follows:
0. Install Jupyter-Notebook (if not already installed)
```console
foo@bar:~$ pip install notebook
```
1. Clone the Git Repository and install heapq.
```console
foo@bar:~$ git clone https://github.com/mridul2899/AIFA-Assignment-1.git
foo@bar:~$ pip install heapq
```
2. Enter into the repository and start the notebook.
```console
foo@bar:~$ cd AIFA-Assignment-1
foo@bar:~/AIFA-Assignment-1$ jupyter notebook
```
3. Now, navigate the folder and open the notebook `AIFA-ASSIGNMENT-final.ipynb`. Once opened, run all the cells from the beginning sequentially. The original outputs will be generated on the default inputs provided. For running the code on different sets of input, make appropriate changes in the text files. The information about the inputs in each of these is given in the report.

Post running these cells, after some short time, the paths which the robots should take will appear.

## Contributors
The following students have contributed equally towards solving the assignment:
1. Saransh Gupta           |  17QM30005
2. Mridul Agarwal          |  17QE30008
3. Aniruddha Chattopadhyay |  17QE30007
4. Divyanshu Sheth         |  18QE30008
