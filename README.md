# MediQuery

**MediQuery** is an AI-powered health assistant that uses verified medical sources, including WHO and government health documents, combined with Retrieval-Augmented Generation (RAG) to provide trusted, multilingual, and real-time symptom guidance.

> **Disclaimer:** This tool is for educational purposes only and is not a substitute for professional medical advice.

---

## 📌 Features
- Uses **IBM Granite LLM** (`granite-3-3-8b-instruct`) for natural language understanding.
- Integrated **RAG** to fetch information from verified medical PDFs.
- Real-time information retrieval from trusted health sources.
- Multilingual query support.
- Educational guidance on symptoms, possible conditions, treatments, and prevention measures.

---

## 🛠️ Tech Stack
- **IBM Cloud Lite Services**
- **IBM Granite Foundation Model**
- **RAG (Retrieval-Augmented Generation)**
- **Watson Discovery**
- Verified **WHO** and **Government Health PDFs**

---

## 📂 Project Workflow
1. **Project Definition & Setup** – Defining MediQuery’s purpose and scope.
2. **Model Selection** – Choosing `granite-3-3-8b-instruct` for the AI core.
3. **Knowledge Base Upload** – Adding WHO and government health PDFs.
4. **Agent Configuration** – Setting operational instructions.
5. **Initial Testing** – Running prompts to evaluate baseline performance.
6. **RAG Integration** – Linking documents from vector index for contextual retrieval.
7. **RAG Query Testing** – Assessing retrieval accuracy with health-related queries.
8. **Agent Deployment** – Saving and finalizing MediQuery for ongoing use.

---

## 🚀 Getting Started

### Prerequisites
- IBM Cloud account with access to **Watson Discovery** and **Granite Models**.
- Verified medical documents in **PDF** format for ingestion.

### Steps
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/MediQuery.git
   cd MediQuery
2. Log in to IBM Cloud and set up:
  - Watson Discovery instance.
  - Granite LLM (granite-3-3-8b-instruct).

3. Upload verified medical PDFs (WHO and government sources) to Watson Discovery.

4. Configure RAG integration:
  - Create a Vector Index from the uploaded documents.
  - Enable retrieval for the MediQuery agent.

5. Set Agent Instructions to ensure responses are accurate, multilingual, and educational.

6. Test the Agent with example prompts to validate functionality.

7. Deploy and Save the Agent for ongoing use.
