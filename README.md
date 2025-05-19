# Assignment 7: Effective AI Agents using LangGraph and CrewAI

## 📚 Overview

This project demonstrates multiple **effective AI agent design patterns** using **LangGraph** and **CrewAI** frameworks.  
It covers three major patterns:
- Tool-Using Agents
- Sequential Workflow Agents
- Branching Router Agents

Both frameworks are used to implement each pattern separately, using **free models** hosted on Hugging Face and Together AI.

All code is executed and demonstrated in Google Colab notebooks.

---

## ⚙️ Frameworks and Models Used

| Framework | Purpose | Model Used |
|:---|:---|:---|
| LangGraph | Build flexible agent workflows | HuggingFaceHub (small free models) |
| CrewAI | Organize agents into structured teams and tasks | Together AI free model (`arcee-ai/arcee-blitz`) |

- No OpenAI API keys are needed.
- Only free-tier Hugging Face and Together services are used.

---

## 🛠 Setup Instructions (Colab)

No installation needed locally.  
Each Colab automatically installs required packages:
- `langgraph`
- `langchain-core`
- `langchain-community`
- `crewai`
- `together`
- Other minimal dependencies as needed.

**Authentication:**  
- HuggingFace free API key for Hugging Face models
- Together AI free API key for Together models

---

## 🛤️ Project Structure and Links

Each Colab demonstrates a specific pattern with a different framework:

| Pattern | Framework | Notebook Link |
|:---|:---|:---|
| Tool-Using Agent | LangGraph | [Colab 1](https://colab.research.google.com/drive/16bn0w9c8-kzW1GkrmKqmcUx6iKBVCB4a?usp=sharing) |
| Tool-Using Agent | CrewAI | [Colab 2](https://colab.research.google.com/drive/1oH0aFwLfpnWimidkFS-6CCGz0UZq7rbo?usp=sharing) |
| Sequential Workflow Agent | LangGraph | [Colab 3](https://colab.research.google.com/drive/1cxLFmVHHnt7rBmYCLwpwUP-vK4mzFrAW?usp=sharing) |
| Sequential Workflow Agent | CrewAI | [Colab 4](https://colab.research.google.com/drive/1RGPNIQdVxwjT2SbXbMSAQGdJuiyUqevh?usp=sharing) |
| Branching Router Agent | LangGraph | [Colab 5](https://colab.research.google.com/drive/1LZetSxPpdaLBc48nplKrkfMfhgRU-oqR?usp=sharing) |
| Branching Router Agent | CrewAI | [Colab 6](https://colab.research.google.com/drive/11PlxjbVMRttzmmRaADYTN29kt9GrjFs5?usp=sharing) |

---

## 🧠 Patterns Explained

### 1. Tool-Using Agents
Agents that leverage external tools (like simple calculators) to enhance their abilities.

**Highlights:**
- LangGraph version: Built a basic tool-calling workflow.
- CrewAI version: Used free TogetherAI LLM to simulate tool-based tasks.

---

### 2. Sequential Workflow Agents
Agents working in a pipeline where output of one agent is input for the next.

**Highlights:**
- LangGraph version: Modeled sequential flow using nodes.
- CrewAI version: Created multiple agents and tasks in a strict order.

---

### 3. Branching Router Agents
Agents dynamically route tasks based on input content (e.g., numbers vs text).

**Highlights:**
- LangGraph version: Created conditional edge workflows (dynamic branching).
- CrewAI version: Dynamically assigned tasks based on input type.

---

## 🎥 Video Walkthrough

➡️ [Demo](https://drive.google.com/file/d/1mbJjb-JaiZCDFWDhWtO6hyQJhAWGXRS1/view?usp=sharing)

The video will cover:
- Overview of each pattern
- Step-by-step walkthrough of each Colab
- Demo of agent executions and outputs
- Summary of frameworks and models used

---

## 📬 Submission Summary

- 6 Colab notebooks uploaded
- Comprehensive README included
- Full video walkthrough recorded
- Free model usage (no paid APIs)
- Correct execution traces and outputs

---
