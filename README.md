# AIDAMS Lab 4: An LLM Extraction You Can Trust

Submitted by Labergere Adrien (ID B00822082).

## Files

- `lab4.ipynb` — the completed notebook (all questions answered, outputs visible)
- `excerpts.json`, `gold_labels.json`, `recorded_responses.json`, `aurelia_report_chunks.json` — the data given with the lab

## How to run

1. Install dependencies: `pip install numpy pandas matplotlib scipy pydantic scikit-learn`
2. Open `lab4.ipynb` in Jupyter (or VS Code) from this folder. The data files must sit next to the notebook.
3. Run **Kernel → Restart & Run All**. `BACKEND = "recorded"` in the setup, so no API key is needed for the main parts.

## Optional parts

- **D2 (dense embeddings):** needs `pip install sentence-transformers` (the first run downloads the `all-MiniLM-L6-v2` model, about 90 MB).
- **A2 (own model):** needs a local [Ollama](https://ollama.com) server with `ollama pull llama3.2`. If Ollama is not running, the cell only prints a message and the rest of the notebook is not affected.
