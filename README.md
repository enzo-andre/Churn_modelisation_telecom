# Prédiction de départ clients (Churn Prediction)

Ce projet vise à prédire le départ des clients d'une entreprise de télécommunications à l'aide du Machine Learning. Il a été pensé comme une **simulation de mission client**.

---

## Objectifs

- Identifier les facteurs qui influencent le plus le churn client.
- Construire un modèle de machine learning capable de prédire les départs clients.
- Dégager des insights exploitables pour des prises de décisions marketing stratégiques.

---

## Stack technique

- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Plotly)
- **Machine Learning** : Scikit-learn (Logistic Regression, Random Forest)
- **Visualisation** : Plotly Express

---

## Étapes du projet

1. **Introduction**
2. **Chargement et nettoyage des données** : nettoyage, encodage.
3. **Manipulation des données** : compréhension fine des profils à risque (clients sans partenaire, avec fibre optique, contrats mensuels…).
4. **Modélisation** :
   - Régression logistique (baseline)
   - Random Forest (modèle final avec GridSearchCV)
5. **Conclusion** 

---

## ✅ Résultats

- **Accuracy modèle final** : 79 %
- **Recall sur la classe churn** : 54 %
- **Variables les plus importantes** : `tenure`, `MonthlyCharges`, `type de contrat`, `sécurité en ligne`, `mode de paiement`


---

## Recommandations client type

- **Inciter les clients récents** à s'engager via des contrats annuels ou biannuels.
- **Offrir la sécurité en ligne** gratuitement pour les clients les plus à risque.
- **Optimiser l'expérience de paiement** pour ceux utilisant le prélèvement automatique (clients à risque plus élevé avec "Electronic check").


---

## 👤 Auteur
> Enzo André, dans le cadre d'une transition en data science
> [LinkedIn](https://www.linkedin.com/in/enzoandre/) | [Portfolio](https://github.com/enzo-andre)
