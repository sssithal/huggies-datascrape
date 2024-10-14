Huggies Product Data Analysis

This repository contains a project focused on web scraping, data processing, and interactive AI querying for product data on the Huggies website. The primary goal is to retrieve product information, process it for rapid access, and enable user interaction through a conversational AI interface powered by GPT-3.5. Below is an overview of the key features of the project.
Features

    Web Scraping:
        Scraped product details from the Huggies website using BeautifulSoup.
        Converted scraped data into JSON format for structured storage and ease of manipulation.

    Data Processing:
        Preprocessed product information into manageable chunks using Langchain’s text-processing libraries.
        Embedded text data with OpenAI Embeddings for enhanced retrieval, storing them in a Vector Database for efficient access.

    AI Interaction:
        Developed an interface for interacting with GPT-3.5 through Langchain, enabling dynamic querying of the VectorDB to retrieve relevant product information.
        Implemented and tested prompt engineering techniques to refine how the AI understands user queries, providing accurate information and recommendations regarding products.
