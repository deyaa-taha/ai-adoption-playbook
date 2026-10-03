# Suitability Scoring Matrix

> Goal: rank processes objectively so the first projects are chosen by evidence, not by whoever shouts loudest.

## 1. Criteria

Score each criterion **1 (low) to 5 (high)**.

### Value

| Criterion | 1 | 3 | 5 | Weight |
|---|---|---|---|---|
| **Volume** | Rare (monthly) | Weekly | Many times daily | 20% |
| **Time per instance** | < 2 min | 10–20 min | > 1 hour | 15% |
| **Error cost** | Cosmetic | Rework needed | Financial / customer / legal impact | 10% |
| **Strategic visibility** | Nobody notices | Department level | Management / customers notice | 5% |

### Feasibility

| Criterion | 1 | 3 | 5 | Weight |
|---|---|---|---|---|
| **Input structure** | Handwritten, chaotic | Semi-structured | Digital, consistent | 15% |
| **Rule clarity** | Pure judgment | Mostly rules + some judgment | Clear rules / examples | 10% |
| **Data availability** | No access | Access with effort | Ready via API / export | 10% |
| **Risk (inverted)** | Autonomous high-stakes decisions | Human reviews output | Internal, low-risk | 15% |

- **Total score** = Σ (criterion × weight) → 1.0 to 5.0, used for ranking.
- **Value score** = Σ (value criteria × weight) ÷ 0.5 → 1.0 to 5.0
- **Feasibility score** = Σ (feasibility criteria × weight) ÷ 0.5 → 1.0 to 5.0

The total ranks the list; the two sub-scores decide the category below.

## 2. Classification

| Value | Feasibility | Category | Action |
|---|---|---|---|
| High | High | **Quick win** | Do now — pilot within 90 days |
| High | Low | **Strategic bet** | Plan; fix data/integration first |
| Low | High | **Self-service** | Let teams use approved tools themselves |
| Low | Low | **Park** | Revisit next year |

Use a sub-score **≥ 3.5** as "high" for a first pass, then adjust with management judgment.

## 3. Readiness check (before committing a quick win)

- [ ] A named business owner who wants it
- [ ] A measurable baseline (time, volume, error rate)
- [ ] Sample data available (at least 20–50 real examples)
- [ ] Data classification known and allowed by policy
- [ ] Human approval step defined
- [ ] Success criteria agreed in writing

## 4. Example

| Process | Vol | Time | Err | Vis | Struct | Rules | Data | Risk | Value | Feas. | **Total** | Category |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| Classify incoming customer emails | 5 | 2 | 3 | 4 | 4 | 4 | 5 | 4 | 3.6 | 4.2 | **3.90** | Quick win |
| Extract fields from supplier invoices | 4 | 3 | 4 | 3 | 3 | 5 | 4 | 4 | 3.6 | 3.9 | **3.75** | Quick win |
| Draft legal contract changes | 2 | 5 | 5 | 4 | 2 | 2 | 3 | 1 | 3.7 | 1.9 | **2.80** | Strategic bet |

*Example values are illustrative.*

---
Next → [03 · Governance](../03-governance/ai-usage-policy.md)
