#  LLaMA Doc-Constrained QA

A modified version of the LLaMA language model that strictly answers questions based only on a provided document. This project is useful for secure, context-restricted applications like legal, academic, or enterprise document Q&A.

##  Features

-  Answers strictly from the input document
-  Accepts plain text, PDF, or other formats as source
-  Based on Meta's LLaMA architecture (v1/v2/v3 compatible)
-  Fast inference with quantized or original models
-  Optional retrieval or chunk-based document processing

## 📦 Installation

bash
git clone https://github.com/yourusername/llama-doc-qa.git
cd llama-doc-qa
pip install -r requirements.txt

## Model Architecture
This project modifies LLaMA by injecting the document context at runtime and preventing hallucination through:

- Prompt engineering with strict instructions

- Optional retrieval-based chunking (if enabled)

- Context window management to avoid overflow


## Contributing
Pull requests are welcome. For major changes, please open an issue first.

