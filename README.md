# Generative AI and Agentic AI Tutorials

Four independent notebooks introducing text generation, language model components, chat applications, and document question answering.

## Notebook Index

| Notebook | What it demonstrates |
|---|---|
| `GenAI_Tutorials1.ipynb` | GPT-2 text generation and decoding settings |
| `GenAI_Tutorial_2.ipynb` | Tokenization and sentence embeddings |
| `GenAI_Chatbot_T3.ipynb` | Gradio placement assistant using the Hugging Face Inference API |
| `PDF_RAG_System.ipynb` | PDF text extraction, FAISS retrieval, and contextual answers |

These are separate tutorials; each notebook has its own execution flow.

## Tech Stack

Python, Jupyter Notebook, Hugging Face Transformers and Hub, Sentence Transformers, FAISS, PyTorch, pypdf, scikit-learn, and Gradio.

## Run a Notebook

Create an environment and install the libraries used by the tutorials:

```bash
python -m venv .venv
# Activate the environment for your shell, then:
python -m pip install jupyter transformers sentence-transformers scikit-learn huggingface_hub gradio pypdf faiss-cpu torch pandas numpy
jupyter notebook
```

Run a selected notebook's cells in order. The chatbot requires a Hugging Face access token for its configured inference provider. The PDF notebook uses a file-upload flow in Google Colab; model downloads require network access.

## Author

**Gireesh Sadanand Patgar** · [GitHub](https://github.com/gireeshpatgar17)
