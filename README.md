# ProjetIA_mlflow_dagshub_2026

Projet IA : Méthodologie et déploiement (La Cité) – Groupe 9, Salome Bolivar.

Suivi des expériences MLflow avec DagsHub pour notre système de recommandation musicale (Jalon 2, version 2).

## Contenu

| Fichier | Rôle |
|---|---|
| `projet_ia_mlflow.ipynb` | Prépare les données, entraîne et évalue 5 modèles (popularité, cosinus audio, KNN item-item, SVD, EASE) et enregistre 16 expériences dans MLflow |
| `data/msd/` | Échantillon de 20 000 utilisateurs du *Taste Profile* du Million Song Dataset, relié à Spotify |
| `requirements.txt` | Bibliothèques Python nécessaires |

Métriques suivies : précision@5, rappel@5, hit rate@5 et temps d’inférence.

## Lancer le notebook

- Dans Google Colab : [ouvrir le notebook](https://colab.research.google.com/github/Salome2601/ProjetIA_mlflow_dagshub_2026/blob/main/projet_ia_mlflow.ipynb), puis *Exécution › Tout exécuter* et autoriser DagsHub.
- En local : `pip install -r requirements.txt`, puis ouvrir `projet_ia_mlflow.ipynb`.

## Interface MLflow

https://dagshub.com/Salome2601/ProjetIA_mlflow_dagshub_2026.mlflow

## Sources des données

- Million Song Dataset, *Taste Profile Subset* – Bertin-Mahieux et al., 2011 : http://millionsongdataset.com/tasteprofile/
- Spotify Tracks Dataset (maharshipandya) : https://huggingface.co/datasets/maharshipandya/spotify-tracks-dataset
