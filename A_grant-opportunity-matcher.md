---
name: grant-opportunity-matcher
description: Filter and score grant opportunities for strategic fit with Bitz IT Consulting / OpenCHS capabilities. Monitors priority channels, applies fit rubric, and recommends high-value opportunities to pursue in child protection, GBV, PSEA, and humanitarian technology sectors.
---

# Grant Opportunity Matcher

## Purpose
Systematically evaluate grant opportunities against organizational capabilities and strategic priorities. Provides fit scores, identifies best-match opportunities, and recommends monitoring channels. Saves time by filtering out low-fit opportunities early.

## Inputs Required

### One-time setup (reusable profile):
- Organizational capabilities (auto-filled for Bitz/OpenCHS, user can override)
- Geographic priorities
- Thematic preferences
- Budget range preferences
- Strategic focus areas

### Per opportunity:
- **OPPORTUNITY_TEXT**: Grant announcement, call summary, or RFP excerpt
- **SOURCE**: Where it was found (optional, for channel tracking)

## Workflow

### Step 1: Extract Opportunity Basics
From OPPORTUNITY_TEXT, identify:
- Donor/funder name
- Program name
- Theme/sector
- Geography
- Instrument type (grant, contract, prize, etc.)
- Budget range (if stated)
- Deadline
- Eligibility criteria

### Step 2: Apply Fit Scoring Rubric
Score against weighted criteria (total: 100 points)

### Step 3: Generate Recommendation
- Pursue / Consider / Pass
- Rationale
- Next steps if pursuing

### Step 4: Track Channels (aggregate over time)
- Which sources yield high-fit opportunities
- Recommend monitoring priorities

## Bitz/OpenCHS Organizational Profile

### Core Capabilities
- **Technology:** OpenCHS platform (open-source, interoperable case management + helpline)
- **AI/Automation:** AI-assisted documentation, risk detection, triage
- **Sectors:** Child protection (VAC), GBV, PSEA, grievance mechanisms, e-governance
- **Services:** Software development, technical assistance, capacity building, M&E
- **Model:** Open-source, government ownership, systems strengthening

### Geographic Presence
- **Primary:** East Africa (Kenya, Uganda, Tanzania)
- **Secondary:** Southern Africa (Lesotho), Horn of Africa (Somalia)
- **Expansion potential:** Other Africa regions, South Asia

### Partners & Endorsements
- UNICEF ESARO (regional implementation partner)
- UNICEF Venture Fund (innovation portfolio)
- UNFPA (GBV prevention)
- GIZ (technical cooperation)
- Multiple national governments

### Team Size & Capacity
- 10-20 staff (scalable with partners)
- Can lead: $50K - $500K projects
- Can participate: Up to $2M+ (as consortium member)

### Strategic Priorities
1. Scale OpenCHS to more countries
2. Deepen AI/automation capabilities
3. Expand to adjacent sectors (education, health grievance mechanisms)
4. Strengthen government ownership and sustainability
5. Build evidence base for impact

## Fit Scoring Rubric (100 points total)

| Criterion | Weight | Scoring Guide (0-5 scale × weight) |
|-----------|--------|-------------------------------------|
| **Thematic Alignment** | 25 pts | Child protection/GBV/PSEA/governance (5), Adjacent sectors (3), Unrelated (0) |
| **Geographic Fit** | 20 pts | East/Southern Africa (5), Other Africa (4), Other regions (2) |
| **Capability Match** | 20 pts | Perfect match (5), Strong with partner (4), Stretch (2), Gap (0) |
| **Instrument Type** | 10 pts | Grant/innovation fund (5), Consultancy (4), Prize (3), Investment (2) |
| **Budget Appropriateness** | 10 pts | $50K-$500K (5), $20K-$1M (4), <$20K or >$1M (2) |
| **Timeline Feasibility** | 5 pts | >6 weeks to deadline (5), 3-6 weeks (3), <3 weeks (1) |
| **Competition Level** | 5 pts | Niche/targeted (5), Moderate (3), Highly competitive (1) |
| **Strategic Value** | 5 pts | Advances priorities (5), Neutral (3), Distracts (0) |

### Scoring Interpretation
- **90-100:** Excellent fit - Priority pursuit
- **75-89:** Strong fit - Pursue if capacity allows
- **60-74:** Moderate fit - Consider if strategic or low-effort
- **45-59:** Weak fit - Pass unless exceptional circumstances
- **<45:** Poor fit - Do not pursue

## Output Format

### OPPORTUNITY SNAPSHOT

