**Ornith 1.0 is a new open‑source AI coding model (released June 2026) that doesn’t just learn to write code — it learns how to design its own coding workflow. This “self‑scaffolding” approach makes it capable of evolving problem‑solving strategies automatically, rivaling proprietary frontier models while remaining free and open.**

---

## 🧠 What Ornith 1.0 Is
- **Ornith 1.0** is a family of reinforcement‑learning based **Large Language Models (LLMs)** optimized for coding tasks.  
- Built on **Gemma 4** and **Qwen 3.5** foundations.  
- Comes in multiple sizes: from **9B lightweight models** (edge‑deployable) to a massive **397B Mixture‑of‑Experts (MoE)** model.  
- Fully **open source** and available on Hugging Face.

---

## 🔑 Core Innovation: Self‑Scaffolding
Traditional coding AIs follow a fixed pipeline: *Task → Generate Code → Run Tests → Retry → Answer*.  
- Ornith changes this by **learning to design its own pipeline**.  
- It decides:
  - How many reasoning steps to take  
  - When to call tools  
  - How to organize memory  
  - When to retry or debug  
- The **workflow itself becomes trainable**, not just the code output.

---

## ⚙️ How It Works
1. **Stage 1 – Generate Scaffold**  
   - Ornith first creates a strategy: reasoning order, tool usage, debugging plan, retry policy.  
2. **Stage 2 – Solve Task**  
   - Using that scaffold, it executes: reading repos, editing code, running tests, fixing bugs.  
3. **Reinforcement Learning Feedback**  
   - Rewards update both the *solution* and the *scaffold*.  
   - Ineffective workflows fade, efficient ones survive.  
   - Over time, Ornith evolves better workflows automatically.

---

## 📊 Why It Matters
- **Automation of agent design**: Removes need for human engineers to handcraft retry logic, memory systems, or tool pipelines.  
- **Adaptability**: Learns different workflows for different categories of software engineering tasks.  
- **Performance**: Benchmarks show Ornith matches or exceeds proprietary coding agents.  
- **Scalability**: Works across small devices (9B) and enterprise‑grade systems (397B MoE).  

---

## 📌 Takeaway
**Ornith 1.0 is not just a coding AI — it’s a self‑learning coding *engineer*. By teaching itself how to structure workflows, it evolves into a more autonomous agent, making open‑source coding models competitive with frontier proprietary systems.**

---
