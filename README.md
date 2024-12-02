# Sentiment Analysis with VADER and RoBERTa
Ce projet explore deux approches pour l'analyse des sentiments :
1. **VADER (Valence Aware Dictionary and sEntiment Reasoner)** : Un outil basé sur des règles pour analyser les sentiments, particulièrement adapté aux textes informels comme les tweets.
2. **RoBERTa** : Un modèle de Deep Learning pré-entraîné sur des données de texte pour la classification des sentiments.
Ce dépôt contient :
- Un notebook Google Colab (`sentiment_analysis.ipynb`) montrant comment utiliser VADER et RoBERTa pour analyser les sentiments.
- Un jeu de données Reviews.csv .
- Des visualisations des résultats.
### Prérequis
- Python 3.x
- Bibliothèques nécessaires :
  - `transformers`
  - `torch`
  - `nltk`
  - `matplotlib`
  - `seaborn`
  - `pandas`
- Télécharger le lexique VADER avec :
  ```python
  import nltk
  nltk.download('vader_lexicon')
