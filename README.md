### Playground
Exploring ideas 

#### MLFlow
*   pip install mlflow

* Run locally on 8080 (or other) port
mlflow server --host 127.0.0.1 --port 8080


##
Notebook  | Description
------------- | -------------
[Mlflow intro](https://github.com/algodigger/playground/blob/main/notebooks/mlflow.ipynb) | Basic mlflow introdcution including checking the server, training, pulling metrics data and displaying it. Fetching model artifacsts and running prediction
[RAG and Reranking](https://github.com/algodigger/playground/blob/main/notebooks/reranking.ipynb) | Demonstrate [FlagEmbedding](https://github.com/FlagOpen/FlagEmbedding/tree/master/FlagEmbedding/reranker) and 'BAAI/bge-reranker-large' reraking 
[ViT demo](https://github.com/algodigger/playground/blob/main/notebooks/visual_transformers.ipynb) | Visual transformer demo
[LORA FT](https://github.com/algodigger/playground/blob/main/notebooks/databrics/FineTune1_%20Fine%20tune%20%20with%20Lora.ipynb) | Run LORA finetuing of small llm using databriks instance and data stored on delta lake via spark
[DATABRICS demo](https://github.com/algodigger/playground/blob/main/notebooks/databrics/FineTune0_%20data%20preparation.ipynb) | Load HF dataset into the deltaa laake with spark