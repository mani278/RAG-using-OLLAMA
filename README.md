# RAG-using-OLLAMA

### Setting up Ollama:
Download and install Ollama from https://ollama.com/download

open **cmd** and type ***ollama --version***. If it show the version, it is installed, otherwise reinstall.

### Downloading Model:
In **cmd** type *ollama pull {model_name}*. For example, ***ollama pull gemma:2b***.

I will be using gemma 2billion on this tutorial.

### Working with code
Install libraries from requiements (if using gpu, use ***pip install faiss-gpu***)

Change the document directory path.

Change the query and run.

**Bonus:** Type ***Ollama list*** to list all the downloaded model.
