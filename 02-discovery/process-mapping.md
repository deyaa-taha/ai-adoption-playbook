# 02 · Discovery — Process Mapping

> Goal: build an evidence-based inventory of **routine processes** and identify where AI can help — before choosing any tool.

## 1. Method (4–6 weeks for a mid-size organization)

1. **Pick departments.** Start with 2–3 departments with a willing manager and visible repetitive work.
2. **Interview.** 45–60 minutes per team, using the guide below. Ask about work, not about AI.
3. **Capture.** One [process card](../templates/process-card.md) per routine process.
4. **Score.** Apply the [suitability scoring matrix](suitability-scoring.md).
5. **Visualize.** Plot processes on a value × feasibility chart and review with department managers.
6. **Select.** Choose 2–3 quick wins and a longer-term backlog.

> Rule of thumb: an organization with ~10 departments typically surfaces **40–80 routine processes**. Expect roughly 10–20% to be strong quick-win candidates.

## 2. Interview guide

Ask about **work**, not technology. People describe pain more accurately than solutions.

**Volume & time**
- What tasks do you repeat every day or week?
- How long does each take? How many times per month?

**Inputs & outputs**
- What do you receive (emails, forms, PDFs, scans, system screens)?
- What do you produce (replies, reports, data entry, decisions)?

**Pain & errors**
- Where do mistakes happen? What happens when they do?
- What do you copy-paste between systems?
- What waits in a queue because nobody has time?

**Knowledge**
- Where do you look up rules, procedures or past answers?
- What do new employees struggle to learn?

**Constraints**
- Which data is sensitive (customers, finance, HR, health)?
- Who must approve the output?

## 3. Typical AI patterns to look for

| Pattern | Example signals | Typical solution |
|---|---|---|
| **Document understanding** | Reading invoices, forms, contracts, scans | OCR + structured extraction + validation |
| **Classification & routing** | Sorting emails or tickets to the right team | LLM classifier with confidence threshold |
| **Drafting** | Writing replies, summaries, reports | LLM drafting with human approval |
| **Knowledge Q&A** | "Where is the procedure for…?" | RAG over approved documents |
| **Data entry between systems** | Copying fields from one screen to another | Workflow automation + extraction |
| **Analysis & reporting** | Manual Excel consolidation | Automation + AI summarization |
| **Multi-step work** | Investigate, gather, decide, act | Agent with tools and human checkpoints |

## 4. Output of the discovery phase

- Process inventory (spreadsheet or dashboard) with scores
- Value × feasibility chart
- Quick-win shortlist with owners and baselines
- Longer-term backlog grouped by AI pattern
- A short presentation for management

---
Next → [Suitability scoring](suitability-scoring.md)
