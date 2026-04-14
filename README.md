# 📊 Market Research Crew

An AI-powered **multi-agent market research system** built using the CrewAI framework.
This project leverages collaborative AI agents to perform in-depth research, analyze trends, and generate structured reports.

---

## 🚀 Features

* 🤖 **Multi-Agent System**
  Multiple AI agents working together with defined roles

* 📊 **Automated Market Research**
  Generates insights and reports on selected topics

* 🧠 **Customizable Agents & Tasks**
  Easily configure agents and workflows using YAML

* 📄 **Report Generation**
  Outputs structured research results (`report.md`)

* ⚡ **Powered by CrewAI**
  Efficient orchestration of AI agents

---

## 🧠 Tech Stack

* **Language:** Python
* **Framework:** CrewAI
* **Dependency Management:** UV
* **LLM Support:** OpenAI

---

## 📂 Project Structure

```
market_research_crew/
│── src/
│   └── market_research_crew/
│       ├── config/
│       │   ├── agents.yaml
│       │   ├── tasks.yaml
│       ├── crew.py
│       ├── main.py
│── .env
│── README.md
```

---

## ⚙️ Installation

Make sure you have **Python 3.10 – 3.13** installed.

### 1️⃣ Install UV

```bash
pip install uv
```

### 2️⃣ Install Dependencies

```bash
crewai install
```

---

## 🔐 Environment Setup

Create a `.env` file in the root directory:

```bash
OPENAI_API_KEY=your_openai_api_key_here
SERPER_API_KEY=your_serper_api_key_here
MODEL=your_model_name_here
```

---

## ▶️ Running the Project

Run the following command:

```bash
crewai run
```

👉 This will:

* Initialize AI agents
* Execute defined tasks
* Generate a `report.md` file with research output

---

## 🛠️ Customization

You can easily customize the system:

* ✏️ `config/agents.yaml` → Define agent roles and behavior
* 🧩 `config/tasks.yaml` → Define research tasks
* ⚙️ `crew.py` → Add tools and logic
* 🧠 `main.py` → Customize inputs and execution

---

## 📈 Example Use Cases

* Market trend analysis
* Competitor research
* Industry insights generation
* AI-powered report creation

---

## 🔗 Project Link

GitHub Repository:
https://github.com/namrakoyani123/Market_Research_Crew

---

## 👩‍💻 Author

**Namra Koyani**
B.Tech Student | Developer | AI Enthusiast

🔗 GitHub: https://github.com/namrakoyani123

---

## 📜 License

This project is licensed under the MIT License.

---

⭐ If you found this project useful, consider giving it a star!
