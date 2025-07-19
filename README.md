# AI\_Projects\_By\_Abishek

Welcome to **AI\_Projects\_By\_Abishek** — a modular, extensible toolkit designed to simplify and enhance research paper analysis using state-of-the-art Large Language Models (LLMs). This project empowers researchers, students, and developers with intelligent agents that can summarize academic literature and extract meaningful insights, all with minimal setup.

---

## 🚀 Key Features

* **Research Agent Framework**
  Instantiate intelligent agents capable of performing detailed analysis of academic papers.

* **Summarization Agent**
  Extracts concise and relevant summaries from long-form research papers, preserving technical depth.

* **Advantages & Disadvantages Agent**
  Automatically identifies and presents the pros and cons of each paper in a clear, pointwise format.

* **Seamless LLM Integration**
  Built using powerful tools like LangChain, Autogen, and Groq for fast and accurate language processing.

* **Secure Configuration Management**
  Uses `python-dotenv` for managing API keys and environment-specific variables securely.

---

## 🧰 Tech Stack

* **Python** — Primary programming language
* **LangChain & LangChain Community** — For LLM orchestration
* **Autogen** — Framework for building autonomous AI agents
* **GROQ** — High-performance LLM API integration
* **Transformers** — Model utilities and tokenization
* **Streamlit** — Interactive web app development
* **Scholarly** — Academic article search and retrieval
* **python-dotenv** — Secure environment variable handling

---

## 📦 Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/abishekP101/AI_Projects_By_Abishek.git
   cd AI_Projects_By_Abishek
   ```

2. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Configure Environment Variables**

   * Create a `.env` file in the root directory.
   * Add your API keys:

     ```dotenv
     GROQ_API_KEY=your_groq_api_key_here
     ```

---

## 🧑‍💻 Getting Started

The core logic resides in the `ResearchAgents` class (`agents.py`). Instantiate it with your API key to access all the available tools:

```python
from agents import ResearchAgents

# Initialize agents
agents = ResearchAgents(api_key="your_groq_api_key")

# Summarize a research paper
summary = agents.summarize_paper("Full text of the research paper here")

# Analyze the paper's advantages and disadvantages
adv_dis = agents.analyze_advantages_disadvantages(summary)
```

You can also build interactive interfaces (e.g., Streamlit apps) on top of this backend.

---

## 📄 Requirements (`requirements.txt`)

```
langchain-community
langchain-core
streamlit
langchain
python-dotenv
langchain_groq
transformers
scholarly
autogen
```

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 👨‍💻 Author

Developed with ❤️ by [Abishek P](https://github.com/abishekP101)

---

## ⭐️ Support the Project

If you find this project useful, please consider starring ⭐ and watching 👀 the repository to stay updated!

👉 [Visit on GitHub](https://github.com/abishekP101/AI_Projects_By_Abishek)

---
