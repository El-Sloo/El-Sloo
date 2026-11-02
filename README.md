<p align="center">
  <img src="banner.svg" width="100%" alt="David Sebastián Rodríguez Guzmán, Machine Learning Engineering">
</p>

I study Actuarial Science and Data Science in Guadalajara, Mexico, and I'm working toward Machine Learning Engineering. I like taking a model past the notebook: clean data pipelines, models I can actually explain, and tools people can use.

<!-- Cambia TU-USUARIO-AQUÍ por tu URL real de LinkedIn -->
<p>
  <a href="mailto:sebastianrg.sw@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://www.linkedin.com/in/TU-USUARIO-AQUÍ"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logoColor=white" alt="LinkedIn"></a>
</p>

## What I'm building

<img width="400" src="valorant-card.png" alt="+RR, Valorant rank rating predictor">

**+RR** predicts how much RR you win or lose in a Valorant ranked match, and tells you why.

- Data pipeline that pulls real ranked matches from a Valorant stats API into my own dataset
- Two-stage XGBoost model, about 1.6 RR average error
- SHAP breaks every prediction into reasons that add up to your real RR
- Sanity check: the model's 5-stack penalty (~5 RR) matches the patch notes (5.3)

**Roadmap**
- [x] Data pipeline from the API
- [x] RR model + SHAP explanations
- [ ] Player archetypes with PCA + clustering (next)
- [ ] Serve the model as a REST API with FastAPI, plus a Streamlit app, all in Docker
- [ ] CI/CD with GitHub Actions: automated retraining when a patch shifts the meta, runs tracked in MLflow, and the new model only ships if it beats the current one
- [ ] Drift monitoring to know when it's time to retrain

## Other projects

<p>
  <a href="https://github.com/El-Sloo/glm-vs-ml-actuarial-pricing"><img width="49%" src="glm-card.png" alt="GLM vs. machine learning for claim frequency"></a>
  <img width="49%" src="bitcoin-card.png" alt="Bitcoin regimes with a Markov-switching GBM">
</p>

## Tools

<p><img src="models.svg?v=3" width="100%" alt="Models I work with: regression (GLMs), clustering (K-Means + PCA), classification (logistic regression, SVM) and tree models (Random Forest, XGBoost)"></p>

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white" alt="pandas">
  <img src="https://img.shields.io/badge/NumPy-777BB4?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="scikit-learn">
  <img src="https://img.shields.io/badge/XGBoost-189FDD?style=for-the-badge" alt="XGBoost">
  <img src="https://img.shields.io/badge/SHAP-FF0D57?style=for-the-badge" alt="SHAP">
  <img src="https://img.shields.io/badge/SQL-005C84?style=for-the-badge&logo=mysql&logoColor=white" alt="SQL">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
</p>

Learning now:

<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white" alt="MLflow">
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions">
</p>

If you're working on ML for games, or anything with a lot of data behind it, I'd love to chat.
