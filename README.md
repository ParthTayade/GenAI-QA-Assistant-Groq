# GenAI QA Assistant using Groq

A production-oriented conversational AI application built with Python, LangChain, Streamlit, and Groq LLMs. The application provides fast, interactive question answering through a clean web interface and demonstrates practical integration of modern Generative AI technologies.

Overview

GenAI QA Assistant is an interactive conversational AI application designed to answer natural-language questions using a Large Language Model (LLM) served through Groq.

The project demonstrates how to integrate an LLM into an application using LangChain's model abstraction layer, expose it through a Streamlit interface, and securely manage API credentials through environment variables.

The architecture is intentionally lightweight and modular, making it suitable as a foundation for extending the application with capabilities such as RAG, conversation memory, tool calling, structured outputs, and AI agents.

Key Features
Conversational Question Answering — Ask natural-language questions and receive contextual AI-generated responses.
Groq LLM Integration — Uses Groq's high-speed inference infrastructure for low-latency responses.
LangChain Integration — Uses LangChain to manage the LLM interaction layer.
Interactive Streamlit UI — Provides a simple and responsive browser-based interface.
Environment-Based Configuration — API credentials are managed securely using environment variables.
Modular Architecture — Designed for future integration of RAG, tools, agents, memory, and additional LLM providers.
Fast Inference — Takes advantage of Groq's inference capabilities for responsive conversational interactions.
Architecture
                    ┌──────────────────────┐
                    │      User Query      │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │    Streamlit UI      │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │      LangChain       │
                    │    LLM Abstraction   │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │     Groq LLM API     │
                    │  High-Speed Inference│
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │   Generated Response │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │      Streamlit UI     │
                    └──────────────────────┘
Technology Stack
Category	Technology
Language	Python
LLM Provider	Groq
LLM Integration	LangChain
Frontend	Streamlit
API Configuration	Environment Variables
Dependency Management	pip
Version Control	Git / GitHub


License

This project is intended for educational and portfolio purposes.

Author

Parth Tayade

AI/ML Engineer | Generative AI | LLM Applications | RAG
