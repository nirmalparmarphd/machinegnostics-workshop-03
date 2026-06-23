# machinegnostics-workshop-03

Small-data tutorial workshop focused on where classical statistics can fail silently and Machine Gnostics can recover hidden structure.

This workshop is centered on real small datasets curated in `REAL_DATASETS_CLASSICAL_FAILURES.md`.

## How These Notebooks Are Structured
Each notebook follows the same flow:
1. Data and problem context
2. Classical analysis baseline (mean, median, confidence intervals, error bars)
3. Machine Gnostics analysis (robust center, interval analysis, ELDF comparisons)
4. Linear and polynomial regression comparison
5. What classical methods miss
6. Key takeaways

## Notebook Order
1. berkeley_admissions_aggregate.ipynb
2. berkeley_department_c_detail.ipynb
3. ms_trial_outlier_sensitivity.ipynb
4. pain_trial_bimodal_response.ipynb
5. vitamin_d_activity_confounding.ipynb
6. education_wage_composition_shift.ipynb
7. basketball_free_throw_paradox.ipynb
8. chest_xray_pneumonia_tail_risk.ipynb
9. psa_screening_prevalence_paradox.ipynb

Run notebooks in the order above for a consistent tutorial narrative.

## Google Colab Link Table
Repository: https://github.com/nirmalparmarphd/machinegnostics-workshop-03

| Notebook | Colab |
|---|---|
| berkeley_admissions_aggregate.ipynb | https://colab.research.google.com/github/nirmalparmarphd/machinegnostics-workshop-03/blob/main/berkeley_admissions_aggregate.ipynb |
| berkeley_department_c_detail.ipynb | https://colab.research.google.com/github/nirmalparmarphd/machinegnostics-workshop-03/blob/main/berkeley_department_c_detail.ipynb |
| ms_trial_outlier_sensitivity.ipynb | https://colab.research.google.com/github/nirmalparmarphd/machinegnostics-workshop-03/blob/main/ms_trial_outlier_sensitivity.ipynb |
| pain_trial_bimodal_response.ipynb | https://colab.research.google.com/github/nirmalparmarphd/machinegnostics-workshop-03/blob/main/pain_trial_bimodal_response.ipynb |
| vitamin_d_activity_confounding.ipynb | https://colab.research.google.com/github/nirmalparmarphd/machinegnostics-workshop-03/blob/main/vitamin_d_activity_confounding.ipynb |
| education_wage_composition_shift.ipynb | https://colab.research.google.com/github/nirmalparmarphd/machinegnostics-workshop-03/blob/main/education_wage_composition_shift.ipynb |
| basketball_free_throw_paradox.ipynb | https://colab.research.google.com/github/nirmalparmarphd/machinegnostics-workshop-03/blob/main/basketball_free_throw_paradox.ipynb |
| chest_xray_pneumonia_tail_risk.ipynb | https://colab.research.google.com/github/nirmalparmarphd/machinegnostics-workshop-03/blob/main/chest_xray_pneumonia_tail_risk.ipynb |
| psa_screening_prevalence_paradox.ipynb | https://colab.research.google.com/github/nirmalparmarphd/machinegnostics-workshop-03/blob/main/psa_screening_prevalence_paradox.ipynb |

## Tutorial Focus
- Mean and median comparison under small-sample instability
- Interval analysis and error-bar interpretation
- ELDF/EGDF and distribution-function visualization
- Linear vs polynomial regression behavior under confounding and outliers
- Why Machine Gnostics can be stronger than classical pooled statistics for small datasets

## Machine Gnostics Imports Used
```python
from machinegnostics.magcal import ELDF, EGDF, IntervalAnalysis
from machinegnostics.models import LinearRegressor, PolynomialRegressor
```
