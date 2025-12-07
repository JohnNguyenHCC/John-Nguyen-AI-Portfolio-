SpendCents – AI-Powered Spending Advisor

SpendCents is a lightweight AI financial advisor that helps users make smarter day-to-day spending decisions. The app combines rule-based reasoning with an LLM to give personalized, vibe-adjusted purchase recommendations based on the user’s spending activity.

This project was built as part of my AI coursework and demonstrates practical AI agent design using client-side technologies and a secure LLM proxy.

🚀 Features
• “Can I Buy This?” AI Advisor

Enter an item and price, and the agent evaluates whether the purchase fits your daily discretionary budget.
The response blends:

Today’s spending

Your income and essentials (if set)

A budget model

Your “vibe” (Balanced or Thrifty)

AI-generated coaching from an LLM

• Add Purchases

Log spending quickly and track your daily totals.

• Purchase History

View all previously logged purchases (stored locally).

• Daily Spending Summary

Shows how much you’ve spent today and gives helpful feedback.

• Vibe Toggle

Switch between Balanced and Thrifty styles to adjust tone and recommendation strictness.

🧠 How the AI Agent Works

SpendCents uses a simple agent loop:

Collect user context
Item name, price, today’s spending, income/essentials (if set), and vibe.

Compute a Baseline Judgment
Using:

Daily discretionary budget estimate

Today’s spending

Small-purchase exceptions

Rule-based thresholds

AI Reasoning (LLM)
A Cloudflare Worker securely forwards a structured prompt to OpenAI.
The LLM returns a concise recommendation that never contradicts the baseline.

Return advice
The app shows both the baseline and the AI’s suggestion.

🛠️ Tech Stack
Frontend

HTML

CSS

JavaScript

LocalStorage (state)

AI Backend

Cloudflare Workers

OpenAI GPT-4o-mini

Worker secrets for API key security

CORS-safe POST endpoint

This architecture keeps API keys private while supporting live AI inference.

📦 Project Structure
SpendCents-Agent/
│
├── index.html         # Main app
└── README.md          # Project description

🔗 Live Demo

Add your hosted link here:

Live App:
[https://your-netlify-site.netlify.app](https://spendcents2.netlify.app/)

⚡ Running Locally

Clone or download this folder

Open index.html in a browser

Add your Worker URL inside the script:

const WORKER_URL = "https://your-worker-url.workers.dev";


AI features require:

A Cloudflare Worker

OpenAI API key stored as a Worker secret

📘 License

For educational and portfolio use.
