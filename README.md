# Mental Health Companion AI (Earlent)

> **Attribution:** This repository contains **Earlent**, an open-source mental-health platform created by **Dhrumil Patel** and released under the MIT License (see [`Mental-Health-Companion-main/LICENSE`](Mental-Health-Companion-main/LICENSE)). It is kept here for study and experimentation. Original authorship belongs to Dhrumil Patel.

**Important:** This is not a medical device and not a substitute for professional care. If you are in crisis, contact local emergency services or a crisis line (India: Tele-MANAS **14416**).

## What's inside

| Part | Path | Stack |
|---|---|---|
| Web client | `Mental-Health-Companion-main/client` | React + Vite (prebuilt copy in `client/dist`) |
| API server | `Mental-Health-Companion-main/server` | Python (Flask) + MongoDB |

Main routes in the client: `/auth`, `/chat`, `/user/mood_logging`, `/user/mood_logs`, `/user/check_in`, `/user/chat_log_Manager`.

## Run locally

```bash
cd Mental-Health-Companion-main/server && cp .env.example .env   # fill in your own values
pip install -r requirements.txt && python app.py
cd ../client && npm install && npm run dev
```

The full feature description is in the original [project README](Mental-Health-Companion-main/README.md).
