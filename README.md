# NFL Field Goal Outcome Prediction

## Overview  
A notebook for predicting NFL field-goal success using play-by-play data, from ingestion through model evaluation. Data sourced from PFF and is proprietary and not publicly available. 

## Quick Start  
1. **Clone**  
   ```bash
   git clone https://github.com/your-username/nfl-fg-prediction.git
   cd nfl-fg-prediction
   ```  
2. **Install**  
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   ```  
3. **Run**  
   ```bash
   jupyter notebook notebooks/fg_prediction.ipynb
   ```

## Highlights  
- **Data & EDA**: clean, filter (field goals only), visualize distance, weather, situational factors  
- **Modeling**: scikit-learn Pipelines, Random Forest & Gradient Boosting, SMOTE, hyperparameter search  
- **Evaluation**: ROC AUC, precision, recall, F1-score, threshold selection  

## Languages and Libraries  
Python · pandas · numpy · scikit-learn · imbalanced-learn · matplotlib · seaborn  

_For detailed interpretation and a full skills breakdown, see the final markdown cells in the notebook._  

## Contact

**Kasper Halevy**
- GitHub: [@kasperhalevy](https://github.com/kasperhalevy)
- LinkedIn: [Kasper Halevy](https://linkedin.com/in/kasperhalevy)
- Email: kasper.e.halevy@gmail.com
