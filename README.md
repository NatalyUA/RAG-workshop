# RAG Workshop (Day 1)

Hands-on introduction to Retrieval-Augmented Generation (RAG):
- embeddings
- chunking
- vector store (ChromaDB)
- augmentation + generation

## Required API Key

This workshop requires:
- OpenAI API key (`OPENAI_API_KEY`)

Do not hardcode secrets in notebook cells.


## Open In Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NatalyUA/RAG-workshop/blob/main/rag_workshop_00_intro_v2.ipynb)

Direct link:
https://colab.research.google.com/github/NatalyUA/RAG-workshop/blob/main/rag_workshop_00_intro_v2.ipynb

## Contents (Day 1)

- `rag_workshop_00_intro_v2.ipynb`
- `RAG_intro.png`
- `RAG_mindmap.png`
- `RAG_end-to-end_pipeline.png`

## Quick Start (for participants)

1. Open the notebook in Colab using the badge above.
2. Create your own editable copy: `File -> Save a copy in Drive`.
   - Important: opening the link does **not** automatically create a personal copy.
   - The shared GitHub link opens the source notebook version in Colab.
3. Set your `OPENAI_API_KEY`:
   - Preferred: Colab Secrets (left panel -> key icon).
   - Alternative: temporary environment variable in a cell.
4. Run cells from top to bottom.
5. If package installation asks for restart, restart runtime and run all again.



## Troubleshooting

- `OPENAI_API_KEY is missing`
  - Add your key in Colab Secrets or set it in a cell before creating `OpenAI()` client.


