# 🧠 Analyse de Sentiment de Tweets avec NLP & Gradio

Ce projet utilise le **Traitement du Langage Naturel (NLP)** pour prédire le **sentiment de tweets** (positif ou négatif) à l’aide du dataset **sentimentTweet**. Il inclut un modèle de Machine Learning, une visualisation des résultats, ainsi qu’une interface utilisateur interactive développée avec **Gradio**.

---

## 📌 Objectifs du projet

- Prétraiter et nettoyer des tweets bruts
- Vectoriser le texte avec TF-IDF
- Entraîner un modèle Naive Bayes pour la classification binaire (positif vs négatif)
- Évaluer les performances du modèle
- Créer une interface web simple pour tester le modèle

---

## 📁 Contenu du projet

- `Sentiment_Analysis_Tweets_NLP_Gradio.ipynb` : Notebook principal avec toutes les étapes
- `sentimentTweet.csv` : Dataset utilisé 
- `naive_bayes_model.pkl` : Modèle entraîné
- `tfidf_vectorizer.pkl` : TF-IDF vectorizer sauvegardé
- Interface Gradio intégrée dans le notebook
<img width="584" alt="Screenshot 2025-05-21 220823" src="https://github.com/user-attachments/assets/ce463e8b-8b9d-4c44-a592-0adc569628e8" />

---


🖼️ Exemple d’utilisation
Tweet : "I love this phone, it works perfectly!"

Prédiction : 🟢 Positif

Tweet : "This is the worst update ever..."

Prédiction : 🔴 Négatif
📈 Résultats du Modèle
Modèle : Naive Bayes

Vectorisation : TF-IDF

Accuracy : ~76% sur les données de test

Évaluation : matrice de confusion, classification report, WordCloud

<img width="411" alt="2" src="https://github.com/user-attachments/assets/dadfcc32-1621-44f1-9231-f2318c5668cc" />


🧑‍💻 Auteur
Pierre Musili – https://www.linkedin.com/in/pierre-musili/ 
