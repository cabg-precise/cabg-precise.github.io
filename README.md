# CABG-PRECISE Risk Score

### Overview
**CABG-PRECISE** is a preoperative clinical predictive model designed to estimate in-hospital mortality risk following coronary artery bypass graft (CABG) surgery. The model was developed and validated at Hospital General Universitario Gregorio Marañón (Madrid, Spain) using a cohort of 2,101 consecutive patients.

### Clinical Calculator
The interactive web-based tool is available here:
**[https://cabg-precise.github.io](https://cabg-precise.github.io)**

### Performance & Clinical Utility
The model demonstrates high precision and significant improvement over traditional scoring systems:

* **Discrimination:** The final model achieved a corrected AUC of 0.810, significantly outperforming EuroSCORE II in our cohort (p=0.003).
* **Calibration:** Excellent agreement between predicted and observed mortality, with a Hosmer-Lemeshow p-value of 0.317 and an Expected/Observed (E/O) Ratio of 1.00.
* **Clinical utility:** Significant reclassification improvement over EuroSCORE II with a Net Reclassification Improvement of 52.1% and an Integrated Discrimination Improvement of 6.8%. Decision Curve Analysis confirmed a higher net benefit across the majority of risk thresholds.
* **Methodology:** Utilization of *Restricted Cubic Splines* for age to capture non-linear risk and internal validation via bootstrapping (1,000 iterations).

### Authors
* **Corresponding author & developer:** Ignacio Vasserot, MD.
* **Senior investigators:** Manuel Martínez-Sellés, MD, PhD; José María Barrio, MD, PhD; Gregorio Cuerpo, MD, PhD; Javier Bermejo, MD, PhD; Ignacio Garutti, MD, PhD; Javier Hortal, MD, PhD.

### Affiliation
* Department of Anesthesiology / Department of Cardiology / Department of Cardiac Surgery.
* Hospital General Universitario Gregorio Marañón, Madrid, Spain.

### Reference
*Manuscript in press (2026).*
