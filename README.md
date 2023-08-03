# PDFQA

# ChatGPT Chatbot for PDF Files

Integrate GPT-4 and LangChain to create a seamless conversational interface for querying content from PDF files.

## Table of Contents

- [Research Points](#research-points)
- [Related Papers](#related-papers)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [License](#license)

## Research Points

### 1. PDF Parsing and Text Extraction

- Understand the structure of PDFs.
- Extract text and graphics.
- Convert non-textual info into a textual format.

### 2. Document Indexing and Information Retrieval

- Breakdown PDF content.
- Index and search the extracted info.
- Return relevant info in response to queries.

### 3. Natural Language Understanding (NLU)

- Interpret user queries.
- Translate user intent.
- Understand context and manage dialog.

### 4. Chatbot Interaction and Feedback Loop

- Provide a conversational interface.
- Gather feedback and improve responses.
- Allow query refinements.

### 5. Integration of All Components

- Integrate PDF extraction, indexing, and chat interface.
- Handle large data volumes.
- Ensure real-time performance.

## Related Papers

### PDF Parsing and Text Extraction

- Smith, R. (2007). [An overview of the Tesseract OCR engine](#link-to-paper).
- Zanibbi, R., et al. (2002). [A survey of table recognition](#link-to-paper).

### Document Indexing and Information Retrieval

- Manning, C. D., et al. (2008). [Introduction to Information Retrieval](#link-to-paper).

### Natural Language Understanding (NLU):

- Jurafsky, D., & Martin, J. H. (2019). Speech and Language Processing. Draft of the third edition.
- Vaswani, A., Shazeer, N., Parmar, N., Uszkoreit, J., Jones, L., Gomez, A. N., ... & Polosukhin, I. (2017). Attention is all you need. Advances in neural information processing systems.

### Integration of All Components:
- Reimers, N., & Gurevych, I. (2019). Sentence-BERT: Sentence embeddings using Siamese BERT-networks. arXiv preprint arXiv:1908.10084.
- Devlin, J., Chang, M. W., Lee, K., & Toutanova, K. (2018). BERT: Pre-training of deep bidirectional transformers for language understanding. arXiv preprint arXiv:1810.04805.

## Getting Started

1. **Installation**
    ```bash
    git clone https://github.com/your-repo-url.git
    cd your-repo-name
    pip install -r requirements.txt
    ```

2. **Usage**
    ```bash
    python main.py --input "path-to-pdf"
    ```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)



Related projects:

1. Pinecone: https://github.com/mayooear/gpt4-pdf-chatbot-langchain
2. faiss: https://github.com/anpigon/gpt4-pdf-chatbot-langchain-faiss
