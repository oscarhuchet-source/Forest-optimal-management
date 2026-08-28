# Gestion Optimale d'une Forêt

Projet de recherche appliquée — L3 Ingénierie Mathématique, Université de Bordeaux (2025–2026)  
Encadrant : Adrien Richou · Fondé sur : *Christensen & Strauch, arXiv:1909.09528, 2022*

---

## Contexte

Ce projet traite de l'optimisation de stratégies d'exploitation forestière sous incertitude stochastique. La quantité de bois disponible est modélisée par une équation différentielle stochastique. L'objectif est de déterminer le seuil de coupe optimal maximisant le profit moyen à long terme - d'abord en supposant la dynamique connue, puis sans connaissance a priori via un algorithme d'apprentissage par renforcement.

## Méthodes

- Simulation de trajectoires par schéma d'Euler (4 variantes : dérives linéaire/logistique × bruits constant/proportionnel)
- Estimation des lois stationnaires via le théorème ergodique et estimation par noyau
- Calcul du seuil optimal par la théorie du renouvellement stochastique
- Apprentissage par renforcement : alternance dynamique exploration/exploitation convergeant vers l'optimum théorique

## Implémentation

Python · NumPy · SciPy · Matplotlib

## Contenu

```
├── README.md
└── RapportGTA_GestionOptimaleForet.pdf
```
