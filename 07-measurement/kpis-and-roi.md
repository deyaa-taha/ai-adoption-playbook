# 07 · Measurement — KPIs and ROI

> Goal: prove value with numbers management trusts — and decide what to scale or stop.

## 1. KPIs by level

| Level | KPI | How to measure |
|---|---|---|
| **Use case** | Time saved per transaction | Baseline vs. pilot timing on a sample |
| | Volume handled | System logs |
| | Accuracy / error rate | Review of a sample vs. ground truth |
| | Manual-review rate | % of items below confidence threshold |
| | Cost per transaction | Gateway cost ÷ transactions |
| **Program** | Use cases in production | Lifecycle backlog |
| | Hours saved per month (total) | Sum across use cases |
| | Active users of approved tools | Tool admin dashboards |
| | Time from idea to production | Lifecycle dates |
| **People** | Employees trained (by track) | Training records |
| | Satisfaction / perceived usefulness | Short quarterly survey |
| **Risk** | Policy incidents | Incident log |
| | Shadow-AI usage trend | Network / CASB signals, surveys |

## 2. ROI formula

```text
Monthly benefit  = hours saved × loaded hourly cost
                 + error cost avoided
                 + other measurable gains (faster SLA, revenue, etc.)

Monthly cost     = licenses + model usage + platform/hosting
                 + support & maintenance effort

ROI (12 months)  = (12 × monthly benefit − one-time build cost − 12 × monthly cost)
                   ÷ (one-time build cost + 12 × monthly cost)
```

**Be conservative.** Count only time that is actually redeployed to other work, and show the assumptions.

## 3. Worked example (illustrative)

| Item | Value |
|---|---|
| Emails classified per month | 6,000 |
| Time saved per email | 1.5 min |
| Hours saved per month | 150 |
| Loaded hourly cost | $40 |
| **Monthly benefit** | **$6,000** |
| Model + platform cost per month | $400 |
| Support effort per month | $600 |
| **Monthly cost** | **$1,000** |
| One-time build cost | $15,000 |
| **12-month ROI** | (72,000 − 15,000 − 12,000) ÷ (15,000 + 12,000) = **167%** |

## 4. Executive report (quarterly, one page)

1. **Headline:** hours saved, use cases live, ROI to date
2. **Wins:** 2–3 short stories with numbers and a user quote
3. **Pipeline:** what's in pilot, what's next
4. **Risks & incidents:** what happened, what changed
5. **Asks:** budget, people, decisions needed

---
Back to [README](../README.md)
