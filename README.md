PUC Big Data workshop assignment
================================

### Docker
We use Jupyter's docker image `pyspark-notebook`. To run it, execute:

    docker run -p 8888:8888 jupyter/pyspark-notebook:latest start-notebook.sh --NotebookApp.token=""
