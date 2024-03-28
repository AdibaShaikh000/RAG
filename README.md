# RAG Application for Question Answering

This repository contains the code base for a Retrieval-Augmented Generation (RAG) application designed for question answering tasks. The application leverages Lang Chain, FAISS, and OpenAI to provide accurate and efficient responses to user queries.

## Overview

The RAG application utilizes a combination of retrieval-based and generation-based techniques to answer user questions. It leverages Lang Chain framework for LLM usage, FAISS for efficient similarity search, and OpenAI for language modeling.

## Features

- **Retrieval-Augmented Generation (RAG):** Integrates retrieval-based and generation-based methods for question answering.
- **Lang Chain:** Framework for development of applications powered by large language models (LLM)
- **FAISS:** Enables fast and efficient similarity search for retrieving relevant information.
- **OpenAI:** Utilizes state-of-the-art language models for generating accurate responses to user queries.

## Setup

1. Clone the repository:

git clone https://github.com/AdibaShaikh000/RAG.git

2. Install dependencies:

pip install -r requirements.txt

3. Obtain API key:

Create your API keys for Lang Chain and OpenAI on Open AI website.
You can locate your key here:
https://platform.openai.com/api-keys

4. Dataset:

The Approved IP Law PDF dataset is sourced from Huggingface's datasets.
https://huggingface.co/datasets/omar87/pdf-laws

5. Run the file:

You can directly execute the Jupyter notebook of the project to gain insight into each component

## Usage

1. Send a question to the RAG application via the provided API endpoint.
2. The application will process the question using Lang Chain and retrieve relevant information using FAISS.
3. OpenAI will generate a response based on the retrieved information, and the application will return the answer to the user.
