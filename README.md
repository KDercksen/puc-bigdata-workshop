PUC Big Data workshop assignment
================================

### Docker
We use Jupyter's docker image `pyspark-notebook`. To run it, execute:

    docker run -p 8888:8888 jupyter/pyspark-notebook:latest start-notebook.sh --NotebookApp.token=""

### Part #1
A simple counting algorithm; given a list of words, use MapReduce paradigms to
obtain individual word counts.  Maybe display some different approaches?

The students will be required to fill in particular critical parts of code.

### Part #2
(TODO)

A slightly more complicated algorithm; obtain the average of a list of numbers
using MapReduce paradigms. Since the list is divided over individual workers,
this requires some rethinking of the problem!
