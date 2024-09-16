# AI Design Wins 2024 Demos

This repository contains notebooks that explain how Azure AI Search works, RAG with Azure Open AI, building Agent with Azure Open AI Function calling.

## Pre-requisites
The following Azure resources need to be provisioned before running the demo
1. Azure AI Search
2. Azure Open AI service
## Environment setup


1. Create a .env with these variables, with the values taken from `.env.sample`.

    ```shell
    AZURE_OPENAI_SERVICE="SERVICE-NAME"
    AZURE_OPENAI_API_KEY=AZURE_OPENAI_API_KEY
    AZURE_OPENAI_DEPLOYMENT_NAME=DEPLOYMENT-NAME
    AZURE_OPENAI_EMBEDDING_DEPLOYMENT=AZURE_OPENAI_EMBEDDING_DEPLOYMENT
    AZURE_SEARCH_SERVICE=SEARCH-SERVICE-NAME
    AZURE_SEARCH_SERVICE_KEY=AZURE_SEARCH_SERVICE_KEY
    ```

2. Create a Python virtual environment or open the project in a container. (Skip if using CodeSpace)

3. Install the requirements (Skip if using CodeSpace):

    ```shell
    pip install -r requirements.txt
    ```

## Notebooks

These are the available notebooks, in suggested order:

* [Vector Embeddings Notebook](./notebooks/01_vector_embeddings.ipynb)
* [Azure AI Search Notebook](./notebooks/02_azure_ai_search.ipynb)
* [RAG with Azure AI Search](./notebooks/03_rag.ipynb)
* [Build Agent with Function calling](./notebooks/04_build_agent.ipynb)