**Opportunity:** [Program name]  
**Donor:** [Funder]  
**Theme:** [Primary sector/theme]  
**Geography:** [Countries/regions]  
**Budget:** [Range or amount]  
**Deadline:** [Date] ([X] weeks from today)  
**Instrument:** [Grant/Contract/Prize/etc.]

---

### FIT ASSESSMENT

**Overall Fit Score:** [X]/100  
**Recommendation:** 🟢 PURSUE / 🟡 CONSIDER / 🔴 PASS

**One-Sentence Summary:**
[Quick take on fit]

---

### DETAILED SCORING

#### Thematic Alignment: [X]/25
- **Primary theme:** [Extracted from opportunity]
- **Alignment:** Perfect / Strong / Partial / Weak / None
- **Rationale:** [Why score is what it is]

#### Geographic Fit: [X]/20
- **Target geography:** [Countries/regions]
- **Our presence:** Strong / Moderate / Weak / None
- **Rationale:** [Explanation]

#### Capability Match: [X]/20
- **Required capabilities:** [List from opportunity]
- **Our capabilities:** [What we have]
- **Gaps:** [What we'd need partners for]
- **Confidence:** High / Medium / Low

#### Instrument Type: [X]/10
- **Type:** [Grant/Contract/etc.]
- **Our preference:** [How it fits our model]

#### Budget Appropriateness: [X]/10
- **Budget:** [Amount]
- **Our sweet spot:** [$50K-$500K lead; up to $2M consortium]
- **Fit:** Ideal / Acceptable / Stretch

#### Timeline Feasibility: [X]/5
- **Deadline:** [Date]
- **Time to prepare:** [Weeks]
- **Feasibility:** Ample / Tight / Unrealistic

#### Competition Level: [X]/5
- **Anticipated competition:** Low / Medium / High
- **Our positioning:** Strong / Moderate / Weak

#### Strategic Value: [X]/5
- **Strategic fit:** Advances priorities / Neutral / Off-strategy
- **Which priority:** [If advances, which one]

---

### DECISION FACTORS

**✅ Reasons to Pursue:**
- [Positive factors]

**❌ Reasons to Pass:**
- [Negative factors or gaps]

**Partnership Needs:**
- [If gaps exist, what type of partners would address them]

---

### RECOMMENDATION

**🟢 PURSUE** (if score ≥75)
**Next Steps:**
1. [Immediate action - e.g., "Register by [date]"]
2. [Key information to gather]
3. [Partners to contact]
4. [Estimated prep time: X hours]

**🟡 CONSIDER** (if score 60-74)
**Conditions for pursuit:**
- [What would need to be true to justify effort]
- [Strategic considerations]

**🔴 PASS** (if score <60)
**Why passing:**
- [Primary disqualifying factors]
- [Alternative opportunities to prioritize instead]

---

### EXAMPLE OPPORTUNITIES MATCHING OUR PROFILE

Based on our capabilities and priorities, here are 12 example opportunity types we should monitor:

1. **UNICEF Innovation Fund** - AI for child protection (global, $50K-$100K)
2. **UNFPA Innovation Challenge** - GBV prevention technology (multi-country, $100K-$500K)
3. **GIZ Digital Solutions for Development** - E-governance platforms (Africa, €100K-€500K)
4. **World Bank Consultancy** - Grievance redress mechanism design (country-specific, $75K-$300K)
5. **DRK Foundation** - Tech for marginalized communities (Africa/Asia, $100K-$1M)
6. **UNICEF Country Office Grants** - OpenCHS deployment and scale-up (Kenya/Uganda/Tanzania, $50K-$200K)
7. **Bill & Melinda Gates Foundation** - Digital public infrastructure (global, $500K-$5M, consortium)
8. **Innovation for Policy Foundation** - Evidence-based governance tech (Africa, $50K-$150K)
9. **USAID DRG** - Democracy, Rights, Governance tech (regional, $100K-$500K)
10. **Africa Catalyst Fund** - Social impact ventures (Africa, $50K-$200K)
11. **Google.org Impact Challenge** - AI for social good (global, varies)
12. **Ministry Tenders** - Case management system deployment (country-specific, $50K-$500K)

---

### OPPORTUNITY CHANNELS TO MONITOR

**Top Priority Channels (check weekly):**
1. **UNICEF ESARO Opportunities Portal** - Direct access via partnership
2. **UNFPA Innovation Calls** - Regular grants in our sectors
3. **GIZ ToR Database** - Consultancy opportunities
4. **Devex / ReliefWeb** - Aggregated humanitarian opportunities
5. **Foundation Directory Online** - Private foundation grants

**Secondary Channels (check monthly):**
6. World Bank Consultancy Opportunities
7. USAID Grants.gov (filtered: Africa, child protection, GBV)
8. African Development Bank Procurement
9. Google.org / Tech for Good directories
10. DRK Foundation / Oak Foundation calls

**Monitoring Tools:**
- Set Google Alerts for: "child protection technology grant", "GBV digital solutions", "OpenCHS", "helpline case management"
- Subscribe to: UNICEF Innovation Newsletter, UNFPA Innovation Updates, GIZ Calls for Proposals
- Network monitoring: Engage with program officers at key donors

---

## Taxonomy for Opportunity Filtering

### Donor Types (Primary Keywords)
- **UN Agencies:** UNICEF, UNFPA, WHO, UNDP, UNHCR, UNOCHA
- **Bilateral:** GIZ, USAID, FCDO (UK), GAC (Canada), SIDA (Sweden)
- **Multilateral:** World Bank, African Development Bank, Asian Development Bank
- **Foundations:** Gates, DRK, Oak, Wellspring, Open Society
- **Government:** National ministries, local government, government-to-government
- **Innovation Funds:** UNICEF Venture Fund, UNFPA Innovation Fund, Africa Catalyst

### Themes (Search Keywords)
- **Child Protection:** VAC, child abuse, child helplines, 116 helpline, child safeguarding
- **GBV:** gender-based violence, SGBV, intimate partner violence, violence against women
- **PSEA:** protection from sexual exploitation and abuse, accountability to affected populations
- **Grievance:** grievance redress mechanisms, complaints mechanisms, feedback mechanisms
- **E-Services:** e-governance, digital public infrastructure, DPI, interoperability
- **Legal/Governance:** legal aid, access to justice, civic tech, transparency
- **AI/Tech:** artificial intelligence, machine learning, natural language processing, automation

### Instruments
- **Grant:** traditional grant, innovation grant, challenge fund
- **Investment:** equity, debt, recoverable grant
- **Prize:** challenge prize, innovation prize
- **Contract:** consultancy, technical assistance, fee-for-service
- **Pilot:** proof-of-concept, innovation pilot, R&D funding

### Stage
- **R&D:** research, proof-of-concept, prototype
- **Pilot:** small-scale testing, demonstration
- **Scale-up:** expansion, replication, national rollout
- **Systems Strengthening:** institutionalization, government capacity

---

## Quality Checks

Before finalizing recommendation:
- ✅ All rubric criteria scored
- ✅ Gaps and partnership needs identified
- ✅ Timeline feasibility realistic
- ✅ Recommendation aligns with score
- ✅ Next steps actionable

## Constraints & Rules

**DO:**
- Be honest about fit (even if opportunity is prestigious)
- Consider strategic value beyond immediate revenue
- Factor in opportunity cost (other opportunities)
- Recommend passing when fit is poor

**DO NOT:**
- Recommend pursuing every opportunity
- Ignore capacity constraints
- Overestimate capabilities
- Underestimate competition

## Example Usage

**Input:**
```
OPPORTUNITY_TEXT: "UNICEF ESARO seeks proposals for AI-powered child helpline systems to strengthen case management and risk detection across East Africa. Budget: $200,000. Deadline: 6 weeks."
```

**Output:**
```
OPPORTUNITY SNAPSHOT
Opportunity: AI-Powered Child Helpline Systems
Donor: UNICEF ESARO
Theme: Child Protection (VAC)
Geography: East Africa
Budget: $200,000
Deadline: [Date] (6 weeks from today)
Instrument: Grant

FIT ASSESSMENT
Overall Fit Score: 95/100
Recommendation: 🟢 PURSUE - PRIORITY

One-Sentence Summary: Perfect thematic, geographic, and capability alignment with ideal budget and timeline—this is our core offering in our primary market with our key partner.

[Full scoring breakdown follows...]

RECOMMENDATION: 🟢 PURSUE
Next Steps:
1. Confirm partnership with UNICEF ESARO by [date]
2. Gather evidence: Kenya/Uganda/Tanzania deployment stats
3. Engage local government partners for letters of support
4. Estimated prep time: 40 hours
```

---

## Related Skills

Works with:
- `grant-requirements-analyzer` (if pursuing, use this next)
- Can batch-process multiple opportunities for comparison

---

**Created for:** Bitz IT Consulting Ltd / OpenCHS  
**Version:** 1.0  
**Last Updated:** February 2026
