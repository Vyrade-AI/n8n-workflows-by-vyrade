# ⚙️ Vyrade's n8n Workflow Library

Welcome to the official **n8n automation workflow repository** by [Vyrade](https://vyrade.ai), curated by [Fahad Ali](https://github.com/fahad-ali).  
This repository contains **2,055+ production-ready workflows** built using [n8n](https://n8n.io) to automate tasks across AI, content, operations, marketing, and more.

---

## 📁 Repository Structure

n8n-workflows/
├── workflows/ # All exported .json workflow files
├── tools/ # Optional scripts (rename, readme generation)
├── README.md # This file
├── LICENSE # Open-source license (MIT recommended)
└── .gitignore # Ignore rules

yaml
Copy
Edit

Each `.json` file in `/workflows/` is a direct export from the n8n editor and ready to use.

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/vyrade/n8n-workflows.git
cd n8n-workflows
2️⃣ Import Workflows into n8n
Open your n8n instance

Click the Import button in the top-right corner

Upload any .json file from the /workflows/ directory

Configure any required credentials

Save and run the workflow 🚀

🧠 What's Inside
This library includes automations across multiple domains:

Category	Example Use Cases
🔁 Content Automation	Auto-generate posts, approvals, LinkedIn publishing via Buffer
🤖 AI Workflows	Use OpenAI, Claude, or LLMs to summarize, rewrite, or generate text
📊 Reports & Syncing	Google Sheets updates, Notion sync, Airtable reports
📡 API & Webhook Logic	Real-time triggers, CRM/API requests, error handling logic
🧩 Systems Integration	Slack, Google Drive, databases, CRMs, productivity tools

These workflows represent real-world automation built in production and refined over time.

🔐 Environment Variables & Credentials
Some workflows use environment variables like:

json
Copy
Edit
"Authorization": "Bearer {{$env.OPENAI_API_KEY}}"
To make these workflows functional:

Set environment variables in your .env or through n8n Credential Manager

Replace with hardcoded values (not recommended for production)

🛠 Optional Utility Tools (in /tools/)
We’ve added optional scripts you can use to manage the workflows:

bulk-rename.py – Rename all workflows consistently like 0001-title.json

readme-generator.js – Automatically build an index of all workflows in markdown

validate-json.py – (optional) Check workflow syntax before import

These are useful for bulk updates or automating documentation.

📌 Best Practices
✅ Keep credentials out of exports

✅ Use descriptive, clear workflow names

✅ Always test before going live

✅ Version your critical workflows using Git

🙌 Contributing
Want to submit a workflow?

Fork the repo

Add your .json to the /workflows/ folder

Use a file name like: 2056-auto-email-followup.json

Add a short comment in the JSON file like:

json
Copy
Edit
"_comment": "Sends a follow-up email via Gmail after lead form submission"
Submit a pull request 🚀

📬 Contact
Have questions, feedback, or ideas?

Founder: Fahad Ali

Platform: vyrade.ai

Email: fahad [at] vyrade.ai

🧾 License
This repository is licensed under the MIT License.
Feel free to use, share, or modify these workflows for personal or commercial use.