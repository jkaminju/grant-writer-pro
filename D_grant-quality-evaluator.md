---
name: grant-quality-evaluator
description: Evaluate grant proposal drafts against RFP requirements and quality standards. Scores compliance, identifies gaps, suggests improvements, and validates evidence quality for Bitz IT Consulting / OpenCHS humanitarian tech proposals.
---

# Grant Proposal Quality Evaluator

## Purpose
Systematically evaluate grant proposal drafts to ensure compliance, quality, and competitiveness. Provides scored assessment against donor evaluation criteria, identifies fatal flaws, and generates prioritized improvement recommendations.

## Inputs Required

### Required:
- **PROPOSAL_DRAFT**: The proposal document to evaluate
- **RFP_REQUIREMENTS**: Output from grant-requirements-analyzer skill
  - Evaluation criteria and weights
  - Mandatory requirements
  - Format/submission rules

### Optional:
- **DONOR_TYPE**: UNICEF/UNFPA/GIZ, World Bank, Foundation (inferred if not stated)
- **EVALUATION_FOCUS**: compliance-only, quality-only, or full (default: full)

## Workflow

### Step 1: Compliance Check (Pass/Fail)
Verify all mandatory requirements are met:
- Page/word limits
- Required sections present
- Mandatory attachments referenced
- Formatting rules followed
- Eligibility criteria addressed
- Submission instructions followed

**Output:** COMPLIANCE STATUS: PASS / FAIL (with specific violations listed)

### Step 2: Evaluation Criteria Scoring
For each criterion in the RFP:
- Locate where it's addressed in proposal
- Score against rubric (see below)
- Identify evidence gaps
- Note competitor advantages/disadvantages

### Step 3: Quality Assessment
Evaluate overall quality dimensions:
- Clarity and readability
- Evidence quality and specificity
- Logical flow and coherence
- Risk management and realism
- Value for money demonstration
- Innovation and differentiation

### Step 4: Generate Improvement Recommendations
Prioritized list of:
- Fatal flaws (must fix)
- High-impact improvements
- Quick wins (easy fixes with big impact)
- Optional enhancements

## Evaluation Rubric

### Overall Scoring (Total: 100 points)

Aligns with typical donor evaluation frameworks:

| Criterion | Weight | Scoring Guide |
|-----------|--------|---------------|
| **1. Relevance & Problem Clarity** | 15 pts | How well does it address the problem and donor objectives? |
| **2. Solution Quality & Feasibility** | 20 pts | Is the approach sound, innovative, and realistic? |
| **3. Evidence & Impact Measurement** | 15 pts | Quality of evidence, M&E framework, past performance |
| **4. Scalability & Sustainability** | 10 pts | Post-project viability, government ownership, scalability |
| **5. Value for Money** | 10 pts | Cost-effectiveness, budget justification, efficiency |
| **6. Team & Governance** | 10 pts | Qualifications, relevant experience, management structure |
| **7. Risk Management** | 5 pts | Risk identification, mitigation strategies |
| **8. Safeguarding & Responsible AI** | 5 pts | Child protection, PSEA, data protection, AI ethics |
| **9. Partnerships & Country Ownership** | 5 pts | Government coordination, local partners, capacity building |
| **10. Compliance & Presentation** | 5 pts | Format, completeness, clarity, professionalism |

### Detailed Scoring Anchors (1-5 scale for each criterion)

**5 - Excellent**
- Exceeds requirements
- Compelling evidence
- No gaps or weaknesses
- Highly competitive

**4 - Good**
- Meets all requirements
- Solid evidence
- Minor gaps easily addressed
- Competitive

**3 - Satisfactory**
- Meets minimum requirements
- Some evidence provided
- Notable gaps that weaken proposal
- May be competitive depending on field

**2 - Weak**
- Partially addresses requirements
- Limited or weak evidence
- Significant gaps
- Unlikely to be competitive

**1 - Poor**
- Does not address requirements
- No evidence or irrelevant evidence
- Major flaws
- Not competitive

## Output Format

### EXECUTIVE ASSESSMENT

**Overall Score:** [X]/100  
**Competitive Position:** Excellent / Strong / Moderate / Weak / Non-competitive  
**Compliance Status:** PASS / FAIL  
**Recommendation:** Submit as-is / Minor revisions / Major revisions / Do not pursue

**One-Sentence Summary:**
[Concise overall assessment]

---

### COMPLIANCE CHECKLIST

| Requirement | Status | Notes |
|------------|--------|-------|
| Page limit ([X] pages max) | ✅ PASS / ❌ FAIL | [Current: X pages] |
| Word limit ([X] words max) | ✅ PASS / ❌ FAIL | [Current: X words] |
| Required sections complete | ✅ PASS / ❌ FAIL | [Missing: list if any] |
| Formatting rules followed | ✅ PASS / ❌ FAIL | [Violations: list if any] |
| Mandatory attachments referenced | ✅ PASS / ❌ FAIL | [Missing: list if any] |
| Eligibility demonstrated | ✅ PASS / ❌ FAIL | [Gaps: list if any] |

