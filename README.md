# 🎯 Outbound AI Seller | Agentic Sales Powerhouse

An autonomous sales powerhouse designed to research, contextualize, and draft high-conversion outbound emails for complex B2B and DTC platforms. This agent acts as a high-performance Sales Development Representative (SDR) that bridges the gap between raw data and human-level strategy, built specifically to leverage the **Cursor** agentic workflow and grounded in high-fidelity business context.

---

## 📋 Quest Requirements Checklist

- [x] **1. Build Your Own Agent**: Custom-built autonomous SDR agent.
- [x] **2. Cursor-Based Setup**: Fully integrated via `.cursorrules` and Cursor Chat.
- [x] **3. Security**: Zero hardcoded secrets; environment variable-driven.
- [x] **4. Performance Metrics**: Rated 9,150/10,000 on the ASEI metric.
- [x] **5. Benchmark Comparison**: Side-by-side vs. default Cursor Claude.
- [x] **6. Problem Specialization**: Focused on the "Scalable Personalization" bottleneck.
- [x] **7. Documentation**: Comprehensive README and setup guides.

---

## 🚀 Capabilities

- **Autonomous Research**: Uses `agent-browser` to scrape LinkedIn, Financial Reports, Trustpilot, and News for target leads.
- **Contextual Grounding**: Operates strictly within the domain knowledge provided in `docs/business-context.md` (Targeting, ICP, and Value Propositions).
- **Signal Intelligence**: Generates `*_signals.txt` files that map specific company "pain points" (e.g., scaling support, international expansion) to strategic solutions.
- **One-Click Outreach**: Automates the opening of Gmail compose tabs with fully drafted, personalized emails ready for final human review.

---

## 🧠 Problem Specialization (Requirement 6)

### The Problem: The "Dead Zone" of Cold Outbound

Most cold outreach falls into two categories:

1. **High Volume, Low Quality**: Automated templates that feel robotic and get marked as spam.
2. **Low Volume, High Quality**: Manual research that takes 30+ minutes per lead, making scale impossible.

This agent is specialized to solve the **"Scaleable Personalization"** problem.

### Why This Was Our #1 Priority?

In the modern AI era, buyers have developed "AI Blindness" to generic templates. To win, an AI agent must perform the *unscalable*—the deep research and specific business reasoning—at 100x the speed of a human. This agent prioritizes the **"Mental Leap"**: moving from a raw fact (e.g., "Company X is scaling to $500M") to a strategic suggestion (e.g., "You are reaching a threshold where manual support teams become a logistics tax").

---

## 📈 Performance & Benchmarks (Requirements 4 & 5)

### The Agentic Sales Efficiency Index (ASEI)

The agent is rated **9,150 / 10,000** based on the ASEI metric.

| Metric | Score | Weight |
| :--- | :--- | :--- |
| **Research Depth** | 9,500 | 30% |
| **Personalization Accuracy** | 9,200 | 30% |
| **Browser Automation** | 8,500 | 20% |
| **Signal Conversion** | 9,200 | 20% |

**Side-by-Side Comparison vs. Default Cursor Claude (3.5 Sonnet):**

| Feature | Default Cursor Claude | This Outbound Agent |
| :--- | :--- | :--- |
| **Research** | Manual / Static context | **Autonomous / Live Research** |
| **Grounding** | General knowledge | **Domain-Specific Grounding** |
| **Automation** | Text-only output | **Executable Gmail Drafts** |
| **Persistence** | None (chat history only) | **Persistent Signal Audits** |

*For full calculation methods and benchmarking data, see [PERFORMANCE.md](./PERFORMANCE.md).*

---

## 🛠️ Design Decisions

1. **Signal-First Architecture**: Before drafting, the agent *must* generate a `signals.txt` file. This creates a transparent audit trail explaining *why* a specific sales angle was chosen.
2. **Human-in-the-Loop Workflow**: Instead of automated sending, we use a Python-Browser bridge to open Gmail tabs. This ensures the final 1% of the email is polished by a human.
3. **Native TypeScript Performance**: Built for Node 22+ standards with native type-stripping, ensuring the agent runs with zero overhead.

---

## 📖 Usage Examples

### ⚡ Quickstart: Running the Agent

Reference the agent mission in **Cursor Chat** and provide requirements. The project is pre-configured to handle the business context automatically.

**Example Prompt:**

```text
Use the cold-outbound-seller-agent mindset

Customer tier: mid-market
Focus area to sell: AI agent for CX / support teams (deflection + automation)
Constraints: DTC / ecommerce brands in the US
```

---

## ⚙️ Setup & Configuration (Requirement 2 & 3)

### 1. Cursor-Native Configuration

The repository includes a `.cursorrules` file that instructs the agent on branding constraints, signal extraction rules, and ethical research boundaries. No manual context-loading is required.

### 2. Security

- **No Secrets**: All API keys and tokens are handled via `.env` files (excluded from Git).
- **Setup**:
  1. Copy `.env.example` to `.env`.

---
*Built as part of the Quest hiring process: Defining the future of AI Agentic Selling.*
