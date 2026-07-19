---
id: dashboard
title: Tableau de bord
sidebar_position: 3
slug: /dashboard
---

# Tableau de bord (`/index`)

Le tableau de bord est la page d'accueil de la plateforme. Il offre une vue d'ensemble rapide de l'activité, avant d'aller consulter le détail dans **Rapports**.

Il est composé de quatre zones, empilées du haut vers le bas.

![Vue du dashboard](/img/1.jpg)

## 1. Indicateurs globaux

La première ligne affiche quatre indicateurs clés (KPI) pour l'ensemble de la plateforme :

- **Enfants enregistrés** — nombre total de fiches d'identification.
- **Plans PRI** — nombre total de Plans de Réadaptation Individuels.
- **Évaluations** — nombre total d'évaluations réalisées.
- **Taux de réalisation** — pourcentage des PRI ayant fait l'objet d'une évaluation (ou des activités planifiées effectivement réalisées).

## 2. Carte et liste des structures

La deuxième ligne présente :

- une **carte géographique** qui situe chaque structure (affichée sous la forme *Structure × Commune*), avec sa Province et sa Région ;
- à côté de la carte, une **liste** reprenant les mêmes structures sous forme de cartes cliquables, chacune affichant les mêmes quatre indicateurs que ci-dessus (Enfants enregistrés, Plans PRI, Évaluations, Taux de réalisation), mais calculés pour cette structure uniquement.

## 3. Détail d'une structure (zone masquée par défaut)

Cette troisième zone est **cachée par défaut**. Elle s'affiche uniquement lorsque vous cliquez sur un marqueur de la carte ou sur un élément de la liste des structures, et présente alors le détail correspondant à la structure sélectionnée.

## 4. Points d'attention et activité récente

La dernière ligne comporte deux cartes côte à côte :

### Points d'attention

Cette card met en avant les situations qui nécessitent une action, en n'affichant **que les compteurs différents de zéro** parmi :

- Bénéficiaire(s) sans PRI ;
- PRI sans évaluation ;
- PRI en attente (de validation) ;
- Structure(s) sans activité ;
- Fiches hors ligne en attente (de synchronisation).

### Activité récente

Cette card liste les dernières actions enregistrées sur la plateforme : Identification enregistrée, Plan PRI créé, Évaluation créée. Cliquer sur un élément de la liste ouvre directement sa page de détail.
