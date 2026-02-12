Home Loan Application Credit Risk Scorecard
**Author:** Abhijit Kudtarkar

**Overview:**
Built an end-to-end application credit risk scorecard to predict 90+ DPD at 12 Months on Book (12 MOB) using industry-standard methodology.

**Methodology**
100K synthetic home loan applications generated
931 bureau features engineered → 947 total variables
WOE encoding with monotonic binning
IV filtering (0.02–0.6)
Correlation & VIF checks
Final model: L1-Regularized Logistic Regression

**Model Performance (Test Data):**
AUC: 0.68
Gini: 0.36
KS: 0.28

**Business Impact:**
Approving Deciles 1–7 removes ~30% of portfolio while eliminating ~54% of bad loans.

Full methodology and documentation available in the project report.
