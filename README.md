# 🎯 Antigravity Outbound AI Seller

An agentic sales powerhouse designed to research, contextualize, and draft high-conversion outbound emails for **Siena AI**. This agent doesn't just write emails; it acts as an autonomous Sales Development Representative (SDR) that bridges the gap between raw data and human-level strategy.

## 🚀 Capabilities

* **Autonomous Research**: Uses `agent-browser` to scrape LinkedIn, Financial Reports, Trustpilot, and News for target leads.
* **Contextual Grounding**: Operates strictly within the provided `docs/business-context.md` (Siena AI's brand voice, ICP, and value props).
* **Signal Intelligence**: Generates `*_signals.txt` files that map specific company "pain points" (e.g., scaling support, international expansion) to Siena’s solutions.
* **One-Click Outreach**: Automates the opening of Gmail compose tabs with fully drafted, personalized emails ready for a final human touch.

---

## 🧠 Problem Specialization (Section 6)

### The Problem: The "Dead Zone" of Cold Outbound

Most cold outreach falls into two categories:

1. **High Volume, Low Quality**: Automated templates that feel robotic and get marked as spam.
2. **Low Volume, High Quality**: Manual research that takes 30+ minutes per lead, making scale impossible.

We specialized this agent to solve the **"Scaleable Personalization"** problem.

### Why This Was Our #1 Priority?

Sales is the lifeblood of growth. In the modern AI era, buyers have developed "AI Blindness" to generic templates. To win, an AI agent must perform the *unscalable*—the deep research and specific business reasoning—at 100x the speed of a human. This agent prioritizes the **"Mental Leap"**: moving from a fact (e.g., "Olipop is scaling to $500M") to a strategic suggestion (e.g., "You are paying a logistics tax on your community team").

---

## 📈 Performance & Benchmarks

### The Agentic Sales Efficiency Index (ASEI)

The agent is rated **9,150 / 10,000** based on our proprietary ASEI metric.

* **Research Depth (30%)**: 9,500
* **Personalization Accuracy (30%)**: 9,200
* **Browser Automation (20%)**: 8,500
* **Signal Conversion (20%)**: 9,200

**Side-by-Side Comparison vs. Default Cursor (Claude 3.5 Sonnet):**

| Feature | Cursor Claude | Antigravity Agent |
| :--- | :--- | :--- |
| **Research** | Manual / Static | **Autonomous / Live** |
| **Grounding** | General | **Business-Specific** |
| **Automation** | Text only | **Gmail-Ready Drafts** |
| **Persistence** | None | **Persistent Signal Audits** |

*For full calculation methods and benchmarking data, see [PERFORMANCE.md](./PERFORMANCE.md).*

---

## 🛠️ Design Decisions

1. **Signal-First Architecture**: We didn't want the agent to just "write an email." We forced it to first generate a `signals.txt` file. This creates an audit trail where a human can see *why* the AI made a certain claim.
2. **Python-Browser Bridge**: Instead of trying to "send" the email (which risks spam filters and account bans), we open focused Gmail tabs. This keeps the "Human-in-the-Loop" for the final 1% of the process.
3. **Experimental Type Stripping**: Built for Node 22+ standards, ensuring high performance and native TypeScript execution.

---

## 📖 Usage Examples

## ⚡ Quickstart: run the `cold-outbound-seller` agent

In **Cursor Chat**, explicitly reference the agent file and ask it to run.

**Example (copy/paste):**

```text
Use the cold-outbound-seller agent

Customer tier: mid-market
Focus area to sell: AI agent for CX / support teams (deflection + automation)
Constraints: DTC / ecommerce brands in the US
```

---

## ⚙️ Setup & Configuration

1. **Security**: Copy `.env.example` to `.env` and add your credentials.
2. **Cursor-Ready**: This project includes `.cursorrules` to ensure AI instructions are consistently followed.

---
*Built for the Quest: Defining the future of AI Agentic Selling.*
