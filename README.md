IRQC: Item Recommendation and Quantum Correlation for Recommender Systems

Overview
This repository presents the implementation of an Item Recommendation and Quantum Correlation (IRQC) approach for recommender systems. The project explores how quantum-inspired techniques can be used to compute similarity between users/items and compares their performance with classical correlation methods.

The work integrates:
- Quantum correlation computation using parameterized circuits  
- Classical similarity methods (Pearson & Cosine)  
- Performance evaluation using statistical and error metrics  

 Key Features
-  Quantum correlation using randomly initialized quantum circuits
-  Classical baselines:
     - Pearson Correlation
     - Cosine Similarity
-  Train-test split (80–20) evaluation
-  Error metrics:
    - Mean Squared Error (MSE)
    - Root Mean Squared Error (RMSE)
-  Statistical validation:
    - T-test
    - P-value analysis


Repository Structure

IRQC/
│── Classical_cosine_correlation.ipynb
│── Classical_Pearson_correlation.ipynb
│── Proposed_IRQC_QuantumCorrelation_MSE_RMSE.ipynb
│── Split_80_20_of_irqc.ipynb
│── T_statistic_and_P_value_IRQC.ipynb
│── README.md

Methodology

1. Classical Correlation
- Pearson Correlation: Measures linear similarity between users/items  
- Cosine Similarity: Measures angular similarity in vector space  

2. Quantum Correlation (IRQC)
- Uses quantum circuits to encode user/item data  
- Parameters are randomly initialized (non-trainable setup)  
- Acts as a quantum feature mapping mechanism

3. Data Splitting
- Dataset split into:
   - 80% Training
   - 20% Testing

4. Evaluation Metrics
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

 5. Statistical Analysis
- T-statistic computation  
- P-value significance testing  

Requirements

Install dependencies using:

pip install pennylane numpy pandas scikit-learn scipy


How to Run

1. Clone the repository:

git clone https://github.com/Bhaskaran-p/IRQC.git
cd IRQC

2. Open Jupyter Notebook:

jupyter notebook

3. Run notebooks in order:
   - Classical methods  
   - Quantum correlation  
   - Train-test split  
   - Evaluation & statistical analysis  


