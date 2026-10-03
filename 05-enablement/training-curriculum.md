# 05 · Enablement — Role-Based Training Curriculum

> Goal: teach people to **use AI professionally** in their own role — not to turn everyone into data scientists.

## 1. Tracks

| Track | Audience | Length | Outcome |
|---|---|---|---|
| **A · AI basics** | All employees | 1.5 hours | Safe, effective daily use under the policy |
| **B · AI for systems analysts** | Analysts, product owners | 5 × 3-hour sessions | Can identify, specify and validate AI use cases |
| **C · AI for developers** | Engineers | 4 × 3-hour sessions | Can use AI coding tools and build AI features properly |
| **D · AI for managers** | Department managers | 2 hours | Can spot opportunities and sponsor use cases |

## 2. Track A — AI basics (everyone)

1. What LLMs are good and bad at (and why they "hallucinate")
2. The usage policy in 10 minutes — data classes and do / don't
3. Prompting basics: role, context, task, format, examples
4. Hands-on: rewrite an email, summarize a document, build a checklist
5. Verifying output and staying accountable

## 3. Track B — AI for systems analysts

The core flow taught across the track:

```text
Business problem → Use case → Data → Solution pattern (RAG / agent / extraction) → Requirements → Architecture → Backlog
```

| Session | Topics | Exercise |
|---|---|---|
| 1 | GenAI fundamentals, model types, limits, cost | Compare two models on the same task |
| 2 | Prompt engineering for analysis: structured prompts, few-shot, output schemas | Turn a messy requirement into a structured spec with AI |
| 3 | Identifying AI use cases; suitability scoring; RAG vs. agents vs. extraction | Score 5 real processes |
| 4 | Writing AI requirements: inputs, outputs, confidence, fallbacks, human review, evaluation criteria, security | Write requirements for one use case |
| 5 | AI-assisted impact analysis on a codebase; final project review | Present a complete use-case specification |

**Final deliverable:** a full use-case specification using the [use-case canvas](../templates/use-case-canvas.md).

## 4. Track C — AI for developers

| Session | Topics |
|---|---|
| 1 | AI coding assistants: workflows, context, reviewing generated code, team standards |
| 2 | Calling LLMs from code: structured outputs, retries, timeouts, cost, the AI gateway |
| 3 | RAG: chunking, embeddings, retrieval, citations, evaluation |
| 4 | Agents & security: tools, human checkpoints, prompt injection, secrets, logging |

**Team standards to agree on:** which assistant(s) are approved, what may be sent to them, and that **AI-generated code gets the same review as any other code**.

## 5. Making training stick

- Use **real, sanitized examples from the participants' own work**.
- Every session ends with something they will use **tomorrow**.
- Create an internal **prompt library** and a channel for sharing wins.
- Champions run short follow-up sessions in their departments.

---
Next → [06 · Delivery](../06-delivery/use-case-lifecycle.md)
