🧾 AI Agents
This repo is just for my own practice and experiments with n8n workflows.
I’m using it to try out automations, agents, and AI tools — nothing too serious, just learning and building.

🤖 Workflow No. 1 – Chatbot from Google Drive Files
Workflow 1 does a simple but cool job:

Whenever I add a new file to a specific Google Drive folder,

It gets the file’s content and sends it to Pinecone (a vector database)

Uses OpenAI embeddings to understand the content

Then powers a chatbot that can answer questions about that document

It’s like turning my Google Drive files into something I can actually talk to.

🛟 Workflow No. 2 – Auto-Reply for Customer Policy Emails
Workflow 2 is a lightweight customer support agent:

Every minute, it checks for new incoming emails

If it detects that an email is asking about a customer policy,

It queries a stored policy document (embedded in Pinecone)

Then drafts and sends a smart, helpful reply using AI — based on the actual content of the policy

It’s basically a mini AI assistant that reads the manual so I don’t have to.

📥 Workflow No. 3 – Invoice Intake and Notification System
Workflow 3 automates invoice handling from Google Drive:

It watches a Google Drive folder for new uploads

When a new invoice file is added, it:

Extracts key details like invoice number, client name, email, address, phone, total amount, invoice date, and due date

Updates a Google Sheet with all the extracted information

Sends an internal email to notify the billing team that an invoice has been received

Simple setup, but really helps keep things organized and cuts out the manual work.

More agents and experiments coming soon (hopefully).

