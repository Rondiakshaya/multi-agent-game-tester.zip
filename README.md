# Multi-Agent Game Tester POC

This project is a **Proof of Concept (POC)** for a multi-agent game tester of a number/math puzzle web game  
(target game: [https://play.ezygamers.com/](https://play.ezygamers.com/)).

It demonstrates how **LangChain agents** can generate, rank, execute, and analyze automated test cases.  
The backend is built with **FastAPI**, and the frontend is a simple HTML/JS UI.

---

## 🚀 Features
- ✅ **PlannerAgent** – generates 20+ candidate test cases
- ✅ **RankerAgent** – selects top 10 test cases
- ✅ **ExecutorAgents** – simulate test execution
- ✅ **OrchestratorAgent** – coordinates execution
- ✅ **AnalyzerAgent** – validates results (repeat & cross-agent checks)
- ✅ **Artifacts** – mock screenshots, logs
- ✅ **Reports** – JSON summary with pass/fail stats

---

## 📂 Project Structure


