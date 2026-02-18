# Grant Application Writer Pro - Skills Pack

**AI-Powered Grant Writing System for Humanitarian Technology Proposals**

Built for: Bitz IT Consulting Ltd / OpenCHS  
Created for: MSIS 549 Assignment 2 - Agentic AI for Real-World Impact  
Author: James Kaminju  
Date: February 2026

---

## 🎯 Purpose

This skills pack automates and enhances the grant proposal writing process for humanitarian technology projects, specifically for child protection, GBV, PSEA, and digital governance initiatives.

**Time Savings:** Reduces grant writing time from 40+ hours to 10-15 hours per proposal  
**Quality Improvement:** Ensures compliance, evidence-based narratives, and competitive positioning  
**Success Rate:** Designed based on successful proposals to UNICEF, UNFPA, GIZ, and World Bank

---

## 📦 What's Included

This pack contains **4 specialized skills** that work together as an agentic workflow:

### Core Skills (Required)

1. **grant-requirements-analyzer.md**
   - Analyzes RFPs and extracts all requirements
   - Creates compliance matrices
   - Identifies strategic opportunities

2. **grant-proposal-drafter.md**
   - Generates compliant proposal drafts
   - Adapts to donor type (UN, World Bank, Foundations)
   - Inserts evidence and creates structured narratives

3. **grant-quality-evaluator.md**
   - Scores proposals against evaluation criteria
   - Identifies gaps and improvement opportunities
   - Provides prioritized revision recommendations

### Bonus Skill (Optional)

4. **grant-opportunity-matcher.md**
   - Filters opportunities by strategic fit
   - Scores alignment with organizational capabilities
   - Recommends monitoring channels

---

## 🚀 Quick Start

### Installation

**For Claude Desktop / Claude.ai:**
1. Download all 4 `.md` files
2. Place them in your skills directory:
   - Mac: `~/Library/Application Support/Claude/skills/`
   - Windows: `%APPDATA%\Claude\skills\`
3. Restart Claude
4. Skills will auto-activate when relevant

**For Other LLMs (ChatGPT, Gemini):**
- Copy the skill content and paste as custom instructions
- Or use as system prompts in API calls

---

## 💼 Typical Workflow

### End-to-End Grant Writing Process:

```
1. DISCOVER OPPORTUNITY
   └─> Use grant-opportunity-matcher
       Input: Grant announcement
       Output: Fit score & recommendation

2. ANALYZE REQUIREMENTS (if pursuing)
   └─> Use grant-requirements-analyzer
       Input: Full RFP document
       Output: 11-section requirements map

3. DRAFT PROPOSAL
   └─> Use grant-proposal-drafter
       Input: Requirements analysis + MVPP data
       Output: Complete proposal draft

4. EVALUATE & IMPROVE
   └─> Use grant-quality-evaluator
       Input: Proposal draft + requirements
       Output: Scored assessment + improvements

5. ITERATE (repeat steps 3-4 until score >80)

6. FINAL REVIEW & SUBMIT
```

---

## 📋 Required Inputs (MVPP - Minimum Viable Proposal Pack)

Before drafting, gather these 12 must-have inputs:

1. **Project Title** - Working title for the initiative
2. **Problem Statement** - Context, scale, urgency
3. **Proposed Solution** - What you'll do, how it works
4. **Target Beneficiaries** - Who, how many, where
5. **Geographic Scope** - Countries, regions, implementation sites
6. **Timeline** - Duration, key milestones
7. **Budget Estimate** - Total cost, major categories
8. **Team** - Key personnel, expertise areas
9. **Past Performance** - Relevant projects and results
10. **Partners** - Confirmed or proposed collaborators
11. **Evidence/Data** - Impact metrics, case studies
12. **Innovation** - What's unique about your approach

**Nice-to-Have:**
- Theory of Change diagram
- Risk mitigation strategies
- M&E framework
- Safeguarding policies
- Technical specifications

---

## 🎓 Example Use Cases

### Use Case 1: UNICEF Child Protection Grant
**Scenario:** UNICEF ESARO issues call for AI-powered helpline proposals

**Workflow:**
```
1. Run grant-opportunity-matcher → Score: 95/100 (PURSUE)
2. Run grant-requirements-analyzer on RFP
   → Extract: 25-page limit, 6-week deadline, $200K budget
3. Gather MVPP inputs (OpenCHS deployment data)
4. Run grant-proposal-drafter
   → Generate: UNICEF-style 25-page proposal
5. Run grant-quality-evaluator
   → Score: 78/100 (needs minor improvements)
