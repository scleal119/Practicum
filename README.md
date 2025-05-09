# Multi-Agent Cybersecurity Training System

This project is a modular, AI-powered training system designed to deliver personalized cybersecurity learning paths based on a user’s field of interest and experience level. Built using Langflow, OpenAI, Ollama, and ChromaDB, the system uses a multi-agent architecture to dynamically assess users and provide curated learning content.

## 🎯 Project Goal

To modernize cybersecurity education by:
- Identifying individual skill levels and learning goals
- Automatically retrieving and refining high-quality learning materials
- Delivering personalized training recommendations via an adaptive multi-agent system

## 🧠 System Architecture

The system is composed of four core agents:

- **UI Agent**: Collects user preferences (cybersecurity field + experience level)
- **Knowledge Retrieval Agent**: Searches a locally embedded ChromaDB for relevant training resources
- **Refinement Agent**: Adjusts content based on clarity, depth, and user suitability
- **Coordinator Agent**: Orchestrates tool agents and compiles the final output

## 🔧 Technologies Used

- [Langflow](https://github.com/logspace-ai/langflow) – LLM workflow orchestration
- [OpenAI API](https://openai.com/) – Language model fallback and primary inference
- [Ollama](https://ollama.com) – Local LLM serving (Mistral, Gemma)
- [ChromaDB](https://docs.trychroma.com/) – Vector store for document retrieval
- [Docker](https://www.docker.com/) – Containerized deployment
- [Markdown Wiki](https://github.com/scleal119/Practicum/wiki) – Project documentation

## 📦 Project Deliverables

- Modular Langflow flow with multi-agent orchestration
- Embedded ChromaDB containing cybersecurity learning content
- GitHub Wiki with milestone documentation
- Final project report and system presentation

## 📚 Documentation

See the [Wiki](https://github.com/scleal119/Practicum/wiki) for milestone breakdowns, system design, known issues, and future improvements.

## 🏁 Future Improvements

- Add API-connected UI (React or Streamlit)
- Integrate schema validation and logging
- Support additional LLM backends with dynamic switching
- Improve agent testing and error recovery

---

