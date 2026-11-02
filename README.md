<p align="center">
  <img src="banner.svg?v=3" width="100%" alt="David Sebastián Rodríguez Guzmán, Machine Learning Engineering">
  <img src="about.svg?v=1" width="100%" alt="About me. Hi! I'm David, an Actuarial Science and Data Science student from Mexico who likes turning data into things that work. My goal is to build tools and apps people use every day, software that solves real problems, with machine learning doing the hard part behind the scenes.">
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

<p align="center">
  <a href="https://mail.google.com/mail/?view=cm&fs=1&to=sebastianrg.sw@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"></a>
  <a href="https://www.linkedin.com/in/david-sebasti%C3%A1n-rodr%C3%ADguez-guzm%C3%A1n-8a464b421/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yMC40NDcgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODUzIDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTFWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjkgMS42MzctMS44NSAzLjM3LTEuODUgMy42MDEgMCA0LjI2NyAyLjM3IDQuMjY3IDUuNDU1djYuMjg2ek01LjMzNyA3LjQzM2EyLjA2MiAyLjA2MiAwIDEgMSAwLTQuMTI1IDIuMDYyIDIuMDYyIDAgMCAxIDAgNC4xMjV6TTcuMTE5IDIwLjQ1MkgzLjU1NVY5aDMuNTY0djExLjQ1MnpNMjIuMjI1IDBIMS43NzFDLjc5MiAwIDAgLjc3NCAwIDEuNzI5djIwLjU0MkMwIDIzLjIyNy43OTIgMjQgMS43NzEgMjRoMjAuNDUxQzIzLjIgMjQgMjQgMjMuMjI3IDI0IDIyLjI3MVYxLjcyOUMyNCAuNzc0IDIzLjIgMCAyMi4yMjIgMGguMDAzeiIvPjwvc3ZnPg%3D%3D" alt="LinkedIn"></a>
  <a href="https://www.instagram.com/david.rgman/"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"></a>
</p>
If you're working on ML for games, or anything with a lot of data behind it, I'd love to chat.
</p> <p align="center"> <a href="mailto:sebastianrg.sw@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a> <a href="https://www.linkedin.com/in/david-sebasti%C3%A1n-rodr%C3%ADguez-guzm%C3%A1n-8a464b421/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yMC40NDcgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODUzIDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTFWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjkgMS42MzctMS44NSAzLjM3LTEuODUgMy42MDEgMCA0LjI2NyAyLjM3IDQuMjY3IDUuNDU1djYuMjg2ek01LjMzNyA3LjQzM2EyLjA2MiAyLjA2MiAwIDEgMSAwLTQuMTI1IDIuMDYyIDIuMDYyIDAgMCAxIDAgNC4xMjV6TTcuMTE5IDIwLjQ1MkgzLjU1NVY5aDMuNTY0djExLjQ1MnpNMjIuMjI1IDBIMS43NzFDLjc5MiAwIDAgLjc3NCAwIDEuNzI5djIwLjU0MkMwIDIzLjIyNy43OTIgMjQgMS43NzEgMjRoMjAuNDUxQzIzLjIgMjQgMjQgMjMuMjI3IDI0IDIyLjI3MVYxLjcyOUMyNCAuNzc0IDIzLjIgMCAyMi4yMjIgMGguMDAzeiIvPjwvc3ZnPg%3D%3D" alt="LinkedIn"></a> <a href="https://www.instagram.com/david.rgman/"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"></a> </p>
