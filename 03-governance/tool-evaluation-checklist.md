# AI Tool Evaluation Checklist

> Use before adding any AI tool or AI feature to the approved list.

**Tool:** ____________ **Vendor:** ____________ **Requested by:** ____________ **Date:** ________

## 1. Business fit
- [ ] Clear use case and owner
- [ ] Not duplicating an already approved tool
- [ ] Expected users and monthly volume estimated

## 2. Data protection
- [ ] Vendor does **not** train on our data (contractually confirmed)
- [ ] Data retention period known and acceptable
- [ ] Data residency / region known and acceptable
- [ ] Encryption in transit and at rest
- [ ] Maximum data class allowed: Public / Internal / Confidential / Restricted

## 3. Security & access
- [ ] SSO / enterprise identity integration
- [ ] Role-based access and admin controls
- [ ] Audit logs available
- [ ] Security certifications reviewed (e.g. SOC 2, ISO 27001)
- [ ] Prompt-injection and data-exfiltration risks considered for agents / tool use

## 4. Quality
- [ ] Tested on 20+ real (sanitized) examples from our domain
- [ ] Works in our languages (including RTL languages if relevant)
- [ ] Error / hallucination behavior acceptable for the use case

## 5. Cost & operations
- [ ] Pricing model understood (per seat / per token / per call)
- [ ] Budget owner and monthly cap defined
- [ ] Usage and cost can be monitored
- [ ] Exit plan: data export and replacement option

## 6. Decision

| Decision | Allowed data class | Conditions | Review date |
|---|---|---|---|
| Approved / Approved with conditions / Rejected | | | |

**Approvers:** AI adoption lead · Security · Legal / privacy (for Confidential+)
