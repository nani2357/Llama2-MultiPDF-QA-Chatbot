# Llama2-MultiPDF-QA-Chatbot
Chat with Multiple PDFs using Llama 2 and LangChain


# Multi-PDF Question-Answering with Llama 2 and LangChain

## Overview

This project aims to build a question-answering system that can retrieve and answer questions from multiple PDFs using the Llama 2 13B GPTQ model and the LangChain library.

## Prerequisites

- Python 3.x
- NVIDIA GPU (Optional but recommended)

## Data

The project uses earnings reports from Tesla, Nvidia, and Meta in PDF format. These PDFs are loaded and processed to serve as the knowledge base for the question-answering system.

## Features

- **PDF Loading**: Uses `PyPDFDirectoryLoader` from LangChain to load multiple PDFs into the system.
- **Text Splitting**: Utilizes `RecursiveCharacterTextSplitter` to split the loaded PDFs into manageable text chunks.
- **Question-Answering**: Leverages the Llama 2 13B GPTQ model to generate answers to user queries based on the loaded PDFs.

## Usage

1. Load the PDFs into the system.
2. Initialize the Llama 2 13B GPTQ model and LangChain components.
3. Use the system to answer questions based on the loaded PDFs.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
