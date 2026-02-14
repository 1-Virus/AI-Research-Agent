**Autonomous AI Research & Summarization Agent**
An end-to-end automation pipeline built in n8n that performs real-time web research and generates structured summaries using advanced LLMs.

🚀 Overview
This project automates the manual task of gathering and summarizing information from the web. It utilizes an Agentic Workflow to browse the live internet, synthesize data, and update a centralized database (Google Sheets) automatically.

🛠️ Tech Stack
Orchestration: n8n
AI Model: Llama 3 (via Groq LPU for sub-second inference)
Search Engine: Tavily AI (Optimized for LLM agents)
Storage: Google Sheets & Google Drive

✨ Key Features
- Data Retrieval: Pulls research topics automatically from a Google Sheet using structured read operations.
- Agentic Search: An AI Agent autonomously uses the Tavily API to browse the live web for the latest information.
- Lightning Summarization: Groq (Llama 3) processes findings into a concise, professional summary with minimal latency.
- Auto-Sync: Dynamically updates the original Google Sheet with finalized research in real-time.

📂 How to Use
1. Download the workflow.json file from this repository.
2. Import it into your n8n instance.
3. Configure your API keys for Groq, Tavily, and Google Sheets.
4. Run the workflow to start automated research.
