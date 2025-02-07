# 🚲 Market Basket Analysis : Optimisation des ventes avec l'intelligence artificielle

## 🎯 Objectif
L’objectif de cette étude est d’analyser les **corrélations entre les articles achetés** afin d’identifier les produits qui sont souvent achetés ensemble. Cela permet d’optimiser :
- La **recommandation de produits** en e-commerce.
- Les **stratégies de ventes croisées** (*cross-selling*).
- L’**efficacité des promotions et campagnes marketing**.

## 🔬 Méthodologie

1. **Préparation des données** 📊
   - Extraction et transformation des données brutes.
   - Construction d’une **matrice transactionnelle** des achats.

2. **Détection des règles d’association** 📈
   - **Apriori** : Identification des ensembles d’articles fréquents.
   - **FPGrowth** : Optimisation de l’algorithme Apriori pour réduire le temps de calcul.
   - **SARL (Scalable Association Rule Learning)** : Approche évolutive adaptée aux grandes bases de données.

3. **Approche avancée avec XGBoost** 🚀
   - Application de **XGBoost (eXtreme Gradient Boosting)** pour prédire les associations d’articles.
   - Test de performance sur différents seuils de **support et confiance**.

## 📊 Résultats Clés

- Détection des produits fréquemment achetés ensemble avec un support élevé.
- Génération de **règles d’association précises**, classées selon leur **confiance et lift**.
- Comparaison des performances des algorithmes :
  - **FPGrowth** plus rapide et plus efficace en mémoire qu'Apriori.
  - **XGBoost** améliore la capacité de prédiction en combinant plusieurs modèles.

## 🌈 Visualisation des résultats

### Distribution des transactions les plus fréquentes
![Graphique des transactions](path/to/transactions_chart.png)

### Comparaison des temps d'exécution des algorithmes
![Comparaison des algorithmes](path/to/performance_chart.png)

### Règles d'association les plus significatives
![Règles d'association](path/to/association_rules_chart.png)

## 🚀 Applications Réelles

👉 **Optimisation des recommandations produit** pour les plateformes e-commerce  
👉 **Stratégies de vente personnalisées** basées sur l'analyse des comportements d'achat  
👉 **Amélioration du ciblage marketing** avec des données prédictives  

## 📈 Perspectives de recherches

- **Amélioration des modèles d'apprentissage** : exploration de modèles d'intelligence artificielle plus complexes pour une prédiction plus fine des comportements d'achat.
- **Personnalisation avancée** : intégration de données utilisateur pour adapter les recommandations aux préférences individuelles.
- **Scalabilité** : implémentation de solutions distribuées pour traiter des bases de données à grande échelle en temps réel.

## 🛠 Technologies utilisées

- **Python (Pandas, NumPy, Scipy)** pour la manipulation des données.
- **MLxtend (Apriori, FPGrowth, Association Rules)** pour l’extraction des règles.
- **XGBoost** pour l’optimisation des prédictions.
- **Matplotlib & Seaborn** pour la visualisation des tendances.
