# my_first_chatbot

Hopscotch Support is a Streamlit chatbot that answers customer questions using
the return policy in `hopscotch_policy.md` and the OpenRouter API.

## Setup

Requires Python 3.14.8 (see `.python-version`) and [`uv`](https://docs.astral.sh/uv/).

```bash
uv venv
source .venv/bin/activate
uv pip install -r requirements.txt
cp .env.example .env
```

Add your OpenRouter API key to `.env`, then start the app:

```bash
streamlit run app.py
```
