# Part 2 Report

Due: Friday 16 October 2026

## Section owners

| Section | Owner |
| --- | --- |
| Recap: problem, stakeholders, dataset | Christian Gaston |
| 1. Hyperparameter Tuning | Subba Taniparti |
| 2. Final Model Evaluation | Subba Taniparti (metrics), Harini Mamidala (figures) |
| 3. Ethical Considerations | Bellary Naveen Vishal |
| 4. Real-World Application | Christian Gaston |
| 5. Final Thoughts and Conclusion | Harini Mamidala |
| 6. Teamwork and Documentation | Bellary Naveen Vishal |

## Figures

Exported from the analysis notebook to `part2/figures/`. Each needs an APA caption with an
interpretive note stating what the reader should conclude, not a restatement of the title.

| File | Supports |
| --- | --- |
| `fig1_calibration.png` | Section 2, whether predicted probabilities are trustworthy |
| `fig2_threshold_stability.png` | Section 3, the group-specific threshold is unstable |
| `fig3_confusion.png` | Section 2, the threshold trade in patient counts |

## References to carry forward from Part 1

Part 1 cited 21 sources. The following are directly relevant to Part 2 claims and should be copied
from `part1/report/Group8_Part1_Report.docx` rather than re-found:

- Janosi et al. (1989) — dataset provenance
- Pedregosa et al. (2011) — scikit-learn
- Rajkomar et al. (2018) — why protected attributes are retained for evaluation
- Obermeyer et al. (2019) — algorithms inheriting historical patterns
- Mosca et al. (2011) — sex differences in cardiovascular care
- Chen et al. (2019) — deployment oversight

## Before submission

- [ ] Every number in the report matches the notebook
- [ ] All in-text citations appear in the reference list and vice versa
- [ ] Zero em-dashes (search for the character)
- [ ] Bounded statistics have no leading zero; values that can exceed 1 keep theirs
- [ ] Figures have interpretive captions
- [ ] Notebook committed with outputs intact
