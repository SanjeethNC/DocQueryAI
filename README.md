# DocQueryAI

DocQueryAI is an advanced Retrieval-Augmented Generation (RAG) tool designed to create an intelligent chatbot capable of interacting with and extracting information from PDF documents. By leveraging the LLaMA index and OpenAI's API, DocQueryAI allows for sophisticated querying of documents, providing accurate and contextually relevant responses.

## Features

- **Advanced Retrieval-Augmented Generation**: Combines state-of-the-art document retrieval with powerful language generation for precise answers.
- **Custom Document Training**: Train the chatbot with your own PDFs or other document formats, making it adaptable to various use cases.
- **Interactive Query Engine**: Seamlessly ask questions and receive detailed responses based on the content of the trained documents.
- **Index Persistence**: Efficiently store and reload indexes to save time and computational resources.

## Installation

To get started with DocQueryAI, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/docqueryai.git
    ```
2. Navigate to the project directory:
    ```sh
    cd docqueryai
    ```
3. Create and activate a virtual environment:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```
4. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Ensure you have your OpenAI API key stored in a `.env` file:
    ```makefile
    OPENAI_API_KEY=your_openai_api_key
    ```
2. Place your PDF or document files in the `data` directory.
3. Run the Jupyter notebook `test.ipynb` to load documents and create the index:
    ```sh
    jupyter notebook test.ipynb
    ```
4. Follow the steps in the notebook to query the index and interact with the chatbot.

## Example Code

Acknowledgements
Thanks to the OpenAI team for their powerful API and tools.
Special thanks to the LLaMA Index community for making document indexing and querying straightforward.
