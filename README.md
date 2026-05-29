# Customer Support AI Agent using LangGraph

## Overview

This project is an AI-powered Customer Support Agent built using LangGraph and LangChain.
The agent automatically analyzes customer queries, detects sentiment, categorizes the issue, and generates intelligent responses using OpenAI models.

The workflow is designed using LangGraph, which enables multi-step AI reasoning and structured agent execution.

---

# Features

* Customer Query Classification
* Sentiment Analysis
* Automated AI Responses
* LangGraph Workflow Integration
* OpenAI LLM Integration
* Modular AI Agent Architecture
* Real-time Query Processing

---

# Technologies Used

* Python
* LangGraph
* LangChain
* OpenAI API
* Jupyter Notebook
* dotenv

---

# Project Workflow

The AI agent processes customer queries through multiple stages:

1. User submits a query
2. Query categorization
3. Sentiment analysis
4. AI response generation
5. Final response output

---

# Installation

## Clone Repository

```bash
git clone https://github.com/your-username/customer-support-ai-agent.git
cd customer-support-ai-agent
```

---

# Install Dependencies

```bash
pip install langgraph
pip install langchain
pip install langchain-openai
pip install python-dotenv
pip install openai
```

---

# Setup OpenAI API Key

Create a `.env` file in the project folder.

Example:

```env
OPENAI_API_KEY=your_openai_api_key
```

---

# Run the Project

Open Jupyter Notebook:

```bash
jupyter notebook
```

Run:

```bash
customer_support_agent_langgraph.ipynb
```

---

# Example Query

```python
query = "My internet connection keeps dropping. Can you help?"
```

---

# Example Output

```python
{
  "category": "Technical",
  "sentiment": "Negative",
  "response": "Please restart your router and check your connection settings."
}
```

---

# AI Agent Architecture

The project uses LangGraph nodes for:

* Categorization Node
* Sentiment Analysis Node
* Response Generation Node

These nodes work together as an intelligent AI workflow.

---

# Future Improvements

* Voice-based support
* Database integration
* Multi-language support
* Web application deployment
* Memory-enabled AI agent
* Retrieval-Augmented Generation (RAG)

---

# Learning Outcomes

Through this project, you can learn:

* AI Agent Development
* LangGraph Workflow Design
* LangChain Integration
* OpenAI API Usage
* Prompt Engineering
* State-based AI Systems

---

# Project Structure

```text
customer-support-ai-agent/
│
├── customer_support_agent_langgraph.ipynb
├── .env
├── requirements.txt
└── README.md
```

---

# Author

Dhasaradh

---

# License

This project is for educational and learning purposes.
