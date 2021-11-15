## Survival Analysis - Primary Biliary Cirrhosis
Tableau Visualization: https://public.tableau.com/app/profile/ronnie.nop/viz/KMSurvivalCurvesforPatientswPBC/SurvivalDashboard
 
### Introduction 
Primary biliary cirrhosis (PBC) is a chronic liver disease caused by the buildup up bile, amino acids, and other substances in the bile ducts resulting in the progressive destruction of the liver. There are currently no known treatments to cure PBC, however, there are many ways to slow down its progression through treatment, surgery, and supportive care. Survival analysis offers a way to help clinicians diagnose severely diseased patients which can help decide the best appropriate treatments and plan of action to improve their survivability.

### Survival Analysis
Survival analysis is used to analyze data in which time to the event is the focus of interest where the response variable is either event time or survival time. The original purpose has its morbid roots in the medical field where clinicians were interested in predicting the survival probabilities of patients with a particular disease based on their individual features/covariates. Domains outside the clinical field have applied survival analysis to problems such as customer churn prediction, bank loan survival, credit risk, etc.

### Survival Models
* Kaplan-Meier Product-Limit Method
* Log-Rank Test for Comparison of Treatment Groups
* Cox Proportional Hazards Model
* Random Survival Forests

### Libraries
* python 3.7+
* numpy
* pandas
* matplotlib/seaborn
* lifelines
* scikit-survival
