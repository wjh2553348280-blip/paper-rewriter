# Paper Rewriter

> This repository is the primary maintained version of the paper-rewriter experiments.

An AI-assisted academic writing and paper rewriting tool built with Python and Streamlit.

## Project files

- `app.py` — Streamlit application
- `ai_rewriter.py` — rewriting implementation
- `prompts.py` — prompt definitions
- `requirements.txt` — Python dependencies

## Run locally

```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\\Scripts\\activate
pip install -r requirements.txt
streamlit run app.py
```

Configure credentials locally. Never commit `secrets.toml` or API keys.