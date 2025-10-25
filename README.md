AI Email Assistant with Telegram Approval 🚀

An intelligent Gmail automation system that uses OpenAI GPT to:

✅ Read & summarize incoming emails
✅ Draft professional replies automatically
✅ Send a preview to Telegram for human approval
✅ On approval → Gmail sends the reply automatically

Built using n8n, Gmail API, Telegram Bot API, and OpenAI GPT.

✅ How It Works
Step	Description
1️⃣ Gmail Trigger	Detects a new email in your inbox
2️⃣ GPT Summary	AI writes a concise summary of the email
3️⃣ Draft Creation	GPT drafts a professional reply
4️⃣ Telegram Alert	Summary + draft sent via Telegram with buttons ✅❌
5️⃣ Human Decision	Approve or Reject directly on Telegram
6️⃣ Auto-Reply	Approved messages are finalized by GPT and emailed

This combines automation + human judgment = safer & smarter AI ⚡

🧠 Architecture
Gmail ➜ GPT Summary & Draft ➜ Draft in Gmail ➜ Telegram Approval ➜ GPT Final Reply ➜ Gmail Sends Email


📌 Full diagram ↓

📸 Screenshots
🔹 Full Automation Workflow in n8n

🔹 Telegram Approval Message

🔹 AI-Generated Reply Sent Automatically

🛠️ Tech Used
Tool	Purpose
n8n	Workflow automation
OpenAI GPT	AI summarization + email drafting
Gmail API	Email access and sending
Telegram Bot API	Human-in-the-loop approval
JavaScript Expressions	Dynamic message handling
📦 Installation & Setup

To import workflow:

1️⃣ Clone this repo
2️⃣ Open n8n
3️⃣ Import workflow_redacted.json
4️⃣ Add your own credentials:

Gmail OAuth2

Telegram Bot Token

OpenAI API Key

5️⃣ Update:

Chat ID

Bot username

Your name in reply closing

Then activate & enjoy 🤖📨

✅ Use Cases

✔ Busy professionals
✔ Freelancers handling client messages
✔ Support teams automating replies
✔ Lead follow-ups with human oversight
✔ Smart inbox filtering

🔒 Security

No API keys or private data are included in this export ✅
Users must configure their own credentials inside n8n.

🧑‍💻 Author

👤 Yash Chaudhary
AI Automation Developer & Workflow Engineer
📍 India

“Building intelligent systems that work for you.” ⚡

⭐ Support

If you like this project…
✅ Star the repo
✅ Share on LinkedIn
✅ Connect for freelance automation projects!
