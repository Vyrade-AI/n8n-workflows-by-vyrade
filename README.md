
# 🚀 Vyrade's n8n Workflow Library

Welcome to the official **n8n automation workflow repository** by [Vyrade](https://www.vyrade.ai), curated by [Fahad Ali](https://github.com/vyradeai).  
This repository contains over **2,000 real-world n8n workflows** used in production to automate business operations, AI content pipelines, marketing, approvals, and data flows — without writing code.

---

## 📁 Repository Structure

```
n8n-workflows/
├── workflows/           # All exported n8n .json workflow files (2055+)
├── README.md            # This file
├── LICENSE              # Open-source license (MIT or your choice)
└── .gitignore
```

Each `.json` file in the `workflows/` folder is a complete n8n workflow you can import into your instance.

---

## 🚀 Getting Started

### 1️⃣ Clone This Repository

```bash
git clone https://github.com/vyrade/n8n-workflows.git
cd n8n-workflows
```

### 2️⃣ Import a Workflow into n8n

1. Open your [n8n editor](https://n8n.io)
2. Click the **Import** button in the top-right
3. Upload any `.json` file from the `workflows/` directory
4. Set up any credentials or environment variables if prompted
5. Save and run your new automation 🎉

---

## 🧠 What’s Inside?

This repository includes 2,000+ real n8n workflows used by the Vyrade team for:

| 🔧 Automation Type        | 💡 Description                                                                |
|--------------------------|-------------------------------------------------------------------------------|
| 🧠 AI Content Workflows   | Generate, approve, and auto-post content using OpenAI & Buffer                |
| 📊 Data Sync & Reporting  | Auto-sync Google Sheets, Notion, Airtable, CRMs, and analytics tools          |
| 🔁 Approval Flows         | Manual and scheduled workflows for content review, publishing, or actions     |
| 📡 API Integrations       | Webhook-driven tasks, REST API chaining, JSON processing, and retries         |
| 📂 File Management        | Upload, download, rename, tag, and email attachments via Drive/Dropbox/etc.   |
| 🤖 Chatbot & AI Tasks     | Use LLMs like ChatGPT for summaries, sentiment, classification, etc.          |
| ⏱ Scheduler Automations  | Triggered via time, events, conditions, or approvals                          |

These workflows are used to run multiple LinkedIn pages, content systems, and internal tools — now shared openly for inspiration and reuse.

---

To run them:
- Set environment variables in your n8n instance
- Or manually replace with your own keys (not recommended for production)

> Always secure your secrets using n8n’s built-in **credential manager**.

---

## 📦 File Naming Convention

To keep the workflows organized:
- Each file follows this format: `0001-workflow-name.json`
- Numbers help with ordering and future indexing
- Use lowercase and hyphens for workflow titles

---

## 📬 Contributing

We welcome pull requests! 🚀

To contribute:
1. Fork the repo
2. Add your `.json` file to `/workflows/`
3. Follow the naming format `XXXX-title.json`
4. Optionally include a `_comment` inside the JSON to explain its use
5. Submit a pull request

Example:

```json
"_comment": "Auto-generate LinkedIn post from approved content"
```

---

## 📄 License

You are free to use, modify, and redistribute the workflows with or without credit — though attribution is appreciated!

---

## 📣 Contact

For questions, enterprise usage, or collaboration:

- 👨‍💼 **Founder**: [Fahad Ali](https://github.com/vyradeai)
- 🧠 **Platform**: [vyrade.ai](https://www.vyrade.ai)

---

> 🚀 Let’s automate the future — one workflow at a time.
