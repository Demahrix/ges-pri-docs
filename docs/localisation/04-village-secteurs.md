---
id: village-secteurs
title: Villages / Secteurs
sidebar_position: 4
slug: /village-secteurs
---

# Villages / Secteurs (`/village-secteurs`)

Cette page affiche la liste des Villages (en zone rurale) et Secteurs (en zone urbaine) référencés sur la plateforme.

:::info[Permission requise]
L'accès à cette page nécessite la permission **Voir les paramètres d'administration** (`VIEW_ADMINISTRATION_SETTINGS`).
:::

![Page Provinces](/img/19.png)

## En-tête de la page

- **Champ de recherche** : recherche un Village / Secteur par son nom.
- **Bouton « Nouveau »** : ouvre le formulaire de création d'un nouveau Village / Secteur.
- **Bouton « Filtrer »** : permet de filtrer la liste selon le statut.
- **Boutons d'export** : **Copier**, **CSV**, **Excel**, **PDF**, pour exporter la liste affichée (en tenant compte des filtres et de la recherche en cours).

## Tableau des Villages / Secteurs

| Colonne | Description |
|---|---|
| # | Numéro de ligne |
| Nom | Nom du Village / Secteur |
| Commune | Commune de rattachement |
| Province | Province de rattachement |
| Région | Région de rattachement |
| Longitude | Longitude géographique |
| Latitude | Latitude géographique |
| Statut | Statut du Village / Secteur |
| Crée le | Date de création |
| Action | Actions disponibles sur la ligne |

### Actions disponibles

- **Voir** : affiche le détail du Village / Secteur.
- **Modifier** : ouvre le formulaire pré-rempli pour mettre à jour le Village / Secteur.
- **Supprimer** : supprime le Village / Secteur.

:::tip[Hiérarchie]
Le découpage suit une hiérarchie stricte à quatre niveaux : **Région → Province → Commune → Village/Secteur**. Chaque niveau ne peut être rattaché qu'à un seul élément du niveau supérieur, ce qui garantit la cohérence des filtres géographiques utilisés ailleurs sur la plateforme (fiches, filtres de recherche, rapports, carte du tableau de bord).
:::
