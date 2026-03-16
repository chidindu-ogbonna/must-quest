# 📧 Outbound Email Drafts

This directory serves as the final staging area for hyper-personalized sales outreach. It is primarily managed by the **Cold Outbound Seller Agent**.

## 🏗️ Folder Purpose

Files in this directory are generated after deep research into target accounts. They bridge the gap between "Signal Extraction" (recorded in `*_signals.txt`) and "Action" (Gmail automation).

## 📝 File Naming Convention

For consistency and automation compatibility, follow this format:
`[company-name]-[buyer-last-name]-outbound.txt`

*Example: `stripe-collison-outbound.txt`*

## 📋 Content Requirements

Each file must follow a strict plain-text structure to ensure it is "Copy-Paste Ready" for SDRs:

1. **Buyer Summary**: Name, Role, Company, and LinkedIn/Public URL.
2. **Key Signals**: 3–5 bullet points of research-backed insights (funding, hiring, news).
3. **Sales Opportunities**: 2–3 concrete ways Siena AI solves their objective pain points.
4. **Outreach Angle**: The core narrative hypothesis.
5. **The Draft**:
   - **Subject**: Short, non-spammy, high-hook line.
   - **Body**: Personalized, respectful, senior-tone email.

## 🤖 Instructions for Cursor

When tasked with generating outbound emails for this project:

- **Grounding**: Always read `docs/business-context.md` before drafting.
- **Reference Signals**: Ensure every claim in the email is backed by a signal found during research.
- **Tone**: Professional, empathic, and senior. No hyperbole.
- **Automation**: After drafting, trigger the Gmail compose flow via `agent-browser --headed` if requested.

---
*Note: Do not commit sensitive contact data. Use placeholders for private emails if not publicly found.*
