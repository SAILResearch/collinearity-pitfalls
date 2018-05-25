# The Impact of Correlated Metrics on the Interpretation of Defect Models

This repository is an online appendix for "The Impact of Correlated Metrics on the Interpretation of Defect Models"

### Abstract
---
> Defect models are analytical models for building empirical theories related to software quality.
> Prior studies often derive knowledge from such models using interpretation techniques, e.g., ANOVA Type-I.
> Recent work raises concerns that correlated metrics may impact the interpretation of defect models.
> Yet, the impact of correlated metrics in such models has not been investigated. 
> In this paper, we set out to investigate the impact of correlated metrics on the interpretation of defect models.
> Through a case study of 14 publicly-available defect datasets, we find that (1) correlated metrics have the largest impact on the consistency, the level of discrepancy, and the direction of ranking of metrics, especially for ANOVA techniques.
> On the other hand, we find that removing all correlated metrics (2) improves the consistency of the produced rankings regardless of the ordering of metrics (except for ANOVA Type-I); (3) improves the consistency of ranking of metrics among the studied interpretation techniques; (4) impacts the model performance by less than 5 percentage points.
> Thus, when one wishes to derive sound interpretation from defect models, ones must (1) mitigate correlated metrics especially for ANOVA analyses; and (2) avoid using ANOVA Type-I even if all correlated metrics are removed.
---

### Experimental Results

The repository consists of:

1. **Dataset Statistics** - A statistical summary of the studied defect datasets.
2. **Supplementary Experimental Results** - Results of the correlation analysis and the remaining metrics after correlated metrics are removed for all studied defect datasets.

