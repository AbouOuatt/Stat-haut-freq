# Rapport initialisation à la recherche : Statistique Haute Fréquence et Microstructure des Marchés

## Présentation
Ce projet rassemble le rapport de recherche ainsi que les codes associés à l'étude de divers modèles utilisés pour analyser les dynamiques de prix transactionnels sur les marchés financiers à haute fréquence.

### Objectifs
- Étudier les modèles d'exécution optimale de transactions.
- Estimer la volatilité réalisée en présence de bruit microstructural.
- Modéliser les dynamiques des prix transactionnels en prenant en compte des zones d'incertitude.
- Proposer une estimation robuste de la covariance pour des données observées de manière asynchrone.

## Structure du projet
```
projet-statistique-haute-frequence/
├── rapport.pdf              # Rapport de recherche complet
├── simulations/              # Scripts de simulation
│   ├── simulation1.ipynb     # Simulation du modèle d'Almgren et Chriss
│   ├── simulation2.ipynb     # Simulation sur les estimateurs de Zhang et al.
│   ├── simulation3.ipynb   # Modélisation des zones d'incertitude
│   └── simulation4.ipynb    # Estimateur sans biais de Hayashi et Yoshida
└── README.md                 # Ce fichier
```

## Contenu
### 1. Rapport
Le fichier `rapport.pdf` présente les études et résultats d'analyse autour de plusieurs articles majeurs :
- **Almgren et Chriss (2000)** : Stratégies d'exécution optimale.
- **Zhang, Mykland et Ait-Sahalia (2005)** : Estimateurs robustes pour la volatilité.
- **Robert et Rosenbaum (2010)** : Modèle des zones d'incertitude.
- **Hayashi et Yoshida (2005)** : Estimation de la covariance sans synchronisation.

### 2. Simulations
Les scripts dans le dossier `simulations/` permettent de reproduire les principales simulations présentées dans le rapport, notamment :
- Analyse des trajectoires optimales pour la liquidation d'actifs.
- Estimation des erreurs dues au bruit microstructural.
- Validation empirique des modèles des zones d'incertitude.



## Auteur.e.s
- Ouattara Aboubakar
- Borel Domgue
- Coralie Tonle

Supervision : M. Mathieu Rosenbaum

## Références
- Almgren, R., & Chriss, N. (2000). Optimal Execution of Portfolio transactions.
- Hayashi, T., & Yoshida, N. (2005). On Covariance Estimation of Non-synchronously Observed Diffusion Processes.
- Robert, C., & Rosenbaum, M. (2010). A New Approach for the Dynamics of Ultra-High-Frequency Data.
- Zhang, L., Mykland, P., & Ait-Sahalia, Y. (2005). A Tale of Two Time Scales.

