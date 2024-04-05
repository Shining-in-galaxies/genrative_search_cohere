# Generative Search with Cohere

Welcome to the `genrative_search_cohere` project! This repository contains a unique blend of generative AI and search capabilities powered by Cohere's advanced natural language processing platform. Designed with Python, this project aims to leverage the state-of-the-art in AI to generate insightful responses to queries related to careers in AI and beyond.

## Overview

The `genrative_search_cohere` project showcases an innovative approach to searching and generating responses from a large corpus of text on AI career development. By integrating Cohere's NLP API, we're able to provide detailed answers to complex questions, making it an invaluable resource for anyone looking to navigate the field of AI.

## Project Structure

This repository contains a single Jupyter Notebook file:

- `genrative_search_cohere.ipynb`: This notebook outlines the entire process from text chunking, embedding generation, search index building, to generating coherent and contextually relevant answers.

## Features

- **Text Chunking**: Break down large texts into manageable chunks for better processing.
- **Embedding Generation**: Use Cohere to transform text into high-dimensional vectors that capture the semantic meaning.
- **Search Index**: Build an efficient search index to quickly retrieve relevant sections of text based on query embeddings.
- **Generative Response**: Generate detailed and contextually relevant responses to user queries, leveraging the power of Cohere's generative models.

## Setup and Installation

Ensure you have Python installed on your system. Then, install the required libraries by running:

```bash
pip install cohere numpy pandas dotenv annoy
```

You will also need to obtain an API key from Cohere and store it in a `.env` file as `COHERE_API_KEY`.

## Usage

Open the `genrative_search_cohere.ipynb` in Jupyter Notebook or JupyterLab and follow the instructions within to start generating answers to your queries.
