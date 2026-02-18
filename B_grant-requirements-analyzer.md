---
name: grant-requirements-analyzer
description: Extract and structure grant RFPs/ToRs into an action-ready requirements map and compliance plan. Identifies deadlines, eligibility, evaluation criteria, budget rules, and alignment opportunities for Bitz IT Consulting / OpenCHS humanitarian tech proposals.
---

# Grant Requirements Analyzer

## Purpose
Analyze grant RFPs, calls for proposals, and Terms of Reference to extract all critical requirements, create compliance matrices, and identify strategic alignment opportunities. Designed for humanitarian technology proposals (child protection, GBV, PSEA, grievance mechanisms, AI-assisted case management).

## Inputs
- **RFP_TEXT**: The full RFP/ToR/Call document text (paste or attach)
- **ORG_CONTEXT** (optional): Bitz IT Consulting Ltd + OpenCHS background
  - Default: Helpline + case management for VAC/GBV/PSEA/grievance redress
  - AI-assisted triage and documentation
  - Open-source, interoperable, multi-country deployments
  - Partners: UNICEF/UNFPA/GIZ/World Bank/governments

## Workflow

### Step 1: Initial Scan
Read the entire RFP_TEXT to understand:
- Donor/buyer identity
- Program objectives
- Geographic scope
- Thematic focus
- Instrument type (grant, contract, consultancy, prize, etc.)

### Step 2: Structured Extraction
Extract information into 11 required sections (see Output Format below).
For each section:
- Use only information explicitly stated in the RFP
- If information is missing, write "NOT SPECIFIED"
- Flag ambiguities that need clarification

### Step 3: Compliance Analysis
- Identify mandatory vs. optional requirements
- Flag potential disqualification risks
- Note formatting, submission, and procedural rules

### Step 4: Strategic Assessment
- Assess alignment with Bitz/OpenCHS capabilities
- Identify evidence gaps
- Recommend partnership strategies
- Highlight competitive advantages

## Output Format

Produce a structured analysis with these exact headings:

### 1) Opportunity Summary
- Donor/buyer name
- Program name and reference number
- Geography (countries/regions)
- Theme (child protection, GBV, governance, AI/DPI, etc.)
- Objective (1-2 sentences)
- Instrument type (grant/contract/consultancy/prize/pilot)
- Estimated value (if stated)

### 2) Deadlines & Submission Rules
- Submission deadline (date, time, timezone)
- Q&A/clarification deadline
- Expected start date
- Submission portal/method
- Formatting rules (page limits, font, margins)
- File naming conventions
- Template requirements
- Separation rules (technical vs financial proposals)

### 3) Eligibility & Mandatory Requirements (Must-Pass)
- Entity type requirements (NGO, company, consortium, etc.)
- Required registrations or certifications
- Years in operation
- Geographic presence requirements
- Consortium/partnership rules
- Exclusions or conflicts of interest
- Previous donor experience requirements

### 4) Scope & Deliverables
- Required outputs and deliverables
- Timeline and milestones
- Reporting requirements (frequency, format)
- Staffing expectations (key personnel, expertise)
- Travel or on-site presence requirements
- Technology/platform requirements

### 5) Evaluation Criteria
List each criterion with:
- Criterion name
- Weight/points (if specified; otherwise mark "NOT SPECIFIED")
- Evaluation approach (if described)

Common criteria to look for:
- Technical quality/feasibility
- Relevant experience
- Value for money
- Innovation
- Sustainability/scalability
- Safeguarding/risk management
- Monitoring & evaluation approach
- Team qualifications

### 6) Budget & Financial Rules
- Budget ceiling (max amount)
- Currency
- Allowed cost categories
- Disallowed/ineligible costs
- Co-financing requirements
- Payment terms/schedule
- Budget format requirements
- Audit or financial reporting requirements

### 7) Required Attachments / Annexes
List all mandatory and optional attachments:
- Technical proposal template
- Budget template
- CV format requirements
- Company registration documents
- Past performance references
- Financial statements
- Legal declarations
- Safeguarding policies
- Data protection policies
- Other annexes

