# Fine-Tuning d'un LLM sur le Dataset IMDB

Ce projet présente un exemple complet de fine-tuning d’un modèle de langage pré-entraîné (comme `DistilBERT`) sur le dataset IMDB pour la classification de sentiments (positif/négatif).

##  Fonctionnalités principales

- Chargement et prétraitement du dataset IMDB
- Utilisation de la bibliothèque `datasets` de Hugging Face
- Tokenization avec `AutoTokenizer`
- Fine-tuning d’un modèle `AutoModelForSequenceClassification`
- Évaluation des performances avec `accuracy`, `f1`, etc.
- Sauvegarde et chargement du modèle fine-tuné

##  Librairies utilisées

- `transformers`
- `datasets`
- `evaluate`
- `scikit-learn`
- `torch`

##  Instructions de démarrage

1. Cloner ce dépôt ou télécharger le notebook.
2. Installer les dépendances :


```pip install transformers datasets evaluate scikit-learn torch ```|
##  Instructions d'utilisation

Lancer le notebook `FineTuningLLM_with_IMDB_Dataset.ipynb`.

Suivre les étapes pour :

- Préparer les données
- Entraîner le modèle
- Évaluer et sauvegarder les résultats

##  Résultats

Le modèle atteint une précision et une F1-score compétitives sur l'ensemble de test du jeu de données IMDB, démontrant l'efficacité du fine-tuning avec les LLM.

##  Fichiers

- `FineTuningLLM_with_IMDB_Dataset.ipynb` : Notebook principal avec tout le code.
- `model/` : Dossier prévu pour sauvegarder le modèle fine-tuné (créé automatiquement).

##  Auteurs

Ce projet a été réalisé à titre pédagogique pour illustrer le fine-tuning de modèles de langage avec Hugging Face.


##  Fichiers

    FineTuningLLM_with_IMDB_Dataset.ipynb : Notebook principal avec tout le code.

    model/ : Dossier prévu pour sauvegarder le modèle fine-tuné (créé automatiquement).

##  Contribution

Les contributions sont les bienvenues !
Merci de soumettre un pull request ou d’ouvrir une issue pour discuter de modifications majeures avant de les proposer.
📄 Licence

Ce projet est sous licence MIT.
Vous êtes libre de l’utiliser, le modifier et le distribuer avec mention de l’auteur original.
