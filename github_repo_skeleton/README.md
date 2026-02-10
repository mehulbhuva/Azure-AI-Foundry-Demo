# Azure AI Foundry – IEEE Demo Pack

This repository contains three end-to-end demo packs for Azure AI Foundry Chat Agents:

1. **IT Helpdesk Agent** (RAG over KB + incidents CSV)
2. **Research Assistant** (RAG over synthetic short papers)
3. **HR Screening Bot** (RAG over resumes + candidates CSV)

## Quick Start
- Import the RAG packs in `rag/` as Data assets in Azure AI Foundry.
- Plug them into a Chat Agent with Retrieval.
- Use the prompts in each RAG pack `README.md` to demo.

## Structure
- `datasets/`: Source markdown, CSV, and PDFs.
- `rag/`: Upload-ready folders for each agent.
- `pdfs/`: Pre-rendered PDFs for slides/demos.
