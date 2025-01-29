# Sumarizerr

## Overview
Sumarizerr is a project designed to facilitate the process of document ingestion, retrieval, and summarization, leveraging advanced language models and tools from IBM Watson and Hugging Face. This project aims to provide a robust solution for querying and summarizing large documents, such as company policies, using a conversational retrieval system.

The core functionality of Sumarizerr includes:
- Downloading and loading documents.
- Splitting documents into manageable chunks.
- Creating embeddings for document chunks.
- Building a retrieval-based QA system.
- Enabling interactive querying and summarization of documents.
- Maintaining conversational context across multiple queries.

## Installation
To get started with the project, you need to install the required dependencies. You can install them using the following commands in your Jupyter Notebook or terminal:

```sh
pip install --user "ibm-watsonx-ai==0.2.6"
pip install --user "langchain==0.1.16"
pip install --user "langchain-ibm==0.1.4"
pip install --user "huggingface==0.0.1"
pip install --user "huggingface-hub==0.23.4"
pip install --user "sentence-transformers==2.5.1"
pip install --user "chromadb"
pip install --user "wget==3.2"
