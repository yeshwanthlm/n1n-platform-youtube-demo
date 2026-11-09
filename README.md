# n1n-platform-youtube-demo

A simple demo notebook that compares responses from multiple LLMs (Claude, GPT, and Gemini) through the [n1n.ai](https://n1n.ai) API platform.

## What it does

The notebook sends the same prompt to three models and prints each response along with latency and token usage:

- `claude-opus-5-5`
- `gpt-6-astra`
- `gemini-3.8-flash`

## Setup

```bash
python -m venv .venv
source .venv/bin/activate
pip install openai
```

## Run

Open `demo.ipynb` in Jupyter or VS Code and run the cells.
