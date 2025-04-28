---

# 📚 Effective AI Agents - Assignment 7

This repository demonstrates the implementation of agent design patterns using **LangGraph** and **CrewAI** frameworks, inspired by the principles taught in the "Building Effective Agents" course.

The assignment showcases three essential agent design patterns — implemented both using **LangGraph API** and **CrewAI** — along with LangSmith tracing and a complete video walkthrough.

---

## 🛠️ Patterns Implemented

| # | Pattern | LangGraph Colab | CrewAI Colab |
|:-|:---|:---|:---|
| 1 | Simple Tool-Using Agent | [1_tool_using_agent_langgraph.ipynb](colabs/1_tool_using_agent_langgraph.ipynb) | [2_tool_using_agent_crewai.ipynb](colabs/2_tool_using_agent_crewai.ipynb) |
| 2 | Sequential Workflow Agent | [3_sequential_workflow_langgraph.ipynb](colabs/3_sequential_workflow_langgraph.ipynb) | [4_sequential_workflow_crewai.ipynb](colabs/4_sequential_workflow_crewai.ipynb) |
| 3 | Multi-Agent Collaboration | [5_multi_agent_collab_langgraph.ipynb](colabs/5_multi_agent_collab_langgraph.ipynb) | [6_multi_agent_collab_crewai.ipynb](colabs/6_multi_agent_collab_crewai.ipynb) |

Each pattern demonstrates:
- 🧠 Agent architecture
- ⚡ Tool usage
- 🔀 Workflow design
- 🔍 Debugging and tracing with LangSmith

---

## 🎥 Full Walkthrough Video

📺 **Watch the complete working demo and debug trace recording here:**  
👉 [YouTube Video Walkthrough Link](https://youtube.com/your-uploaded-video-link)

- Demonstrates agent runs
- Shows LangSmith trace for each pattern
- Explains design decisions

*(Video uploaded as Unlisted for assignment submission.)*

---

## 🔍 LangSmith Debug Traces

Each agent execution has been traced and monitored using **LangSmith Studio** for deeper visibility:

| Pattern | Trace Link |
|:---|:---|
| Tool-Using Agent | [LangSmith Trace](https://smith.langchain.com/projects/your-tool-using-trace) |
| Sequential Workflow Agent | [LangSmith Trace](https://smith.langchain.com/projects/your-sequential-workflow-trace) |
| Multi-Agent Collaboration | [LangSmith Trace](https://smith.langchain.com/projects/your-multi-agent-collab-trace) |

Traces include:
- Tool usage steps
- Model reasoning
- Error handling (if any)

---

## 📂 Repository Structure

```bash
effective-ai-agents-patterns/
│
├── colabs/
│   ├── 1_tool_using_agent_langgraph.ipynb
│   ├── 2_tool_using_agent_crewai.ipynb
│   ├── 3_sequential_workflow_langgraph.ipynb
│   ├── 4_sequential_workflow_crewai.ipynb
│   ├── 5_multi_agent_collab_langgraph.ipynb
│   └── 6_multi_agent_collab_crewai.ipynb
│
├── videos/
│   └── assignment7_walkthrough.mp4
│
├── readme_files/  # Optional (screenshots, sample outputs)
│
└── README.md
```

---

## 🛠️ How to Reproduce (Optional for Viewers)

If you want to run the notebooks yourself:

```bash
# Install necessary libraries
pip install langgraph langchain openai crewai langsmith

# Set your API keys in environment variables
export LANGCHAIN_API_KEY=your-key
export HUGGINGFACEHUB_API_TOKEN=your-token
```

Or simply run the provided Google Colabs.

---

## 📑 References

- [LangGraph Tutorials](https://langchain-ai.github.io/langgraph/tutorials/workflows)
- [CrewAI Documentation](https://docs.crewai.com/)
- [Building Effective Agents - YouTube](https://www.youtube.com/watch?v=aHCDrAbH_go)
- [DeepLearning.AI LangGraph Short Course](https://www.deeplearning.ai/short-courses/ai-agents-in-langgraph/)
- [LangSmith Studio](https://smith.langchain.com/)

---

# 📈 Highlights
- Used **LangGraph StateGraph** and **CrewAI Roles** for pattern modeling
- Integrated **LangSmith** for complete agent tracing and debugging
- Designed lightweight tools and workflows for clarity
- Recorded a full video walkthrough with both execution and trace explanation

---

# 🚀 Submission Info

**Submitted GitHub URL:** [https://github.com/your-repo-link](https://github.com/your-repo-link)

---
