# Setup Guide — Lecture 5 Notebook

This guide walks you through getting the notebook running on your own machine. The notebook demonstrates computer-assisted open coding using BERTopic, Word2Vec, and an optional local LLM (Ollama) for inductive qualitative coding.

---

## What you need

| Tool | Purpose |
|---|---|
| Python 3.11 or 3.12 | Running the notebook |
| Jupyter Lab or Jupyter Notebook | Opening the `.ipynb` file |
| Ollama (optional) | Local LLM for automated open coding |

**Important:** Python 3.13+ is not yet compatible with some ML packages used here (hdbscan, umap-learn). Stick to 3.11 or 3.12.

---

## Step 1 — Install Python 3.12

**Mac:**
Install via [Homebrew](https://brew.sh) (recommended):
```bash
brew install python@3.12
```
Or download the installer from [python.org/downloads](https://www.python.org/downloads/).

**Windows:**
Download from [python.org/downloads](https://www.python.org/downloads/). During install, tick **"Add Python to PATH"**.

**Linux:**
```bash
sudo apt install python3.12 python3.12-venv
```

---

## Step 2 — Create a virtual environment

A virtual environment keeps these packages isolated from the rest of your system.

```bash
# Navigate to wherever you put the notebook folder
cd path/to/notebook_folder

# Create the environment
python3.12 -m venv .venv

# Activate it
# Mac / Linux:
source .venv/bin/activate
# Windows:
.venv\Scripts\activate
```

You should see `(.venv)` at the start of your terminal prompt.

---

## Step 3 — Install the required packages

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

This installs: pandas, scikit-learn, BERTopic, sentence-transformers, UMAP, HDBSCAN, Plotly, Gensim, and Jupyter.

The first install takes a few minutes — there are large ML packages.

---

## Step 4 — Register the kernel with Jupyter

So Jupyter sees the virtual environment you just created:

```bash
python -m ipykernel install --user --name lecture05 --display-name "Lecture 05 (.venv)"
```

---

## Step 5 — Open the notebook

```bash
jupyter lab notebook.ipynb
```

When the notebook opens, select the kernel **"Lecture 05 (.venv)"** from the kernel menu (top right).

---

## Step 6 — Point the notebook to your data

Open the second code cell (the one with `CORPUS_PATH`). Change the path to point to your own CSV file:

```python
CORPUS_PATH = Path('path/to/your/corpus.csv')
```

Your CSV needs at minimum these columns:

| Column | Description |
|---|---|
| `doc_id` | Unique identifier for each post |
| `link` | URL to the original post |
| `text` | Full text of the post |

Optional but used if present: `title`, `body`, `text_length`.

---

## Step 7 — Install Ollama (optional)

The Ollama section of the notebook runs a local LLM to apply the inductive coding instructions to your documents. It is optional — the notebook skips it cleanly if Ollama is not running.

1. Download and install from [ollama.com](https://ollama.com)
2. Pull the model used in the notebook:
   ```bash
   ollama pull gemma3:4b
   ```
3. Start the server before running the Ollama cells:
   ```bash
   ollama serve
   ```

The model is ~3 GB. Once downloaded it runs fully offline.

---

## Example outputs

The `example_outputs/` folder contains outputs from a run on 100 Reddit posts so you can see what the pipeline produces before running it yourself:

- **`open_coding_sample_100.csv`** — 100 posts coded by Gemma with relational alters, open codes, and analytic memos.
- **`thematic_analysis.md`** — A four-theme thematic analysis written by Gemma from the coded material.

---

## Troubleshooting

**`ModuleNotFoundError`** — You are probably using the wrong kernel. Check the kernel selector in the top-right of Jupyter and switch to "Lecture 05 (.venv)".

**`hdbscan` / `umap` install fails** — You are likely on Python 3.13. Downgrade to 3.12 (see Step 1).

**Ollama cells print "Skipping — server not running"** — Run `ollama serve` in a separate terminal window before executing those cells.

**Plotly plot is blank** — Try running the cell again. If it stays blank, make sure you installed `plotly==5.24.1` (version 6.x has a known incompatibility with standard Jupyter).
