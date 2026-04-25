# 🧠 Agentic LLM System

A multi-agent LLM system that dynamically selects tools and reasoning paths to solve user queries across multiple domains.

---

## 🚀 What This Project Does

This system goes beyond a simple chatbot by using an **agent-based architecture** that can:

* 🔍 Retrieve external information
* 🧮 Perform computations
* 🌐 Query multiple sources
* 🧠 Decide *how* to solve a problem before answering

Unlike traditional chatbots, this model **reasons + acts**, not just responds.

---

## 🏗️ Architecture

```
User Query
   ↓
Agent Planner (decides strategy)
   ↓
Tool Selection Layer
   ↓
Execution (API / Retrieval / Computation)
   ↓
Response Synthesis
   ↓
Final Answer
```

---

## 🛠️ Tools Integrated

* Web / knowledge retrieval
* Calculator / logic tools
* LLM reasoning chain
* Custom agent routing logic

---

## ⚙️ Tech Stack

* Python
* LangChain (Agents + Tools)
* FAISS / Retrieval (if used)
* Groq / OpenAI API
* FastAPI / CLI (if applicable)

---

## 💡 Key Idea

Instead of:

> Input → LLM → Output

This system does:

> Input → Plan → Choose Tools → Execute → Think → Answer

This is closer to **how real AI systems (like AutoGPT-style agents) operate**.

---

## 📊 Example

**Input:**

```
What is the GDP growth of India and how does it compare to last year?
```

**Process:**

* Agent decides → needs retrieval
* Calls tool → fetch data
* Compares values
* Generates answer

**Output:**

```
India’s GDP grew X%, which is higher/lower than last year by Y%.
```

---

## 🧪 How to Run

```bash
git clone https://github.com/Srik-007/chatbot-with-agents-and-tools
cd chatbot-with-agents-and-tools
pip install -r requirements.txt
python main.py
```

---

## 🔥 Why This Matters

Agent-based systems are the next evolution of LLM applications.

They are used in:

* autonomous assistants
* financial analysis systems
* enterprise copilots

This project demonstrates **core building blocks of real-world AI systems**.

---

## 📌 Future Improvements

* Memory (long-term context)
* Multi-agent collaboration
* Tool learning / auto-selection
* Streaming responses

---

## 👤 Author

Built by [Srik-007](https://github.com/Srik-007)
