# Description du Jeu de Données Ambisonique

Ce document répertorie les caractéristiques techniques des fichiers audio ambisoniques présents dans ce dossier. Tous les fichiers sont au format WAV et utilisent une disposition de canaux compatible avec le format Ambix (SN3D/ACN).

## Tableau Récapitulatif

| Fichier | Ordre Ambisonique | Canaux | Échantillonnage | Résolution | Durée |
| :--- | :---: | :---: | :---: | :---: | :---: |
| deus-ex-machina_4o.wav | 4 | 25 | 48 kHz | 24 bits | 04:30 |
| elliots_joy_o2_9ch.wav | 2 | 9 | 48 kHz | 24 bits | 01:48 |
| hoast_demo_o4_25ch.wav | 4 | 25 | 48 kHz | 24 bits | 04:02 |
| ort3org_o3.wav | 3 | 16 | 48 kHz | 32 bits (float) | 05:56 |
| space_walker_o3.wav | 3 | 16 | 48 kHz | 16 bits | 04:18 |
| Streichquartett_4o.wav | 4 | 25 | 48 kHz | 24 bits | 01:14 |
| tm_o4_25ch.wav | 4 | 25 | 48 kHz | 24 bits | 01:47 |

## Détails Techniques

- **Format** : WAV (Waveform Audio File Format)
- **Normalisation** : SN3D
- **Séquençage des canaux** : ACN (Ambisonic Channel Numbering)
- **Relation Ordre/Canaux** : Le nombre de canaux $N$ est lié à l'ordre $n$ par la relation $N = (n+1)^2$.
    - Ordre 2 : 9 canaux
    - Ordre 3 : 16 canaux
    - Ordre 4 : 25 canaux