**Fatal Flaws (must fix before submission):**
- [List any disqualifying issues]

---

### CRITERION-BY-CRITERION SCORES

#### 1. Relevance & Problem Clarity (15 pts)
**Score:** [X]/15 ([rating]/5 scale)

**Strengths:**
- [What's done well]

**Weaknesses:**
- [What's missing or weak]

**Evidence Quality:**
- [Assessment of supporting data/citations]

**Improvement Opportunities:**
- [Specific suggestions]

---

#### 2. Solution Quality & Feasibility (20 pts)
**Score:** [X]/20 ([rating]/5 scale)

**Strengths:**
- [What's done well]

**Weaknesses:**
- [What's missing or weak]

**Evidence Quality:**
- [Assessment of methodology, innovation claims]

**Improvement Opportunities:**
- [Specific suggestions]

---

[Repeat for all 10 criteria]

---

### EVIDENCE QUALITY ASSESSMENT

| Claim | Evidence Provided | Quality | Recommendation |
|-------|------------------|---------|----------------|
| "OpenCHS serves 120K calls/month" | ✅ Specific, quantified | STRONG | Keep as-is |
| "AI reduces documentation time by 60%" | ✅ Measured | STRONG | Add source/study |
| "System is highly scalable" | ❌ Generic claim | WEAK | Add evidence: deployment speed, cost per country |
| [Other key claims] | [Evidence status] | [Quality rating] | [Action needed] |

**Evidence Gaps Requiring Urgent Attention:**
1. [Critical missing evidence]
2. [Next priority]

---

### WIN THEMES ASSESSMENT

**Are our competitive advantages clearly highlighted?**
- [ ] Open-source approach (vs. proprietary)
- [ ] Multi-country proven track record
- [ ] AI innovation with human oversight
- [ ] Partnership with UNICEF/UNFPA/GIZ
- [ ] Safeguarding built into design
- [ ] Government ownership model
- [ ] Interoperability standards

**Recommended messaging adjustments:**
- [Suggestions to strengthen differentiation]

---

### RISK & MITIGATION REVIEW

| Risk Identified | Mitigation Quality | Scoring Impact | Recommendation |
|----------------|-------------------|----------------|----------------|
| [Risk 1] | Strong / Adequate / Weak | H / M / L | [Improvement if needed] |
| [Risk 2] | Strong / Adequate / Weak | H / M / L | [Improvement if needed] |

**Missing Risks to Address:**
- [Risks evaluators will spot that we haven't addressed]

---

### BUDGET & VALUE FOR MONEY

**Budget Alignment:**
- Total: [Amount] (limit: [Amount]) ✅ / ❌
- Major categories justified: ✅ / ⚠️ / ❌
- Efficiency demonstrated: ✅ / ⚠️ / ❌

**Value-for-Money Narrative:**
- Strength: [assessment]
- Improvements needed: [suggestions]

**Cost-Effectiveness Examples:**
- [Check if proposal includes per-beneficiary costs, cost per outcome, etc.]

---

### SAFEGUARDING & RESPONSIBLE AI

**Child Safeguarding:**
- Policy attached: ✅ / ❌
- Practical measures described: ✅ / ⚠️ / ❌
- PSEA commitment clear: ✅ / ❌

**Data Protection:**
- Privacy measures outlined: ✅ / ⚠️ / ❌
- Consent protocols: ✅ / ⚠️ / ❌
- Data security: ✅ / ⚠️ / ❌

**Responsible AI:**
- Bias mitigation: ✅ / ⚠️ / ❌
- Human oversight: ✅ / ⚠️ / ❌
- Transparency/explainability: ✅ / ⚠️ / ❌
- Accountability mechanisms: ✅ / ⚠️ / ❌

**Improvement Recommendations:**
- [Specific additions needed]

---

### PRESENTATION & CLARITY

**Readability:**
- [1-5 rating]
- [Notes on clarity, jargon, flow]

**Visual Elements:**
- Charts/diagrams effective: ✅ / ⚠️ / ❌
- Tables well-formatted: ✅ / ⚠️ / ❌
- Visuals needed: [Suggestions]

**Formatting:**
- Professional appearance: ✅ / ⚠️ / ❌
- Consistent style: ✅ / ⚠️ / ❌
- Error-free: ✅ / ⚠️ / ❌

---

### PRIORITIZED IMPROVEMENTS

#### 🔴 CRITICAL (Fix before submission - < 24 hours)
1. [Fatal flaw 1]
2. [Fatal flaw 2]

#### 🟡 HIGH IMPACT (Significantly improve score - 2-4 hours)
1. [High-value improvement 1]
2. [High-value improvement 2]
3. [High-value improvement 3]

#### 🟢 QUICK WINS (Easy fixes, visible improvement - < 1 hour)
1. [Quick fix 1]
2. [Quick fix 2]
3. [Quick fix 3]

#### ⚪ OPTIONAL ENHANCEMENTS (if time allows)
1. [Nice-to-have 1]
2. [Nice-to-have 2]

---

### REWRITE CHECKLIST

Top 12 edits that most improve quality:

1. [ ] **Lead with outcomes, not activities**
   - Current: "We will conduct training sessions..."
   - Better: "300 counselors will gain AI-assisted documentation skills, reducing case processing time by 40%..."

2. [ ] **Quantify impact everywhere possible**
   - Add numbers: beneficiaries reached, time saved, cost per case, etc.

3. [ ] **Add specific evidence for each major claim**
   - Every "we are experienced" needs: "In [country], we deployed [system] serving [number] beneficiaries with [result]"

4. [ ] **Tighten language (remove 20% of words)**
   - Cut: "We plan to implement a comprehensive system that will..."
   - Keep: "We will implement a system that..."

5. [ ] **Front-load key information**
   - Most important points in first paragraph of each section

6. [ ] **Address evaluator concerns proactively**
   - Sustainability: How will it continue after donor funding?
   - Scalability: What's the path from pilot to national scale?
   - Government ownership: How do we transfer capacity?

7. [ ] **Replace jargon with plain language**
   - "Leverage synergies" → "work together"
   - "Stakeholder engagement" → "partner coordination"

8. [ ] **Add competitor differentiation**
   - What makes us better than alternatives?

9. [ ] **Strengthen risk mitigation**
   - For each risk: specific, actionable mitigation (not generic)

10. [ ] **Improve budget narrative**
    - Justify why each major cost is necessary and reasonable

11. [ ] **Add visuals where they clarify**
    - Theory of Change
    - Implementation timeline
    - User journey
    - Technical architecture (if applicable)

12. [ ] **Final polish**
    - Remove all [PLACEHOLDER] tags
    - Consistent formatting
    - No typos or grammatical errors
    - All cross-references correct

---

### NON-NEGOTIABLES FOR BITZ/OPENCHS BRAND

Ensure these principles are visible:

✅ **Open-source posture**
- Code transparency, no vendor lock-in

✅ **Child safeguarding**
- Built-in, not bolt-on

✅ **Confidentiality & data protection**
- Privacy by design

✅ **Interoperability**
- Standards-based, government systems integration

✅ **Government ownership**
- Sustainability through public sector capacity

✅ **Evidence-based**
- Measured impact, continuous improvement

**Violations found:**
- [List any places where proposal contradicts brand principles]

---

### COMPETITIVE POSITIONING

**Likely competitors:**
- [Based on donor and scope, who else might bid?]

**Our advantages:**
- [What makes us stronger]

**Our vulnerabilities:**
- [Where competitors might beat us]

**Messaging adjustments:**
- [How to emphasize strengths, mitigate weaknesses]

---

### FINAL RECOMMENDATION

**Submit status:**
- ✅ **READY TO SUBMIT** (score >80, no fatal flaws)
- ⚠️ **SUBMIT WITH MINOR EDITS** (score 70-80, address critical items only)
- ❌ **MAJOR REVISION NEEDED** (score 60-70, significant work required)
- 🛑 **DO NOT PURSUE** (score <60, not competitive or misaligned)

**Time to ready:** [Estimated hours of work needed]

**Probability of success:** High / Moderate / Low  
**Rationale:** [Brief explanation]

---

## Quality Checks

Before finalizing evaluation:
- ✅ All 10 criteria scored
- ✅ Evidence quality assessed for major claims
- ✅ Compliance status clear
- ✅ Improvements prioritized by impact
- ✅ Specific, actionable recommendations (not vague)
- ✅ Honest assessment (acknowledge weaknesses)

## Constraints & Rules

**DO:**
- Be honest about weaknesses
- Provide specific, actionable feedback
- Prioritize by impact (what matters most for score)
- Reference RFP requirements explicitly
- Consider evaluator perspective

**DO NOT:**
- Sugar-coat fatal flaws
- Provide generic feedback ("improve quality")
- Ignore compliance violations
- Recommend pursuing if fundamentally misaligned

## Example Usage

**Input:**
```
PROPOSAL_DRAFT: [25-page UNICEF proposal]
RFP_REQUIREMENTS: [From grant-requirements-analyzer output]
```

**Output:**
```
EXECUTIVE ASSESSMENT
Overall Score: 78/100
Competitive Position: Strong
Compliance Status: PASS
Recommendation: SUBMIT WITH MINOR EDITS

One-Sentence Summary: Solid proposal with strong technical approach and evidence, but needs sharper sustainability narrative and clearer budget justification.

[Full detailed assessment follows...]
```

## Related Skills

Works with:
- `grant-requirements-analyzer` (provides evaluation criteria)
- `grant-proposal-drafter` (evaluates its output)
- Iterative loop: evaluate → improve → re-evaluate

---

**Created for:** Bitz IT Consulting Ltd / OpenCHS  
**Version:** 1.0  
**Last Updated:** February 2026
