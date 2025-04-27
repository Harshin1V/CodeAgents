# 🧠 Code Agents with Hugging Face smolagents

**Research Reference:** [Executable Code Actions Elicit Better LLM Agents](/https://arxiv.org/abs/2402.01030)

This repository explores the evolution of AI agents, demonstrating how they can autonomously perform tasks by leveraging Hugging Face's smolagents. The project progresses through various stages of agent development, from basic conversational agents to advanced memory-based systems.

---

## 📁 Repository Structure & File Summaries

### 1. `Code Agents.ipynb`
- **Purpose:** Demonstrates the implementation of basic code agents using Hugging Face's smolagents.
- **Highlights:**
  - **Introduction to smolagents:** Guides users through setting up and utilizing smolagents for code generation tasks.
  - **Examples:** Provides practical examples of code agents in action, showcasing their capabilities.

### 2. `Secure Code Execution.ipynb`
- **Purpose:** Addresses the security aspects of executing code within agents.
- **Highlights:**
  - **Sandboxing:** Demonstrates methods to safely execute code within isolated environments.
  - **Security Best Practices:** Provides guidelines to ensure secure code execution.


### 3. `Monitoring and Evaluating your Agent.ipynb`
- **Purpose:** Focuses on the assessment and monitoring of agent performance.
- **Highlights:**
  - **Evaluation Metrics:** Introduces metrics to evaluate agent effectiveness and efficiency.
  - **Monitoring Tools:** Discusses tools and techniques for tracking agent performance over time.




### 4. `Deep Research-like agent.ipynb`
- **Purpose:** Explores the development of agents capable of performing deep research tasks.
- **Highlights:**
  - **Advanced Agent Design:** Discusses the architecture and design principles behind research-oriented agents.
  - **Use Cases:** Illustrates how these agents can autonomously gather and analyze information.
 
### 5. `helper.py`
- **Purpose:** Contains utility functions to assist in agent development and operation.
- **Highlights:**
  - **Helper Functions:** Includes functions for common tasks such as logging, error handling, and data processing.
  - **Modular Design:** Designed to be easily integrated into various agent workflows.

# 🌟 Evolution of AI Agents

- **Conversable Agents** → Basic chatting (LLM responds to prompts).
- **Tool-Calling Agents** → LLMs can invoke external tools/functions.
- **Router Agents** → Directs tasks to specialized agents/tools.
- **Multi-Step Reasoning Agents** → Plans sequences of actions (reasoning chains).
- **Web Agents** → Navigate and interact with websites autonomously.
- **MCTS Planning Agents (Agent Q)** → Simulates multiple action paths, picks optimal.
- **Self-Critiquing Agents** → Evaluates own actions before executing.
- **Feedback-Learning Agents** → Improves by learning from feedback (success/failure).
- **Memory Agents** → Stores and uses long-term memory for smarter actions.
- **Self-Improving Agents** → Continuously fine-tunes and evolves without manual retraining.

---

> **Talk → Use tools → Route → Plan → Act → Simulate → Critique → Learn → Remember → Evolve** 🚀
