# Form13
These two notebooks show how to use Neo4j with Amazon SageMaker.  

1. [embedding.ipynb](embedding.ipynb) is first.  In it you connect to a Neo4j instance, load data and compute an embedding.  You then load that data into AWS S3.
2. [learning.ipynb](learning.ipynb) is second.  It takes the data from S3 and trains a supervised learning model using SageMaker.
