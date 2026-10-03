# 03 · Governance — AI Usage Policy Template

> Goal: give employees **clear, simple rules** so they can use AI safely without asking permission every time.
> A short policy that people read beats a long one nobody opens. Aim for **2 pages**.

---

## Template

### 1. Purpose
This policy defines how employees may use AI tools to improve productivity while protecting customers, employees and the company.

### 2. Scope
Applies to all employees, contractors and vendors using AI tools for company work — including chat assistants, coding assistants, AI features inside existing software, and custom-built AI systems.

### 3. Approved tools
Only tools on the **approved tool list** (maintained by the AI adoption lead) may be used with company data.
Tools are approved through the [tool evaluation checklist](tool-evaluation-checklist.md).

### 4. Data rules

| Data class | Examples | Public AI tools | Approved enterprise AI tools | Self-hosted / private models |
|---|---|---|---|---|
| **Public** | Published website content, public docs | ✅ | ✅ | ✅ |
| **Internal** | Internal procedures, non-sensitive code | ❌ | ✅ | ✅ |
| **Confidential** | Customer data, contracts, financials, source code with secrets removed | ❌ | ⚠️ Only if approved for this class | ✅ |
| **Restricted** | ID numbers, payment data, health data, credentials, secrets | ❌ | ❌ | ⚠️ Only with security approval |

**Never** paste passwords, API keys, tokens or connection strings into any AI tool.

### 5. Human accountability
- AI output is a **draft**. The employee who uses it is responsible for the result.
- Outputs affecting customers, money, legal commitments or employees **must be reviewed by a person** before use.
- Do not present AI-generated content as verified fact without checking it.

### 6. Prohibited uses
- Making fully automated decisions about individuals (hiring, credit, discipline) without human review.
- Generating content that impersonates real people or misleads customers.
- Uploading third-party confidential data without contractual permission.
- Bypassing security controls or using personal accounts for company data.

### 7. Building AI systems
Custom AI systems (RAG, agents, automations) must follow the [use-case lifecycle](../06-delivery/use-case-lifecycle.md), including a risk review before production.

### 8. Transparency
When AI meaningfully generates customer-facing content or decisions, disclose it where required by law or company policy.

### 9. Incidents
Report suspected data leaks, harmful outputs or misuse to security immediately. Honest reporting is never penalized.

### 10. Ownership & review
Owner: AI adoption lead, together with security and legal. Reviewed **every 6 months** or after major regulatory or technology changes.

---

## Rollout tips

- Publish v1 within **4–6 weeks** — imperfect and live beats perfect and pending.
- Pair the policy with a **one-page "do / don't" poster** and a 30-minute training.
- Check local regulation (e.g. privacy laws, the EU AI Act where relevant) with legal counsel; this template is a starting point, not legal advice.

---
Next → [Tool evaluation checklist](tool-evaluation-checklist.md)
