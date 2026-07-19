---
id: fiche-pri
title: Créer / Modifier un PRI
sidebar_position: 5
slug: /pris/nouveau
---

# Créer ou modifier un Plan de Réadaptation Individuel (PRI)

- **Création** : `/pris/nouveau/:identification-id` — accessible depuis le bouton **Ajouter un PRI** d'une fiche d'identification.
- **Modification** : `/pris/modifier/:id/:identification-id`

Le formulaire reprend le contenu de la fiche papier « Fiche de PRI ». Il est directement rattaché à une fiche d'identification (`:identification-id`), dont certaines informations sont reprises automatiquement.

![Vue de la fiche PRI](/img/31.png)

## Informations d'en-tête

- ID unique du PRI (généré automatiquement)
- Nom de la structure
- Date
- Région, Province, Commune, Village / Secteur
- Nom du facilitateur
- Diagnostic du spécialiste (Oui/Non) — si oui, possibilité de joindre les conclusions ou recommandations (document ou texte)
- Nom et prénom de l'enfant, Surnom, Sexe, Âge *(repris de la fiche d'identification liée)*
- Nom du parent ou tuteur
- Contact du parent ou du tuteur

## I. Analyse des problèmes

Décrit le ou les problèmes qui empêchent la pleine participation communautaire du bénéficiaire, à travers les questions suivantes :

- Quelle déficience l'individu porte-t-il ? (perte ou dysfonctionnement d'une structure psychologique, physiologique ou anatomique)
- Quelles limitations la déficience a-t-elle entraînées ? (restriction ou manque d'habileté à remplir une fonction : comportement, communication, locomotion, soins personnels, utilisation du corps, etc.)
- L'individu participe-t-il aux activités ménagères, socioculturelles, économiques dans sa famille et sa communauté ?
- La famille ou la communauté a-t-elle développé des initiatives pour faciliter l'intégration/l'inclusion de l'individu ? (accessibilité physique, communication, attitude, accès aux services sociaux de base)
- L'individu arrive-t-il à jouer son rôle social selon son âge et son sexe ?

## II. Facteurs favorisants

Zone de texte libre pour décrire les facteurs qui favorisent l'accompagnement de l'individu.

## III. Projets de la personne / famille (attentes)

Zone de texte libre pour décrire les attentes et projets exprimés par la personne ou sa famille.

## IV. Identification et priorisation des besoins pour le semestre

Zone de texte libre listant les besoins retenus comme prioritaires pour le semestre en cours.

## V. Élaboration du processus d'accompagnement

Tableau des actions planifiées, avec une ligne par action et les colonnes suivantes :

| Objectifs | Activités | Période | Moyens à utiliser | Résultats attendus | Observations |
|---|---|---|---|---|---|

Un bouton permet d'ajouter autant de lignes que nécessaire.

## Enregistrement

Un bouton **Enregistrer** (création) ou **Mettre à jour** (modification) valide le PRI. Un PRI nouvellement créé est à l'état **En attente** jusqu'à validation ou rejet par un Superviseur (voir [Plans PRI](./04-pris.md)).

:::info[Notification par e-mail]
Lors de la création d'un PRI, un e-mail est automatiquement envoyé aux utilisateurs ayant le rôle **Superviseur** dans la structure concernée, pour les informer qu'un PRI attend leur validation.
:::