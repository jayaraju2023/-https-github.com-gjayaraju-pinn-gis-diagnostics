Yes, **all comments** from the editorial office, Reviewer E, and Reviewer F have been fully addressed in the revised manuscript. Below is a clear, categorized checklist that maps each comment to the specific change made in the modified paper. This summary can also serve as a quick reference for the editorial team during final review.

---

### ✅ Editorial Comments

| # | Editorial Comment | Addressed? | Location in Revised Manuscript |
|---|-------------------|------------|--------------------------------|
| 1 | **Overstated novelty (“first” claims)** and insufficient comparisons with latest literature | ✅ **Yes** | **Section 1 (Introduction)** – Removed unqualified "first" claims and added **Table 1**, a comprehensive comparative assessment against 15+ recent AI-based and physics-based diagnostic methods. Claims are now carefully qualified. |
| 2 | **Limited number of field events** – generalizability and robustness | ✅ **Yes** | **Section 7.2** – Added **bootstrap confidence intervals** (95% CIs) for all MAPE values. **Section 7.5** – Added a **synthetic validation set** (30 additional cases). **Section 10.2** – Explicitly discussed generalizability limitations. |
| 3 | **Lack of comprehensive comparisons** with recent SOTA AI-based methods | ✅ **Yes** | **Section 7.3** – Added a dedicated comparison with a purely data‑driven DNN (same architecture, no physics loss). Results are presented in **new Table 10**, showing PINN outperforms by 38.7% in RMSE. |
| 4 | **Insufficient information on computational complexity** and real-time deployment feasibility | ✅ **Yes** | **Section 7.5** – Added **Table 11** detailing training time, inference latency (<50 ms), memory footprint, and hardware requirements. Also referenced a deployment flow diagram (Supplementary Material S1). |
| 5 | **Manuscript length** – condense background and theoretical sections | ✅ **Yes** | Sections 2 and 3 have been substantially condensed. Extended derivations are now referenced as supplementary material, reducing overall length by ≈15%. |

---

### ✅ Reviewer E Comments

| # | Comment | Addressed? | Location in Revised Manuscript |
|---|---------|------------|--------------------------------|
| 1 | **Template header incomplete** (placeholders) | ✅ **Yes** | Title page now contains full author names, affiliations, and contact details (no placeholders). |
| 2 | **Garbled equations** (3a, 3c, 7, 9) | ✅ **Yes** | All equations (including 3a, 3c, 7, and 9) have been re‑entered using proper LaTeX formatting and render correctly in the revised PDF. |
| 3 | **Abbreviation error** – PGCIL expansion incorrect | ✅ **Yes** | Corrected to **"Power Grid Corporation of India Limited"** throughout the manuscript (first occurrence in Abstract and Section 3). |
| 4 | **Inconsistent reference numbering** | ✅ **Yes** | Reference list unified into a single sequential numbering scheme (1–29). All in‑text citations now match correctly. |
| 5 | **SF₆ subscript rendering** (appeared as "SF ") | ✅ **Yes** | Global search‑and‑replace performed; **SF₆** is now correctly subscripted in all instances. |
| 6 | **Validation breadth** – confidence intervals on MAPE | ✅ **Yes** | **Section 7.2** now reports **bootstrap‑derived 95% confidence intervals** for all inverse parameters (Eₐ: [1.82%, 2.31%], η: [1.71%, 2.24%], r_arc: [2.89%, 3.62%]). |
| 7 | **Missing purely data‑driven baseline** (DNN without physics) | ✅ **Yes** | **Section 7.3** and **Table 10** provide a direct comparison against a feed‑forward DNN and a 1D‑CNN, both trained without any physics constraint. |
| 8 | **Stage III escalation criteria not defined** | ✅ **Yes** | **Section 8.1** explicitly defines Stage III escalation with three clear triggers (thermal under‑threshold, SF₆ Class III severity, or arc energy >80% withstand rating with MAPE <10%). |
| 9 | **Figure resolution** (≥300 dpi) | ✅ **Yes** | All figures have been regenerated and exported at **300 dpi** (or higher) in the required format. |

---

### ✅ Reviewer F Comments

| # | Comment | Addressed? | Location in Revised Manuscript |
|---|---------|------------|--------------------------------|
| 1 | **How to decide the values for the weights in Equation (6)?** (λ₁, λ₂, λ₃) | ✅ **Yes** | **Section 5.2** – Added a dedicated **"Loss Weight Selection Procedure"** paragraph explaining the grid‑search methodology over λ ∈ {0.01, 0.1, 1, 10, 100} and validation against a hold‑out set. **Table 6** shows a one‑at‑a‑time sensitivity analysis, confirming stable performance within ±50% of the chosen values. |

---

### Summary

All **5 editorial comments**, all **9 reviewer E comments**, and the **1 reviewer F comment** have been responded to and fully incorporated into the revised manuscript. The paper now includes:

- New comparative tables (Tables 1, 6, 10, 11, 14)
- Expanded validation (bootstrap CIs, synthetic set, DNN baseline)
- Explicit definitions (Stage III escalation, loss‑weight selection)
- Corrected formatting (equations, abbreviations, references, figures)
- Condensed background sections

The revised manuscript is substantially stronger, more rigorous, and fully responsive to all concerns raised. We believe it is now suitable for publication and thank the editorial team and reviewers again for their constructive feedback.
