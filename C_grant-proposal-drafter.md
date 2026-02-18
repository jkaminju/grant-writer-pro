---
name: grant-proposal-drafter
description: Draft compliant grant proposals for Bitz IT Consulting / OpenCHS using analyzed RFP requirements and MVPP intake. Generates structured narratives with donor-appropriate tone, evidence placeholders, and compliance to formatting rules.
---

# Grant Proposal Drafter

## Purpose
Generate complete, compliant grant proposal drafts based on analyzed RFP requirements and organizational inputs. Adapts structure and tone to donor type (UNICEF/UNFPA/GIZ, World Bank, foundations). Designed for humanitarian technology proposals in child protection, GBV, PSEA, and governance sectors.

## Inputs Required

### From grant-requirements-analyzer skill:
- Opportunity Summary
- Evaluation Criteria
- Scope & Deliverables  
- Budget rules
- Required structure/format

### From user (MVPP - Minimum Viable Proposal Pack):
1. **Project Title** (working title)
2. **Problem Statement** (context, scale, urgency)
3. **Proposed Solution** (what we'll do, how it works)
4. **Target Beneficiaries** (who, how many, where)
5. **Geographic Scope** (countries, regions, sites)
6. **Timeline** (duration, key milestones)
7. **Budget Estimate** (total, major categories)
8. **Team** (key personnel, expertise)
9. **Past Performance** (relevant projects, results)
10. **Partners** (confirmed or proposed)
11. **Evidence/Data** (impact metrics, case studies)
12. **Innovation/Differentiation** (what's unique)

### Nice-to-Have Inputs:
- Theory of Change
- Risk mitigation strategies
- Sustainability/scalability plan
- M&E framework
- Safeguarding approach
- Data protection measures
- Interoperability standards
- Government ownership plan

## Workflow

### Step 1: Determine Donor Type & Structure

**UNICEF/UNFPA/GIZ-style grants:**
- Narrative: 15-25 pages
- Structure: Problem → Solution → Impact → Implementation → Team → Budget
- Tone: Evidence-based, child-centered, systems-strengthening
- Emphasis: Safeguarding, interoperability, government ownership

**World Bank / Government consultancies:**
- Narrative: Technical proposal (10-20 pages) + Financial proposal (separate)
- Structure: Understanding of ToR → Methodology → Workplan → Team → Past Performance
- Tone: Professional, methodology-focused, risk-aware
- Emphasis: Value for money, local capacity, compliance

**Foundations (DRK-style):**
- Narrative: 2-5 page executive summary
- Structure: Problem → Solution → Evidence → Team → Budget (concise)
- Tone: Innovation-focused, scalable, sustainable
- Emphasis: Theory of change, earned income, sustainability

### Step 2: Generate Section-by-Section

For each required section:
1. Check RFP requirements (word limits, specific questions)
2. Pull relevant MVPP inputs
3. Apply appropriate donor template
4. Insert [PLACEHOLDER] tags for missing evidence
5. Include section-specific guidance notes

### Step 3: Apply Quality Standards

**For all sections:**
- Use active voice and clear language
- Lead with outcomes, not activities
- Quantify where possible
- Cite evidence with [SOURCE NEEDED] if unavailable
- Address evaluation criteria explicitly
- Flag donor pitfalls to avoid

### Step 4: Insert Compliance Markers

Add notes for:
- [WORD COUNT: current/limit]
- [EVIDENCE NEEDED: description]
- [PARTNER INPUT REQUIRED: topic]
- [BUDGET ALIGNMENT CHECK]
- [FORMATTING NOTE: requirement]

## Output Format

### Cover Page
- Proposal title
- Donor name and program
- Submitted by: Bitz IT Consulting Ltd / OpenCHS
- Submission date
- [Add donor-required cover page elements]

### Executive Summary (1-2 pages)
- Problem (2-3 sentences)
- Solution (2-3 sentences)
- Expected impact (key metrics)
- Budget summary
- Timeline
- Why Bitz/OpenCHS (competitive advantage)

### Section 1: Problem Statement / Background
**UNICEF/UNFPA/GIZ version:**
- Current situation (statistics, evidence)
- Root causes analysis
- Consequences of inaction
- Alignment with donor priorities
- [EVIDENCE NEEDED: country-specific VAC/GBV data]

**World Bank version:**
- Understanding of the ToR
- Context analysis
- Challenges and constraints
- Opportunities for improvement

**Foundation version:**
- Problem in 1 paragraph
- Scale and urgency
- Why now

### Section 2: Proposed Solution / Methodology
**All versions include:**
- What we will do (activities)
- How we will do it (approach, methodology)
- Why this approach (evidence, best practices)
- Innovation and differentiation
- Technology stack (if applicable)

**For OpenCHS-style projects:**
- Platform overview (open-source, interoperable)
- AI/automation capabilities
- Case management workflow
- Multi-channel support (phone, SMS, chat, web)
- Data security and privacy
- Offline functionality
- Integration approach

**Include:**
- Theory of Change diagram [DIAGRAM NEEDED]
- User journey or workflow [VISUAL NEEDED]
- Technical architecture [if tech project]

### Section 3: Expected Results / Impact
- Primary outcomes (aligned to donor objectives)
- Secondary outcomes
- Beneficiary reach (numbers, demographics)
- Impact measurement approach
- Evidence of past impact [INSERT: OpenCHS metrics]
  - Example: "In current deployment across 5 countries, OpenCHS processes 120,000 calls monthly, saving counselors 16,000 hours through AI-assisted documentation"

### Section 4: Implementation Plan / Workplan
**Phases and timeline:**
| Phase | Activities | Duration | Deliverables | Responsible |
|-------|-----------|----------|--------------|-------------|
| Inception | [activities] | Month 1 | [deliverables] | [team role] |
| Development | [activities] | Month 2-6 | [deliverables] | [team role] |
| Pilot | [activities] | Month 7-9 | [deliverables] | [team role] |
| Scale-up | [activities] | Month 10-12 | [deliverables] | [team role] |

**Risk Management:**
| Risk | Likelihood | Impact | Mitigation |
|------|-----------|--------|------------|
| [Risk 1] | [H/M/L] | [H/M/L] | [Strategy] |

### Section 5: Team and Governance
**Key Personnel:**
- Project Director: [Name, qualifications, relevant experience]
- Technical Lead: [Name, expertise]
- M&E Specialist: [Name]
- Safeguarding Focal Point: [Name]

**For each person:**
- Role and responsibilities (20%)
- Relevant qualifications
- Past performance on similar projects
- [CV ATTACHED: filename]

**Governance:**
- Reporting structure
- Decision-making process
- Stakeholder engagement plan
- Quality assurance approach

### Section 6: Partnerships and Collaboration
- Confirmed partners (MOUs attached)
- Proposed partners (letters of intent)
- Partner roles and value-add
- Consortium arrangements (if applicable)
- Government coordination plan
- Local capacity strengthening

### Section 7: Monitoring, Evaluation & Learning
- M&E framework aligned to donor requirements
- Key indicators (output, outcome, impact)
- Data collection methods
- Baseline and targets
- Reporting frequency and format
- Learning agenda and adaptation

### Section 8: Safeguarding and Responsible AI
**Standard for all proposals:**
- Child safeguarding policy [ATTACH: policy document]
- PSEA commitment
- Data protection and privacy measures
- Informed consent protocols
- Confidentiality safeguards
- AI ethics and responsible use
- Bias mitigation in algorithms
- Human oversight and escalation
- Grievance mechanisms

### Section 9: Sustainability and Scalability
- Post-project sustainability plan
- Government ownership transition
- Local capacity building
- Revenue or cost-recovery model (if applicable)
- Open-source sustainability
- Scalability pathways (geographic, thematic)

### Section 10: Budget Narrative
- Budget summary table
- Justification for major cost categories
- Value for money demonstration
- Co-financing (if applicable)
- [DETAILED BUDGET ATTACHED separately]

### Annexes Checklist
- [ ] Detailed budget (Excel template)
- [ ] CVs of key personnel
- [ ] Company registration
- [ ] Past performance references (3-5)
- [ ] Letters of support/partnership
- [ ] Safeguarding policy
- [ ] Data protection policy
- [ ] Technical specifications (if applicable)
- [ ] Other donor-required forms

## Donor-Specific Boilerplate

### For UNICEF/UNFPA proposals:
**Safeguarding paragraph:**
"Bitz IT Consulting and OpenCHS are committed to the highest standards of child safeguarding and PSEA. Our comprehensive safeguarding policy [ATTACH] includes mandatory background checks, code of conduct, reporting mechanisms, and zero-tolerance for abuse. All staff complete safeguarding training and sign the code of conduct. The OpenCHS platform includes built-in safeguarding features such as [list features]."

**Interoperability paragraph:**
"OpenCHS is built on open standards and open-source principles to ensure interoperability and government ownership. The platform adheres to [list standards: FHIR, HL7, etc.]. All data structures and APIs are documented and accessible, enabling seamless integration with national systems such as [examples]. This approach ensures sustainability beyond donor funding and supports country-led digital public infrastructure."

### For World Bank proposals:
**Local content paragraph:**
"Our implementation approach prioritizes local capacity strengthening and knowledge transfer. [X%] of the project team will be locally recruited. We will conduct [number] training sessions for government counterparts and establish a sustainability plan for post-project operations. All source code and documentation will be transferred to [government entity] with full technical support during the transition period."

### For Foundation proposals:
**Innovation paragraph:**
"OpenCHS represents a paradigm shift from traditional helpline operations. By applying AI to automate documentation, we free counselors to focus on survivor care—reducing documentation time by 60% while improving data quality by 40%. This innovation is both scalable (already deployed across 5 countries) and sustainable (open-source model eliminates vendor lock-in)."

## Section Swap List by Donor Type

**If UNICEF/UNFPA/GIZ → Include:**
- Child safeguarding (detailed)
- Interoperability standards
- Government coordination
- Multi-country considerations

**If UNICEF/UNFPA/GIZ → De-emphasize:**
- Commercial revenue models
- Proprietary technology
- Short-term pilot thinking

**If World Bank/Government → Include:**
- Value for money analysis
- Local content and capacity
- Procurement compliance
- Risk management (detailed)

**If World Bank/Government → De-emphasize:**
- Innovation for innovation's sake
- Unproven methodologies

**If Foundation (DRK-style) → Include:**
- Earned revenue potential
- Scalability pathways
- Exit/sustainability strategy
- Systems change vision

**If Foundation → De-emphasize:**
- Government bureaucracy details
- Overly technical specifications

## Quality Checks

Before finalizing:
- ✅ All RFP questions answered
- ✅ Word limits respected (±5%)
- ✅ All evaluation criteria addressed
- ✅ No unsupported claims
- ✅ All [PLACEHOLDERS] marked for follow-up
- ✅ Consistent tone throughout
- ✅ Numbers add up (budget matches narrative)
- ✅ No jargon without explanation
- ✅ Active voice, clear language
- ✅ Visuals referenced where needed

## Constraints & Rules

**DO:**
- Follow RFP structure exactly if specified
- Use evidence from past OpenCHS performance
- Acknowledge gaps honestly (with mitigation)
- Keep language clear and accessible
- Quantify wherever possible

**DO NOT:**
- Exceed word/page limits
- Make unsupported claims
- Copy-paste without adaptation
- Ignore donor-specific requirements
- Overpromise on timeline or budget

## Example Output Structure

For a UNICEF child protection grant:
```
1. Executive Summary (1 page)
2. Problem Statement (3 pages) - VAC context, statistics, gaps
3. Proposed Solution (5 pages) - OpenCHS platform, AI features, implementation
4. Expected Impact (3 pages) - Beneficiaries, outcomes, measurement
5. Implementation Plan (4 pages) - Timeline, risks, workplan
6. Team (2 pages) - Key personnel, expertise
7. Partnerships (2 pages) - Government, UNICEF coordination
8. M&E (2 pages) - Framework, indicators
9. Safeguarding (1 page) - Policies, AI ethics
10. Sustainability (2 pages) - Government ownership, open-source
11. Budget Narrative (1 page)
Total: 25 pages + annexes
```

## Failure Modes & Recovery

**If MVPP inputs are incomplete:**
- Generate draft with [INPUT NEEDED: description] tags
- Prioritize which inputs are critical vs. nice-to-have
- Suggest where to find missing information

**If RFP requirements conflict:**
- Flag the conflict
- Propose resolution
- Ask for user decision

**If word limit is insufficient:**
- Prioritize highest-scored evaluation criteria
- Move details to annexes
- Create executive summary approach

## Related Skills

This skill works with:
- `grant-requirements-analyzer` (provides RFP analysis)
- `grant-quality-evaluator` (reviews this draft)
- Uses output from both to iterate

---

**Created for:** Bitz IT Consulting Ltd / OpenCHS  
**Version:** 1.0  
**Last Updated:** February 2026
