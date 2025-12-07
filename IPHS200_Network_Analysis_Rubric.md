# IPHS 200: Network Analysis Assignment

## Overview

You will analyze the social network of a screenplay using computational methods, then interpret what the network structure reveals about narrative.

**All analysis questions are embedded in the notebook.** Look for cells marked with 📊.

---

## What You Submit (3 Files)

| File | Naming Convention | Description |
|------|-------------------|-------------|
| **Notebook** | `LastName_FirstName_NetworkAnalysis.ipynb` | Run all cells with YOUR data (not Barbie demo) |
| **Data** | `LastName_FirstName_copresence.csv` + `LastName_FirstName_dialogue.csv` | Your edge lists |
| **Analysis** | `LastName_FirstName_Analysis.pdf` | Answers to all 13 questions + 3 arguments |

---

## The 13 Questions (All Required)

### Session 1: Co-Presence Network

| # | Question | What to Include |
|---|----------|-----------------|
| 1 | **Global Metrics** | Interpret transitivity and average path length for YOUR network |
| 2 | **Top Characters** | Top 3 in Strength, Betweenness, Closeness, Eigenvector—what each reveals |
| 3 | **Metric Divergences** | 2+ characters high in one metric, low in another—explain significance |
| 4 | **Communities** | List each community, what unites members, who bridges between them |
| 5 | **Network Topology** | Identify shape (hub-spoke, barbell, core-periphery, etc.) with evidence |
| 6 | **Narrative Backbone** | What disappeared in filtered view? What are the thickest edges? |
| 7 | **Bridge Characters** | Who has largest nodes in Viz 3? What do they connect? |

### Session 2: Dialogue Network

| # | Question | What to Include |
|---|----------|-----------------|
| 8 | **Dialogue Patterns** | Identify the hub, driver, balanced characters, high-eigenvector outliers |
| 9 | **Arrow Patterns** | Characters with many in-arrows, out-arrows, asymmetric relationships |
| 10 | **Scatter Plot** | Who's above/below the diagonal? What does position reveal? |

### Session 3: Synthesis (Three Arguments)

| # | Argument Type | Structure |
|---|---------------|-----------|
| 11 | **Topology Argument** | Claim → Visual evidence → Quantitative evidence → Interpretation |
| 12 | **Divergence Argument** | Character → Divergent metrics → Visual + quantitative proof → Meaning |
| 13 | **Asymmetry Argument** | Relationship → Direction of imbalance → Evidence → Narrative significance |

---

## Grading Rubric (100 points)

| Component | Points | Criteria |
|-----------|--------|----------|
| **Notebook Execution** | 10 | All cells run, outputs visible, YOUR data loaded (not demo) |
| **Data Quality** | 10 | Proper CSV format, consistent character names, reasonable weights |
| **Q1–3: Metrics** | 15 | All metrics interpreted with specific values; divergences identified |
| **Q4–5: Structure** | 10 | Communities explained; topology correctly identified with evidence |
| **Q6–7: Visuals** | 10 | Backbone analysis complete; bridge characters identified |
| **Q8–10: Dialogue** | 15 | All patterns identified; scatter plot interpreted correctly |
| **Arguments 1–3** | 25 | Three complete arguments with claim + visual + quantitative + interpretation |
| **Writing Quality** | 5 | Clear prose, organized structure, metrics cited precisely |
| **TOTAL** | **100** | |

---

## What "Complete" Looks Like

### ❌ Incomplete (loses points)
> "Hamlet has high betweenness."

### ✅ Complete (full credit)
> "Hamlet has betweenness of 0.58 (highest in network). In Visualization 3, his node is the largest and positioned between the red cluster (Danish court) and blue cluster (supernatural realm). This proves he's the essential bridge enabling plot transitions between political and metaphysical storylines—without him, these worlds remain disconnected."

**The formula:** Specific metric value + Visual observation + Narrative interpretation

---

## Common Mistakes

| Mistake | How to Avoid |
|---------|--------------|
| Submitting with Barbie data | Replace data in Cell 2 with YOUR screenplay |
| "High betweenness" without numbers | Always cite: "betweenness of 0.45" |
| Describing graphs without meaning | Don't just say "I see clusters"—explain what they MEAN |
| Claims without evidence | Every claim needs visual + quantitative support |
| Skipping questions | All 13 are required |
| Missing visualizations in PDF | Embed all 5 graphs |

---

## Argument Structure Template

Use this structure for Arguments 1–3:

```
CLAIM: [One sentence stating your argument]

VISUAL EVIDENCE: In Visualization [#], I observe [specific pattern]. 
[Character X] is positioned [where] relative to [what].

QUANTITATIVE EVIDENCE: From the [which] table, [Character X] has 
[metric] of [value], which is [comparison to others].

INTERPRETATION: This reveals that [narrative significance]. 
The network structure proves [connection to story/theme/character].
```

---

## Quick Reference: What Each Metric Means

| Metric | Measures | High Value Means |
|--------|----------|------------------|
| **Strength** | Total edge weight | Lots of screen time / presence |
| **Betweenness** | Shortest paths through node | Bridge between communities |
| **Closeness** | Average distance to all others | Central, can reach everyone quickly |
| **Eigenvector** | Connection to important nodes | Knows important people |
| **In-Degree** | Arrows pointing IN | Spoken TO often (attention object) |
| **Out-Degree** | Arrows pointing OUT | Speaks TO others (initiator) |
| **In/Out Ratio** | In ÷ Out | >1 = receives attention; <1 = seeks attention |

---

## Checklist Before Submitting

- [ ] Downloaded notebook and opened in Colab/Jupyter
- [ ] Created my own co-presence and dialogue CSVs
- [ ] Replaced demo data in Cell 2 with my data
- [ ] Ran all cells (Runtime → Run all)
- [ ] Verified my character names appear in outputs
- [ ] Answered ALL 13 questions in PDF
- [ ] Included specific numbers from tables
- [ ] Described what I SEE in each visualization
- [ ] Embedded all 5 visualizations in PDF
- [ ] Wrote 3 complete arguments with full evidence
- [ ] Named files correctly
- [ ] Submitted all 3 files

---

## Getting Help

**Technical issues** (notebook won't run, data won't load):
- Check CSV format: `Source,Target,Weight` header required
- Check character name consistency across both files
- Come to office hours with notebook open

**Interpretation questions** (metrics confusing, can't find patterns):
- Re-read the Interpretation sections after each code cell
- Look at BOTH the table AND the graph together
- Ask: "What's surprising here? What doesn't match expectations?"

---

*The notebook contains everything you need. Follow the 📊 questions and provide thorough answers with evidence.*
