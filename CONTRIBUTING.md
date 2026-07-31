# Contributing to Jai Kisan, Jai Javan

Welcome! This repository is a collaborative policy document for implementing FCI-based military rations. Contributions from stakeholders, researchers, and implementers are encouraged.

---

## How to Contribute

### 1. Report Issues
Found a gap, inconsistency, or calculation error?

**Labels:**
- `v1.0-issue` — Problem with current version
- `pilot-feedback` — Findings from pilot trials
- `scaling-concern` — Implementation challenges
- `farmer-impact` — Agricultural/cooperative feedback
- `military-coordination` — Army/IAF/Navy input
- `financial-adjustment` — Cost model updates

### 2. Submit Findings
Share data from pilots, trials, or implementation:

**Pilot trial results:**
```
File: ANALYSIS/pilot_results_[base_name]_[date].md
Include: Unit location, product variant, soldiers surveyed, 
         acceptance rate, quality feedback, recommendations
```

**Farmer feedback:**
```
File: STAKEHOLDER_BRIEF/farmer_feedback_[state]_[date].md
Include: State, cooperative/FPO name, income impact, 
         any supply chain issues, requests for product variants
```

**Quality audit data:**
```
File: RESEARCH/quality_audit_[mill_location]_[date].md
Include: Batch ID, testing results, variance from specs, 
         issues found, corrective actions
```

### 3. Suggest Improvements
Regional variants, sourcing optimizations, process streamlining?

**Product variants:**
```
File: PRODUCTS/variant_[region]_[product]_[date].md
Include: Regional preference, nutritional specs, cost impact,
         trial results (if available)
```

**Sourcing improvements:**
```
File: SOURCING_CHANNELS/optimization_[channel]_[date].md
Include: Current process, bottleneck, proposed solution, cost/benefit
```

### 4. Update Financial Projections
New commodity prices, revised estimates, or variance data?

**File:** FINANCIAL/updates_[category]_[date].md  
**Include:** Old assumption, new data, impact on projections, date source

### 5. Add State/Regional Coordination Data
Successfully negotiated a state MOU or APMC coordination?

**File:** GOVERNANCE/[state]_coordination_[date].md  
**Include:** State, contacts, MOU status, challenges, recommendations

---

## Contribution Guidelines

### Do's ✅
- ✅ Keep contributions factual and data-backed
- ✅ Reference sources (mil procurement orders, farmer income data, etc.)
- ✅ Use clear, professional language
- ✅ Link to related sections in existing docs
- ✅ Maintain "Jai Kisan, Jai Javan" principle (farmer + soldier support)
- ✅ Respect confidentiality (no personnel names in feedback)
- ✅ Suggest concrete solutions, not just problems

### Don'ts ❌
- ❌ No vendor/private company promotions (this is government ration strategy)
- ❌ No political commentary (stay apolitical, focus on policy merit)
- ❌ No claims without data (pilot results, audit reports, etc.)
- ❌ No confidential military operational details
- ❌ No personal/financial interests (declare conflicts if any)

---

## Process

### For Minor Updates (typos, clarifications)
1. Fork → Edit → Pull Request
2. Include rationale in PR description
3. Request review from @defense-procurement
4. Merge after approval

### For Major Additions (new findings, implementation learnings)
1. Create GitHub Issue first (describe contribution)
2. Discuss with maintainers
3. Fork → Create feature branch (`feature/pilot-results-army-north`)
4. Add detailed markdown file + update README index if needed
5. Submit PR with reference to Issue
6. Coordinate review with stakeholders (state, FCI, military if relevant)
7. Merge after consensus

### For Sensitive Contributions (military security, farmer privacy)
1. Submit via `defense-procurement@gov.in` (confidential)
2. Maintainer will evaluate for public/redacted release
3. Anonymous submission option available

---

## File Naming Convention

```
[category]_[subcategory]_[detail]_[date].md

Examples:
  ANALYSIS/pilot_results_army_north_sep2026.md
  RESEARCH/quality_audit_kanpur_mill_oct2026.md
  STAKEHOLDER_BRIEF/farmer_feedback_maharashtra_aug2026.md
  SOURCING_CHANNELS/apmc_optimization_indore_jul2026.md
  GOVERNANCE/punjab_board_mou_status_jul2026.md
```

---

## Content Standards

### Markdown Format
- Use H2 (##) for main sections, H3 (###) for subsections
- Include data tables where applicable
- Reference related files with [links](../path/to/file.md)
- Add a "Date prepared" at bottom of each contribution

### Data Requirements
- Claims must be supported by data (quotes, cites, trial results)
- Financial figures require source (budget documents, audits, etc.)
- Farmer data requires state/cooperative verification
- Military feedback requires unit/command verification

### Length Guidelines
- Pilot results: 1–3 pages (summarize, link to detailed appendix if >3 pgs)
- Feedback: 0.5–1 page (concise, actionable)
- Findings: 2–5 pages (context + data + recommendations)
- Updates: 0.5–2 pages (what changed, why, impact)

---

## Review Process

### Timeline
- **Submission:** Add via PR or email
- **Initial review:** 1 week (format, completeness check)
- **Stakeholder review:** 1–2 weeks (relevant agencies)
- **Merge/publication:** Within 3 weeks of submission

### Review Checklist
- [ ] Contribution follows guidelines
- [ ] Data is factual and sourced
- [ ] Conflicts of interest disclosed (if any)
- [ ] Sensitive information redacted (if needed)
- [ ] Aligns with "Jai Kisan, Jai Javan" principles
- [ ] No party/vendor bias
- [ ] Links updated in README/index if new section added

---

## Recognition

Contributors will be acknowledged:
- **Acknowledged section** in CHANGELOG.md (with permission)
- **GitHub contributor badge** (auto-tracked)
- **Annual report** to Defense Procurement Committee

---

## Questions?

**Policy questions:** defense-procurement@gov.in  
**Technical repo issues:** GitHub Issues  
**Farmer coordination:** nafed-coordination@gov.in  
**State partnerships:** state-agriculture@gov.in  

---

## License

All contributions are assumed to be MIT-licensed and will be published on GitHub for public government use. If you have specific licensing preferences, note in your submission.

---

**Thank you for strengthening this strategy for India's farmers and soldiers!**

**Jai Kisan, Jai Javan** 🌾⚔️
