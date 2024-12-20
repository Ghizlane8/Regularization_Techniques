# Techniques de Régularisation en Machine Learning

Ce dépôt contient une présentation complète des techniques de régularisation en machine learning, y compris les concepts théoriques, les comparaisons pratiques, et des implémentations en Python. L'objectif est d'expliquer comment la régularisation aide à prévenir le surajustement (`overfitting`) et à améliorer la généralisation des modèles.

---

## 📖 Contenu

### Présentations Théoriques
- **Introduction à la régularisation** : 
  - Explication du problème de surajustement et des limites des modèles trop complexes.
  - Définition et principes fondamentaux de la régularisation.
 
- **Comprendre le surajustement** :
   - Identifier les symptômes d’un modèle trop complexe (overfitting).
   - Comprendre pourquoi la généralisation est essentielle pour de bonnes performances en machine learning.

- **Méthodes de régularisation** :
  - **L1 (Lasso)** : Pénalise la somme des valeurs absolues des coefficients, ce qui encourage la parcimonie.
  - **L2 (Ridge)** : Pénalise la somme des carrés des coefficients pour réduire les grandes valeurs.
  - **Elastic Net** : Combine les pénalités L1 et L2 pour un compromis entre sparsité et généralisation.

- **Comparaison des méthodes** :
  - Tableau comparatif des avantages et inconvénients des différentes techniques.
  - Cas d'utilisation pour chaque méthode.

- **Exemples pratiques** :
  - Applications des techniques sur des données synthétiques et réelles.

---

### Implémentations en Python
- **Scripts basés sur `scikit-learn`** :
  - Régressions linéaires régulières avec Ridge, Lasso, et Elastic Net.
  - Évaluation des scores d'entraînement et de test pour détecter le surajustement ou le sous-ajustement.

- **Classe personnalisée en Python** :
  - Implémentation de la régularisation en régression via des classes pour Lasso, Ridge et Elastic Net.
  - Contrôle des hyperparamètres comme `alpha` et `l_ratio`.

---

## 📂 Structure des fichiers

- `presentation-code1` : 
  - Contient les scripts utilisant `scikit-learn` pour montrer les scores et les visualisations de régularisation.

- `presentation-code2` :
  - Implémentation personnalisée des techniques L1, L2 et Elastic Net avec des classes Python.

- `Regularization_Techniques.pdf` :
  - Présentation complète expliquant les concepts théoriques et les cas d'utilisation.

## 🔍 **Concepts Clés**
- Régularisation : Technique ajoutant une pénalité à la fonction de coût pour contrôler la complexité du modèle.

- Alpha : Contrôle l'importance de la régularisation. Une valeur élevée simplifie le modèle mais risque le sous-ajustement.

- L1, L2 et Elastic Net : Différents mécanismes pour introduire des contraintes sur les coefficients.

## 🚀 Démarrage

### Prérequis
Assurez-vous d'avoir Python 3.x installé et les bibliothèques suivantes :
```bash
pip install numpy pandas matplotlib scikit-learn
