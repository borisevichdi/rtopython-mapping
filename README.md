# rtopython-mapping
Mapping the R standard functions into the python code

## What is it

This is a collaboration repo to try to implement each basic R function as a python code.

## How to help

Join us in describing each basic R function as python code.

* Create an issue named as an R function
* Inside the issue create one code block with the implementation code
* Implementation should be a python callable
* Functions should be implemented as a python function using "def(...)"
* Methods and attributes should be implemented as a python class method using "def(self, ...)"
* Always assume that proper arguments parsing will be done for you
* In R everything is a vector (even a single number!), in python it is convinient to use individual variables. The implementation should work both with individual python variables and numpy arrays, if this is expected.
* If some parts are not implemented yet - fail explicitly by using "raise NotImplemented"
* "..." from R should be treated as \*args
* Vectors from R should be represented as numpy arrays
* Dataframes from R should be represented as pandas dataframes

See https://github.com/borisevichdi/rtopython-mapping/issues/1 if in doubts.

See https://github.com/borisevichdi/rtopython-mapping/blob/main/full_map_R.py for the list of the R functions needed to be implemented.
