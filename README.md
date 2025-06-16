# 🧠 Submind

Submind is a local, multi-agent AI assistant that autonomously thinks, plans, and generates actionable output (code, writing, insights) overnight — all based on your personal goals. It’s like having a second brain that works while you sleep.

---

## 🚀 Why Submind?

Traditional productivity tools remind you to work — Submind **does the work for you**.

By assigning personal objectives like "refactor my codebase," "write blog drafts," or "generate business ideas," Submind uses AI agents to simulate a full night of progress and deliver tangible results by morning.

---

## 🔍 Use Cases

- Generate code for side projects overnight  
- Draft blog posts, tweets, or newsletters  
- Conduct market research or idea validation  
- Refactor and document codebases  
- Brainstorm startup or app concepts  
- Write outlines, study notes, or summaries  

---

## 🧩 How It Works

### 🧠 Multi-Agent System
Submind spins up multiple autonomous agents that collaborate toward a goal using a shared memory space and dynamic task prioritization.

### 🕰️ Overnight Scheduler
Tasks are queued and executed between defined "night" hours. Results are ready in your `/reports` folder each morning.

### 💬 LLM-Powered Reasoning
Each agent uses an LLM (OpenAI, local models like Ollama, etc.) to process instructions, read context, and communicate with other agents.

### 📁 Local First
All data stays on your machine. No cloud sync. No leaks. You own your brain.

---

## ⚙️ Tech Stack

- `Python` (agent orchestration, file I/O)
- `Langchain` or `CrewAI` (agent framework)
- `Ollama` or `OpenAI API` (LLM interface)
- `cron` or `APScheduler` (overnight job scheduling)
- `Markdown` / `HTML` (report formatting)
- `SQLite` or `JSON` (persistent memory store)

---

## 🛠️ Getting Started

### 1. Clone the Repo

```bash
git clone https://github.com/yourusername/submind.git
cd submind
````

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Configure Your `.env`

```env
OPENAI_API_KEY=your-key-here
USE_LOCAL_MODELS=true
MODEL_NAME=llama3
```

### 4. Define Your Goals

Edit your goals file:

```json
{
  "goal_1": "Create a blog post about multi-agent AI systems",
  "goal_2": "Generate TypeScript utilities for data validation"
}
```

### 5. Run Submind

```bash
python run_submind.py
```

Submind will run during your defined "overnight" hours and generate a daily summary in `/reports`.

---

## 🧪 Example Output

* `/reports/2025-06-16.md`
* `/code_generated/blog-outline.tsx`
* `/logs/submind.log`

---

## 📦 Roadmap

* [ ] Web dashboard for reviewing progress
* [ ] Support voice-based goal input
* [ ] Auto-push to GitHub
* [ ] Plugin system for goal types (e.g. “generate API spec”)

---

## 🧠 Inspiration

Inspired by the idea of leveraging idle time to achieve compounding progress using autonomous, intelligent agents.

---


---

Would you like me to generate a `requirements.txt`, `.env` sample, or skeleton Python files next?
```
