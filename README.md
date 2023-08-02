# Estimating Risk and Benefit of Radiation Therapy in (y)pN1 Stage Breast Cancer Patients: A Bayesian Network Model Incorporating Expert Knowledge (KROG 22-13)

Highlights
* We developed a Bayesian Network model for evaluating pathologic N1 breast cancer patients using institutional data and nationwide expert survey
* Nationwide expert survey of 58 participants in 47 institutions were collected for treatment patterns and disability weight of each radiotherapy related risk and benefit 
* The expert survey revealed significant discrepancies among participants concerning factors related to reconstruction, while showing low discrepancies in radiotherapy-related side-effects.
* Analysis of the overall disease burden, calculated as the sum of probabilities multiplied by the respective disability weights, demonstrated a higher tendency in patients with triple-negative breast cancer or those who underwent mastectomy.

Background: 
We aimed to evaluate the risk and benefit of (y)pN1 patients in the Bayesian Network model.

Method: 
We developed a Bayesian Network (BN) model comprising three parts: pretreatment, intervention, and risk/benefit. Pretreatment part consists of clinical information from a tertiary medical center. Intervention part was the field of radiotherapy: The risk/benefit component encompasses radiotherapy (RT) related side-effects and effectiveness, including factors such as recurrence, cardiac toxicity, lymphedema, and radiation pneumonitis. These factors are evaluated in terms of disability weights and probabilities collected from a nationwide expert survey. The overall disease burden (ODB) was calculated as sum of the probability multiplied by the disability weight. A higher value of ODB indicates a greater disease burden for the patient.

Results: 
Among the 58 participants, a BN model utilizing discretization and clustering techniques revealed five distinct clusters. Overall, factors associated with breast reconstruction and its RT exhibited high discrepancies (24-34%), while RT-related side-effects demonstrated low discrepancies (3-11%) among the experts. When incorporating recurrence and RT related side-effects, the mean ODB of (y)pN1 patients was 0.258 (range, 0.244-0.337), with higher tendency observed in triple-negative breast cancer (TNBC) or mastectomy cases. The ODB for TNBC patients undergoing mastectomy without post-mastectomy radiotherapy was 0.327, whereas for no TNBC patients undergoing BCS with RT, the disease burden was 0.251. There were trends in increase of ODB as the field of RT increases. 

Conclusion: 
We developed a Bayesian Network model based on an expert-based survey, which helps understanding of treatment patterns, and enables precise estimations of RT-related risk and benefit in (y)pN1 patients.
Keywords: Bayesian Network, Disease Burden, Expert Knowledge, Survey, Disability Weights, Breast Cancer, Radiotherapy



<img width="80%" src="https://github.com/bigwiz83/BayesianNetwork_KROG22-13/blob/9a043eb7ec9792fa52ee0692bad00aee30127954/bayesian%20network.png">


To used our mode, BayesiaLab software should be installed in your computer.
Please, follow the instructions of the software hompage: https://www.bayesia.com/bayesia/
