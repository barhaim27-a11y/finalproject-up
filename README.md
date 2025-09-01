# Parkinson’s ML App – Ready to Run

## 📦 What’s inside?
- data/parkinsons.csv – full dataset
- model_pipeline.py – training & evaluation (Model Zoo, Train/Test, SHAP, Training Log)
- streamlit_app.py – Streamlit UI (EDA, Models, Prediction, Retrain, Explainability)
- requirements.txt – dependencies
- README.md – this guide
- models/ and assets/ – empty folders (will fill after training)

## ▶ How to run
```bash
pip install -r requirements.txt
streamlit run streamlit_app.py
```

## 🖥 App Tabs
- **📊 Data & EDA**: Explore dataset, statistics, distributions, correlations.
- **🤖 Models**: KPIs dashboard, Model Zoo, Confusion Matrix, ROC Curve.
- **🔮 Prediction**: Manual or batch predictions, risk labels, SHAP explanations, CSV export.
- **⚡ Train New Model**: Upload dataset, retrain, compare models, training log.

## 🔑 Example Usage Flow
1. Launch the app: `streamlit run streamlit_app.py`
2. Go to **📊 Data & EDA** → Inspect dataset & correlations.
3. Open **🤖 Models** → View dashboard, compare models in the Zoo.
4. Go to **🔮 Prediction** → Try manual input or upload a CSV, get predictions + risk levels + SHAP explanations.
5. In **⚡ Train New Model** → Upload new data, retrain models, see log of training history.
6. (Optional) Promote the best performing retrained model for future predictions.
