# PhD Daily Papers — Detailed Report Format

From 2026-09-28 onward, daily reports should focus primarily on the paper itself. Relevance to the user's project is a short final section, not the main structure.

## Required sections for each paper

### 1. Paper information
- Full title
- Authors (first author et al. is acceptable on the card; preserve full citation when practical)
- Journal
- Publication year/date
- DOI
- PMID when available
- Primary paper link
- Paper type: mechanism / method / imaging / drug / review / other

### 2. Why this paper is worth reading
1–2 concise sentences explaining the scientific importance of the paper itself.

### 3. Main scientific question
State the central question in plain scientific language.

### 4. Knowledge gap / problem
Explain what was unknown before this study and why the question mattered.

### 5. Main experimental logic
Describe the paper as a sequence of questions and experiments rather than a list of techniques. Prefer 3–6 steps. For each step include:
- Question / purpose
- Method or perturbation
- Main observation/result
- What that result establishes

### 6. Key experiments / main figures
Select the 2–4 experiments or figures that carry the paper's main argument. For each include:
- Figure number when verifiable from the primary paper
- What was tested
- Experimental system / key method
- Main result
- Why the experiment is decisive

Never invent figure numbers. If the primary full text is unavailable, say “figure number not verified” and still describe the key experiment.

### 7. Main findings / conclusions
Use 3–6 bullets. Separate directly demonstrated conclusions from broader interpretation when necessary.

### 8. Key experimental information extracted
Extract concrete reusable details when they are explicitly reported and verifiable:
- Cell line / model
- Drug or perturbation
- Concentration / dose
- Treatment time
- Stress condition
- SG / ribosome / nucleolar / nuclear-speckle markers
- Antibodies or tagged proteins when useful
- Translation assay
- Imaging modality
- Quantification metric
- Key genetic perturbations
- Important positive/negative controls
- Washout / recovery design
- Statistics when unusually important

Do not guess missing concentrations, times, antibody catalog numbers, or parameters.

### 9. Mechanistic model
If supported by the paper, give a compact causal chain, for example:
A → B → C → phenotype.
State clearly if a step is inferred rather than directly demonstrated.

### 10. Strengths and limitations
Include:
- Strongest aspect of the evidence
- Main limitation(s)
- What should not be over-interpreted

### 11. What is genuinely new
Explain in 2–4 sentences what this paper adds beyond prior knowledge.

### 12. Possible relevance to the user's project
Keep this short (about 10–15% of the report). Explain only the most direct connection.

### 13. One experiment inspired by the paper
Only one high-value experiment. Include:
- Hypothesis
- Minimal groups / perturbations
- Readout
- What alternative outcomes would mean

## Website behavior
Every paper must continue to include:
- stable `data-paper-id` (prefer PMID, otherwise DOI)
- `data-date` in YYYY-MM-DD
- topic tags
- Read checkbox
- Useful for publication checkbox

Preserve:
- Today view
- Archive view
- Useful for publication view
- Unread view
- topic filters
- localStorage state
- existing CSS/JavaScript behavior
- all previous paper entries

The homepage should stay compact. A paper may show a concise summary first with the detailed report expandable/collapsible underneath, but all required scientific content must remain accessible on the page.