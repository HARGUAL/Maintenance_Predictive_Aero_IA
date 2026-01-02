# 🛠️ Maintenance Prédictive Aéronautique par IA
**Projet académique – ENSA Safi – Dépt. IRT – GATE3**  
Réalisation sur **Google Colab** pour une exploration interactive des données et modèles.

---

## 🎯 Objectif
Prédire la **Durée de Vie Restante (RUL)** des moteurs aéronautiques à partir de capteurs (température, pression, vitesse…) pour passer d’une maintenance préventive à une **maintenance prédictive sécurisée**.

---

## 🗃️ Dataset
**NASA C-MAPSS** : 21 capteurs + 3 paramètres opérationnels  
Fichiers principaux : `train_FD001.txt`, `test_FD001.txt`

---

## 🔧 Méthodologie
- **EDA** : courbes de dégradation, capteurs constants, corrélations  
- **Prétraitement** : calcul RUL, suppression des features non pertinentes, normalisation Min-Max  
- **Modélisation** : Régression Linéaire (baseline) et Random Forest (modèle principal)  
- **Évaluation** : RMSE sur jeu de test, importance des features  

---

## ✅ Résultats clés
- RMSE ≈ **32–34 cycles**  
- Features les plus influentes : `sensor_11`, `sensor_9`, `sensor_4`  
- Bon alignement prédictions/réel avec dispersion attendue pour les RUL élevés


---

## 🛠️ Stack
- **Python 3.x**, pandas, scikit-learn, matplotlib, seaborn  
- **Plateforme** : Google Colab

---

🔗 **Tester le notebook sur Colab** : https://colab.research.google.com/drive/1GH2cG3I4gfQzi3oezaXmNLzZqiTnzw9m#scrollTo=CU-J_g72qGLt

