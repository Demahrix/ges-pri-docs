---
id: localisation
title: Localisation
sidebar_position: 1
slug: /configuration/localisation
---

# Localisation

Cette section regroupe la gestion du découpage administratif du Burkina Faso utilisé par la plateforme (Régions, Provinces, Communes, Villages/Secteurs). Ces référentiels servent notamment à renseigner la localisation des structures et des bénéficiaires dans les fiches d'identification, de PRI et d'évaluation.

:::info[Permission requise]
L'accès à l'ensemble des pages ci-dessous nécessite la permission **Voir les paramètres d'administration** (`VIEW_ADMINISTRATION_SETTINGS`).
:::

## Régions (`/regions`)

Liste des Régions du Burkina Faso référencées sur la plateforme. Permet de consulter, ajouter, modifier ou supprimer une Région.

## Provinces (`/provinces`)

Liste des Provinces, chacune rattachée à une Région. Permet de consulter, ajouter, modifier ou supprimer une Province, et de la relier à sa Région.

## Communes (`/communes`)

Liste des Communes, chacune rattachée à une Province. Permet de consulter, ajouter, modifier ou supprimer une Commune, et de la relier à sa Province.

## Villages / Secteurs (`/village-secteurs`)

Liste des Villages (en zone rurale) et Secteurs (en zone urbaine), chacun rattaché à une Commune. Permet de consulter, ajouter, modifier ou supprimer un Village/Secteur, et de le relier à sa Commune.

:::tip[Hiérarchie]
Le découpage suit une hiérarchie stricte à quatre niveaux : **Région → Province → Commune → Village/Secteur**. Chaque niveau ne peut être rattaché qu'à un seul élément du niveau supérieur, ce qui garantit la cohérence des filtres géographiques utilisés ailleurs sur la plateforme (fiches, filtres de recherche, rapports, carte du tableau de bord).
:::