### 8) Compliance Traps & Risks
Top 10 reasons the proposal could be:
- Disqualified outright
- Scored poorly
- Delayed or rejected

Include:
- Formatting violations
- Missing mandatory documents
- Eligibility failures
- Budget ceiling violations
- Deadline misses
- Template non-compliance

### 9) Alignment to Bitz/OpenCHS

**Strong Alignments:**
- Areas where our capabilities directly match requirements
- Competitive advantages (open-source, AI, multi-country experience)
- Relevant past performance

**Partial Alignments:**
- Areas requiring adaptation or partnership
- Capability gaps that can be addressed

**Gaps & Risks:**
- Requirements we cannot meet
- Geographic or technical limitations
- Competitor advantages

**Recommended Partners:**
- Types of partners needed
- Specific organizations to approach
- Consortium structure suggestions

**Evidence to Highlight:**
- Relevant case studies (OpenCHS deployments)
- Impact metrics (120K calls/month, 5 countries, etc.)
- Technical innovations (AI-assisted triage, risk detection)
- Partner endorsements (UNICEF, UNFPA, etc.)

### 10) Compliance Matrix

Create a table with these columns:

| Requirement | Evidence We Have | Evidence Needed | Owner | Risk (H/M/L) | Notes |
|------------|------------------|-----------------|-------|--------------|-------|
| [Each mandatory requirement] | [Existing assets] | [Gaps to fill] | [Team member] | [Risk level] | [Action items] |

Include rows for:
- All eligibility requirements
- All mandatory attachments
- All evaluation criteria
- Budget compliance
- Submission compliance

### 11) Drafting Plan

**Suggested Outline:**
- Recommended proposal structure based on RFP requirements
- Section order that maximizes evaluator impact

**What to Write First:**
- Priority sections requiring most research
- Dependencies (what needs to be done before what)

**Key Win Themes:**
- Top 3-5 strategic messages to emphasize
- Differentiators vs. likely competitors
- Risk mitigation narratives

**Top 10 Questions:**
Questions to ask internally:
- Information gaps for proposal team
- Evidence/data needed
- Partnership decisions

Questions to ask the donor (if Q&A allowed):
- Ambiguities in RFP
- Clarifications needed
- Process questions

## Quality Checks

Before finalizing output:
- ✅ All 11 sections completed
- ✅ No invented information (only what's in RFP)
- ✅ All "NOT SPECIFIED" items flagged
- ✅ Compliance matrix has all mandatory items
- ✅ Risk assessment is realistic
- ✅ Alignment analysis is honest (gaps acknowledged)

## Constraints & Rules

**DO:**
- Extract only what is explicitly stated in the RFP
- Flag ambiguities and missing information
- Provide actionable compliance guidance
- Be realistic about alignment and gaps
- Use bullet points and tables for scannability

**DO NOT:**
- Invent details not in the RFP
- Make assumptions about unstated requirements
- Overstate organizational capabilities
- Provide legal or financial advice
- Guarantee compliance or win probability

## Example Usage

**Input:**
```
RFP_TEXT: [Paste UNICEF Call for Proposals for AI-powered child helpline system]
ORG_CONTEXT: Bitz/OpenCHS (default)
```

**Output:**
[Complete 11-section analysis with tables and action items]

## Failure Modes

If the RFP is:
- **Incomplete**: Note missing sections and request full document
- **In foreign language**: Request translation or note language barrier
- **Too vague**: Flag areas requiring donor clarification
- **Outside expertise**: Note misalignment and suggest not pursuing

## Related Skills

Use this skill as the foundation for:
- `grant-proposal-drafter` (uses this analysis to write proposal)
- `grant-quality-evaluator` (checks compliance against this analysis)
- `grant-opportunity-matcher` (uses criteria to score fit)

---

**Created for:** Bitz IT Consulting Ltd / OpenCHS  
**Version:** 1.0  
**Last Updated:** February 2026