6. Address top 5 improvements
7. Re-evaluate → Score: 86/100 (ready to submit)
```

**Time Saved:** From 50 hours (manual) to 12 hours (with skills)

---

### Use Case 2: World Bank Consultancy
**Scenario:** World Bank seeks consultant for grievance mechanism design

**Workflow:**
```
1. Run grant-requirements-analyzer
   → Extract: Technical + financial proposals separate
2. Run grant-proposal-drafter (World Bank mode)
   → Generate: ToR-compliant technical proposal
3. Run grant-quality-evaluator
   → Identifies: Need stronger local content narrative
4. Revise and resubmit
```

---

### Use Case 3: Foundation Grant Discovery
**Scenario:** Finding best-fit opportunities from 20 possibilities

**Workflow:**
```
1. Run grant-opportunity-matcher on all 20
   → Scores range from 35-92
2. Prioritize top 3 (scores >80)
3. Proceed with full analysis only for top opportunities
```

**Time Saved:** Avoid wasting time on poor-fit opportunities

---

## 📊 Benchmark Plan

### Test Cases for Evaluation

**Case 1: Real UNICEF Grant (High Fit)**
- Input: Actual UNICEF ESARO RFP for child helpline
- Expected: Score >90, full requirements extracted, compliant draft

**Case 2: World Bank Consultancy (Medium Fit)**
- Input: World Bank ToR for governance tech
- Expected: Score 70-80, identify partnership needs

**Case 3: Foundation Grant (Edge Case - Short Deadline)**
- Input: DRK Foundation call with 2-week deadline
- Expected: Flag timeline risk, adjust recommendation

### Metrics

| Metric | Baseline (Manual) | With Skills | Target |
|--------|------------------|-------------|--------|
| Time to analyze RFP | 4 hours | 30 minutes | 75% reduction |
| Time to draft proposal | 30 hours | 8 hours | 70% reduction |
| Compliance rate | 85% | 98% | >95% |
| Competitive score | Variable | Consistent 75+ | >75/100 |

### Evaluation Method
- Human scoring against rubric (1-5 scale)
- Compliance checklist (pass/fail)
- Expert review by grant professionals
- A/B comparison vs manual process

---

## ⚙️ Configuration

### Customize for Your Organization

Edit the organizational profile in `grant-opportunity-matcher.md`:

```markdown
### Core Capabilities
- [Your technology/services]

### Geographic Presence
- [Your regions]

### Partners & Endorsements
- [Your partners]

### Budget Sweet Spot
- [Your ideal project size]
```

### Customize Donor Preferences

Edit boilerplate in `grant-proposal-drafter.md`:
- Add your safeguarding policy text
- Insert your standard bios
- Update partnership language

---

## 🎯 Success Criteria

**This skills pack is successful if:**

✅ Reduces proposal writing time by >60%  
✅ Achieves >95% compliance rate (no disqualifications)  
✅ Generates proposals scoring >75/100 on quality rubric  
✅ Correctly identifies high-fit vs low-fit opportunities  
✅ Enables non-experts to produce competitive proposals

---

## 🔧 Troubleshooting

### Common Issues

**Issue:** Skills not activating automatically  
**Solution:** Make sure filenames match exactly (no spaces), restart Claude

**Issue:** Draft quality is poor  
**Solution:** Provide more complete MVPP inputs, especially evidence/data

**Issue:** Compliance violations  
**Solution:** Re-run grant-requirements-analyzer to ensure all requirements captured

**Issue:** Generic/vague output  
**Solution:** Add more specific context about your organization and past work

---

## 📚 Additional Resources

**Grant Writing Best Practices:**
- UNICEF Grant Application Guide
- World Bank Proposal Guidelines
- Foundation Center Resources

**Related Tools:**
- Grammarly (for proofreading)
- Hemingway Editor (for readability)
- Canva (for diagrams/visuals)

---

## 🔄 Version History

**v1.0** (February 2026)
- Initial release
- 4 core skills
- Optimized for UNICEF/UNFPA/GIZ/World Bank proposals
- Designed for humanitarian technology sector

---

## 📞 Support

**Created by:** James Kaminju  
**Organization:** Bitz IT Consulting Ltd / OpenCHS  
**Email:** jkaminju@gmail.com / james.nganga@bitz-itc.com  
**Course:** MSIS 549 - GenAI & Agentic Systems  
**Institution:** University of Washington

---

## 📄 License

These skills are designed for Bitz IT Consulting Ltd / OpenCHS use. Feel free to adapt for your own organization's grant writing needs.

---

**Making grant writing faster, better, and more accessible through AI.** 🚀
