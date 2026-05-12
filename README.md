# RAG Workshop (Day 1)

Hands-on introduction to Retrieval-Augmented Generation (RAG):
- embeddings
- chunking
- vector store (ChromaDB)
- augmentation + generation

---

## Required Credentials

This workshop requires two credentials:

**1. OpenAI API key** (`OPENAI_API_KEY`)
- Отримати тут: [https://platform.openai.com/](https://platform.openai.com/)
- Sign up → API keys → Create new secret key

**2. Telegram Bot Token** (`TELEGRAM_TOKEN`) — for the bot exercise
- Відкрийте Telegram → знайдіть [@BotFather](https://t.me/BotFather)
- Надішліть `/newbot` → дайте ім'я боту → отримайте токен виду `123456:ABC-DEF...`

> Do not hardcode secrets in notebook cells.

---

## Open In Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NatalyUA/RAG-workshop/blob/main/rag_workshop_00_intro_v2.ipynb)

Direct link:
https://colab.research.google.com/github/NatalyUA/RAG-workshop/blob/main/rag_workshop_00_intro_v2.ipynb

---

## Contents (Day 1)

- `rag_workshop_00_intro_v2.ipynb`
- `RAG_intro.png`
- `RAG_mindmap.png`
- `RAG_end-to-end_pipeline.png`

---

## Quick Start (for participants)

1. Open the notebook in Colab using the badge above.
2. Create your own editable copy: `File → Save a copy in Drive`.
   - Important: opening the link does **not** automatically create a personal copy.
   - The shared GitHub link opens the source notebook version in Colab.
3. Set your credentials in **Colab Secrets** (left panel → 🔑 key icon):
   - `OPENAI_API_KEY` — your OpenAI key
   - `TELEGRAM_TOKEN` — your Telegram bot token
   - Alternative: set as a temporary environment variable in a cell (not recommended for shared notebooks).
4. Run cells from top to bottom.
5. If package installation asks for a runtime restart — restart and run all again.

---

## Troubleshooting

- **`OPENAI_API_KEY is missing`**
  - Add your key in Colab Secrets or set it in a cell before the `OpenAI()` client is created.

- **`TELEGRAM_TOKEN is missing`**
  - Create a bot via [@BotFather](https://t.me/BotFather) and add the token to Colab Secrets.


