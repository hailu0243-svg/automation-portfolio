# Ashenafi Hailu: Automation and Trading-Tools Portfolio

Fintech and trading-automation developer based in Assosa, Ethiopia (UTC+3). I build AI workflows with n8n, Gemini and Telegram, and Python tools for trading research.

**Contact:** hailu0243@gmail.com | +251900871797 | [LinkedIn](https://www.linkedin.com/in/ashenafi-hailu-abdisa-b68419433)

## Projects

| Project | What it does | Stack |
| --- | --- | --- |
| [AI Forex News and Economic Calendar Bot](ai-forex-news-bot/) | Weekday morning market brief and alerts before high-impact economic releases | n8n, Gemini, Telegram, REST |
| [AI Lead Tracker with Follow-Up](ai-lead-tracker/) | Captures leads from a Telegram bot, form and webhook, scores them with AI, logs them and reminds the owner to follow up | n8n, Gemini, Google Sheets, Telegram |
| [AI Clinic Receptionist](ai-clinic-receptionist/) | Turns patient Telegram messages into structured appointment requests for human review; never confirms bookings | n8n, Gemini AI agent, Telegram |
| [Python Trade Journal](python-trade-journal/) | Logs trades and calculates win rate and risk-to-reward against readiness benchmarks | Python, pytest |

## How to use the n8n exports

1. In n8n, create a new workflow, open the menu and choose **Import from file**, then select the project's `workflow.json`.
2. Connect your own credentials (Telegram, Google Gemini, Google Sheets where used).
3. Replace the placeholders: `YOUR_TELEGRAM_CHAT_ID`, `YOUR_GOOGLE_SHEET_ID`, `YOUR_SECRET_KEY`, `YOUR_DATA_TABLE_ID`.

All exports are sanitized: they contain no credentials, tokens, chat IDs, sheet IDs or secrets. Screenshots use demo data only.
