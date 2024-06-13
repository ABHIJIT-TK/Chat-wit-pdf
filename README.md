# Chat with PDF

Chat with PDF is a Streamlit application that allows users to upload PDF files, process the text within them, and ask questions about the content. The app uses LangChain, Google Generative AI, and FAISS for embedding, vectorizing, and answering questions based on the uploaded PDFs.

## Features

- Upload multiple PDF files
- Extract text from PDF files
- Split text into manageable chunks
- Generate embeddings using Google Generative AI
- Vectorize text chunks using FAISS
- Answer user questions based on the content of the PDFs

## Requirements

- Python 3.8 or later
- Streamlit
- PyPDF2
- LangChain
- FAISS
- LangChain Google Generative AI
- Google Generative AI SDK
- python-dotenv

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/chat-with-pdf.git
    cd chat-with-pdf
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Create a `.env` file in the root directory and add your Google API key:
    ```plaintext
    GOOGLE_API_KEY=your_google_api_key
    ```

## Usage

1. Run the Streamlit application:
    ```bash
    streamlit run app.py
    ```

2. Open your browser and go to `http://localhost:8501`.

3. Upload your PDF files using the sidebar and click "Submit & Process".

4. Ask a question in the input field and get answers based on the content of the uploaded PDFs.



## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Streamlit](https://streamlit.io/)
- [PyPDF2](https://pypdf2.readthedocs.io/en/latest/)
- [LangChain](https://langchain.com/)
- [FAISS](https://github.com/facebookresearch/faiss)
- [Google Generative AI](https://developers.google.com/generative-ai)

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any bugs, features, or documentation improvements.

## Contact

For any questions or suggestions, please open an issue on the GitHub repository or contact the author.

