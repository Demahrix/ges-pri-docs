---
id: fiche-evaluation
title: Créer / Modifier une évaluation
sidebar_position: 8
slug: /evaluations/nouveau
---

# Créer ou modifier une évaluation de PRI

- **Création** : `/evaluations/nouveau/:pri-id` — accessible depuis le bouton **Faire une évaluation** d'un PRI.
- **Modification** : `/evaluations/modifier/:id/:pri-id`

Le formulaire reprend le contenu de la fiche papier « Fiche d'évaluation du PRI ». Il est directement rattaché à un PRI (`:pri-id`), dont certaines informations sont reprises automatiquement.

## Informations d'en-tête

- ID unique de l'évaluation (généré automatiquement)
- Nom de la structure
- Date
- Région, Province, Commune, Village / Secteur
- Nom du facilitateur
- Diagnostic du spécialiste (Oui/Non) — si oui, possibilité de joindre les conclusions ou recommandations
- Nom et prénom de l'enfant, Surnom, Sexe, Âge *(repris du PRI / de la fiche d'identification liés)*
- Nom du parent ou tuteur
- Contact du parent ou du tuteur

## Tableau d'évaluation

Le cœur de la fiche est un tableau qui reprend, pour chaque objectif défini dans le PRI, le suivi de sa réalisation :

| Objectifs | Activités prévues | Activités réalisées | Résultats atteints | Observations |
|---|---|---|---|---|

Un bouton permet d'ajouter autant de lignes que nécessaire ; il est recommandé de reprendre les objectifs et activités déjà saisis dans le PRI d'origine, puis de compléter les colonnes « Activités réalisées », « Résultats atteints » et « Observations ».

## Enregistrement

Un bouton **Enregistrer** (création) ou **Mettre à jour** (modification) valide l'évaluation.
