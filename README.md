# GenAI QA Assistant using Groq

A production-oriented conversational AI application built with Python, LangChain, Streamlit, and Groq LLMs. The application provides fast, interactive question answering through a clean web interface and demonstrates practical integration of modern Generative AI technologies.

## Live Demo

[Watch Live Demo](https://drive.google.com/file/d/1_oCHEkzy4jpe0Q-TIhuIfvwghO3b7Ove/view?usp=drive_link)

## Overview

The **GenAI QA Assistant** is a lightweight conversational AI application that enables users to interact with a Large Language Model through a simple web interface.

The application integrates **LangChain** with **Groq's LLM inference platform** and uses **Streamlit** to provide an interactive user experience.

The project demonstrates the core components required to build an LLM-powered application while maintaining a modular architecture that can be extended with RAG, tool calling, agentic workflows, memory, and evaluation pipelines.

## Key Features

- **Conversational Question Answering**
- **Groq LLM Integration**
- **LangChain-based LLM interaction**
- **Interactive Streamlit interface**
- **Secure API key management**
- **Fast LLM inference**
- **Extensible architecture**

## Architecture
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

## Technology Stack

| Category | Technology |
|---|---|
| Programming Language | Python |
| LLM Provider | Groq |
| LLM Framework | LangChain |
| Frontend | Streamlit |
| Configuration | Environment Variables |
| Package Management | pip |
| Version Control | Git / GitHub |


### License

This project is intended for educational and portfolio purposes.

### Author

Parth Tayade

AI/ML Engineer | Generative AI | LLM Applications | RAG
