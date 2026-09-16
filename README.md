# Regression-Quantile-en-contexte-immobilier-et-Prediction-Conforme-en-contexte-educatif

Projet d'analyse, de modélisation du risque dans un contexte d'investissement immobilier, et d'identification des étudiants qui ont besoin d'être suivis, dans un contexte éducatif. On utilisera des techniques avancéees de Machine Learning avec quantification de l'incertitude : la Régression Quantile et la Prédiction Conforme.

### Introduction

Dans le domaine de l'apprentissage automatique, la génération de prédictions ponctuelles est une pratique courante. Cependant, cette approche omet une information cruciale : le degré d'incertitude associé à cette prédiction. Pour des décisions à fort enjeu, cette incertitude n'est pas un détail, mais un facteur de risque critique.

Ce projet vise à implémenter, recoder et analyser des algorithmes de quantification d’incertitude dans deux contextes fondamentaux :
* Régression (Contexte Immobilier) : Nous chercherons à prédire le prix de vente d'une maison. L'objectif sera de générer un intervalle de prédiction fiable (ex: le prix sera entre 490k$ et 510k$), en comparant la Régression Quantile (QR) et la Prédiction Conforme (CP).
*  Classification (Contexte Éducatif) : Nous chercherons à prédire la note finale (GRADE) d'un étudiant. L'objectif sera de générer un ensemble de prédiction garanti (ex: la note sera {1, 2 ou 3}), en implémentant la Prédiction Conforme (CV+).

L'objectif global est d'évaluer la qualité de ces modèles, non seulement sur leur précision, mais aussi sur la fiabilité et l'utilité de l'incertitude qu'ils génèrent pour répondre à une problématique métier.
