# [World Terminal](https://worldterminal-ruby.vercel.app)

Real-time market data, global news, and geopolitical events — unified in a single AI-powered terminal. Ask questions, surface connections, and understand what's moving the world.

---

## What It Does

World Terminal aggregates live financial markets, global news, and geopolitical events into a dense, information-rich display. Think of it as a command center for staying on top of what's moving markets and the world.

**Core panels:**

- **Market Chart** — Live price charts for indices, commodities, metals, and crypto. Switch between 13 instruments across 6 time ranges.
- **AI Analyst** — Auto-generated market commentary linking price moves to recent events.
- **News Feed** — Curated event log with impact levels (HIGH / MED / LOW) and category badges (GEO / MRKT / POL / TECH). Click any event for details.
- **Prediction Markets** — Polymarket odds surfaced inline with event context.
- **World Clock** — Live clocks for 28 global financial centers, drag-to-reorder, searchable.

---

## AI Features

### AI Analyst

An always-on panel that automatically connects market moves to the events driving them. No prompting needed — it surfaces context as prices shift.

### AI Chat *(coming soon)*

An in-dashboard chat assistant that lets you interact directly with the data you're looking at:

- Ask questions about market movements and get answers grounded in live data
- Query events on the timeline by date, category, or severity
- Request summaries, comparisons, or context for anything on screen

AI Chat is scoped entirely to the dashboard — financial markets, macro events, geopolitics. It won't drift into off-topic territory.

### AI Interactive Interface *(coming soon)*

An agent-supported interface that proactively surfaces connections, trends, and notifications across multiple data sources.

---

## Stack


| Layer      | Technology                                         |
| ---------- | -------------------------------------------------- |
| Frontend   | Next.js 16, React 19, TypeScript 5, Tailwind CSS 4 |
| Charts     | lightweight-charts 5.1 (TradingView)               |
| Backend    | Python WebSocket server, yfinance                  |
| AI         | Gemini API + Global Search                         |
| Deployment | Vercel (frontend) + Railway (backend)              |


---

## Demo

### Video



> Demo video coming soon — [Live site](https://worldterminal-ruby.vercel.app)

### Screenshots

<img width="2558" height="1349" alt="Screenshot 2026-04-10 at 3 00 26 PM" src="https://github.com/user-attachments/assets/3328c227-1b96-49e3-abee-d676fa41fe55" />

With AI Analyst
<img width="2558" height="1347" alt="Screenshot 2026-04-10 at 3 16 51 PM" src="https://github.com/user-attachments/assets/6cbeb449-cd12-4336-9c8f-4753b65b704f" />

