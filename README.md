This repository presents the implementation of an Item Recommendation and Quantum Correlation (IRQC) approach for recommender systems. The project explores how quantum-inspired techniques can be used to compute similarity between users/items and compares their performance with classical correlation methods.
The work integrates:
•	Quantum correlation computation using parameterized circuits 
•	Classical similarity methods (Pearson & Cosine) 
•	Performance evaluation using statistical and error metrics 

Key Features
•	Quantum correlation using randomly initialized quantum circuits 
•	Classical baselines: 
  o	Pearson Correlation 
  o	Cosine Similarity 
•	Train-test split (80–20) evaluation 
•	 Error metrics: 
   o	Mean Squared Error (MSE) 
   o	Root Mean Squared Error (RMSE) 
•	Statistical validation: 
   o	T-test 
   o	P-value analysis 

 Repository Structure
IRQC/
│── Classical_cosine_correlation.ipynb
│── Classical_Pearson_correlation.ipynb
│── Proposed_IRQC_QuantumCorrelation_MSE_RMSE.ipynb
│── Split_80_20_of_irqc.ipynb
│── T_statistic_and_P_value_IRQC.ipynb
│── README.md
