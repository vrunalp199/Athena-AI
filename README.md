# 🛡️ Anthena AI

Anthena AI is an AI-powered cybersecurity assistant designed to provide intelligent security analysis, log inspection, report generation, code assistance, and future large-scale cybersecurity knowledge retrieval using Retrieval-Augmented Generation (RAG).

---

## 🚀 Current Features

- AI Chat Interface
- Memory Management
- Log Analysis
- Code Generation
- File Management
- Report Generation
- SQLite Memory Storage
- Flask Web Interface

---

## 📂 Project Structure

```text
Anthena AI/
│
├── ai/
│   ├── llm.py
│   ├── memory.py
│   └── system_prompt.txt
│
├── database/
│   └── memory.db
│
├── templates/
│   └── index.html
│
├── tools/
│   ├── code_generator.py
│   ├── file_manager.py
│   ├── log_analyzer.py
│   └── report_generator.py
│
├── workspace/
│   ├── code/
│   ├── logs/
│   └── reports/
│
├── app.py
├── dataset.py
├── requirements.txt
└── README.md
```

---

## 🛠 Technologies Used

### Backend
- Python
- Flask

### AI Components
- Local LLM Integration
- Memory System
- Prompt Engineering

### Database
- SQLite

### Future Components
- Qwen3.6-27B
- QLoRA Fine-Tuning
- Qdrant Vector Database
- RAG Pipeline
- Cybersecurity Knowledge Base

---

## ⚙ Installation

Clone repository:

```bash
git clone https://github.com/YOUR_USERNAME/Anthena-AI.git
cd Anthena-AI
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run application:

```bash
python app.py
```

Open:

http://127.0.0.1:5000

---

## 🧠 Future Roadmap

### Phase 1
- Improve chatbot capabilities
- Better memory handling
- Enhanced cybersecurity prompts

### Phase 2
- Integrate Qwen3.6-27B
- QLoRA fine-tuning
- Cybersecurity instruction training

### Phase 3
- Retrieval-Augmented Generation (RAG)
- Qdrant integration
- Large-scale cybersecurity knowledge retrieval

### Phase 4
- Multi-agent cybersecurity architecture
- Threat intelligence analysis
- CVE search and exploitation guidance
- Security report automation

---

## 🔬 Planned AI Architecture

```text
User Query
     │
     ▼
 Anthena AI
     │
     ▼
Qwen3.6-27B
     │
     ▼
Cybersecurity LoRA
     │
     ▼
Qdrant Vector Database
     │
     ▼
95GB Cybersecurity Knowledge Base
     │
     ▼
RAG Retrieval Layer
     │
     ▼
Final Response
```

---

## 📚 Planned RAG Configuration

Embedding Model:

- BAAI/bge-large-en-v1.5
- nomic-embed-text

Recommended Settings:

```text
Chunk Size : 1000 Tokens
Overlap    : 150 Tokens
Top-K      : 5-10 Results
Database   : Qdrant
```

---

## 🎯 Project Goal

The goal of Anthena AI is to create a cybersecurity-focused AI assistant capable of:

- Threat Analysis
- Security Research
- Log Investigation
- Vulnerability Intelligence
- Malware Analysis Support
- Incident Response Assistance
- Knowledge Retrieval from Large Cybersecurity Datasets

---

## ⚠ Disclaimer

This project is intended for educational, research, and authorized security testing purposes only.

Users are responsible for ensuring compliance with all applicable laws and regulations.

---

## 📄 License

MIT License

---

## 👨‍💻 Author

Vrunal

Computer Science Student | Cybersecurity Enthusiast | AI Developer
