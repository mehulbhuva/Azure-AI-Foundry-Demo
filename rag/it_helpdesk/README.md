# RAG Pack: IT Helpdesk Agent

This folder contains markdown knowledge base docs for a troubleshooting agent.

**Upload Guidance (Azure AI Foundry)**
1. Create a Data asset (Files) and upload `docs/`.
2. In your Chat Agent, add a Retrieval tool pointing to this data asset.
3. Set chunk size ~1,000–1,500 characters; overlap 150–200.
4. Enable citations for grounded answers.
