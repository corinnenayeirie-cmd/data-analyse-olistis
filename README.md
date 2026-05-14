# Olist Customer Segmentation — K-means Clustering

## 🎯 Objectif
Segmenter les 99 441 clients du dataset Olist (e-commerce 
brésilien) pour identifier des profils acheteurs distincts 
et formuler des recommandations marketing ciblées.

## 📊 Dataset
- **Source** : [Brazilian E-Commerce Public Dataset by Olist (Kaggle)](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- **Volume** : 99 441 commandes, 2016–2018
- **Tables utilisées** : orders, customers, order_items, payments

## 🛠️ Stack technique
- Python 3.x
- pandas, numpy
- scikit-learn (K-means, StandardScaler)
- matplotlib, seaborn

## 🔍 Méthodologie
1. Nettoyage et fusion des tables Olist
2. Feature engineering (RFM : Récence, Fréquence, Montant)
3. Standardisation des variables
4. Détermination du k optimal (méthode du coude / silhouette)
5. K-means clustering
6. Profilage des segments

## 📈 Résultats
- [N] clusters identifiés
- [Profil cluster 1 : ex. "Acheteurs fréquents haut panier"]
- [Profil cluster 2 : ...]
- [...]

## 💡 Recommandations marketing
- [Recommandation 1]
- [Recommandation 2]

## ▶️ Comment lancer
\`\`\`bash
pip install -r requirements.txt
jupyter notebook olist_kmeans_segmentation.ipynb
\`\`\`
