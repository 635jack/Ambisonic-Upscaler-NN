# Ambisonic-Upscaler-NN

Ce projet implémente un réseau de neurones pour l'upscaling audio ambisonique (conversion de First Order Ambisonics - FOA vers High Order Ambisonics - HOA).

## Jeu de Données

Le modèle est entraîné en utilisant le jeu de données suivant disponible sur Hugging Face :
[jack635/ambisonic-dataset](https://huggingface.co/datasets/jack635/ambisonic-dataset-final)

## Structure du Projet

- **ambi_upscaler_train.ipynb** : Notebook principal contenant le code d'entraînement du modèle.
- **model_evaluation.ipynb** : Notebook dédié à l'évaluation des performances du modèle et aux tests qualitatifs.
- **test_samples/** : Répertoire contenant des fichiers audio de test (WAV) de différents ordres (2, 3 et 4).
- **checkpoint_best.pt** : Le meilleur modèle sauvegardé lors de l'entraînement.

## Installation et Utilisation

Ce dépôt utilise **Git LFS** pour gérer les fichiers volumineux (audios et modèles). Assurez-vous de l'avoir installé avant de cloner :

```bash
git lfs install
git clone https://github.com/635jack/Ambisonic-Upscaler-NN
```

Les notebooks peuvent être exécutés localement ou sur Google Colab.
