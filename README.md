# Topological Data Analysis on the Apache Ivy Codebase

## File descriptions

download_urls: Includes download URLs of all Java files in 'ant-ivy/src/java/org/apache
/ivy' of the official Apache Ivy codebase.

CodeEmbeddingsGenerator: Python file that produces the data folder of code embeddings on all classes, methods, and tokens.

tda.yml: Conda environment used for analytical engineering.

AnalyticalEngineering1: Jupyter notebook that includes TDA on the emebedding data.

AnalyticalEngineering2: Jupyter notebook that includes TDA on the emebedding data.

figs: Folder of static and interactive plots produced from analysis.


## Setup

### Install Packages

Go into your terminal and run the following commands:

```
pip install torch
```
```
pip install tree-sitter-java
```
```
pip install tree-sitter
```

### Get UniXcoder

Download [unixcoder.py](https://github.com/microsoft/CodeBERT/blob/master/UniXcoder/unixcoder.py) from its official site, then move it into the same directory as CodeEmbeddingsGenerator.py.


## Instructions

1. Run CodeEmbeddingsGenerator.py to get the code embeddings data.

2. Use tda.yml to create a new conda environment to run analytical engineering code.
