---
id: identifications
title: Identifications
sidebar_position: 1
slug: /identifications
---

# Identifications (`/identifications`)

Cette page liste l'ensemble des fiches d'identification des bénéficiaires enregistrées sur la plateforme.

:::info[Permission requise]
L'accès à cette page nécessite la permission **Voir les identifications** (`READ_IDENTIFICATION`).
:::

:::info[Visibilité selon le rôle]
Un utilisateur ayant le rôle **Superviseur** ou **Facilitateur** ne voit que les fiches de la structure à laquelle il est rattaché. Un utilisateur **Admin** ou **Viewer** voit en principe l'ensemble des fiches de la plateforme, mais si son compte est lui aussi affecté à une structure, la même restriction s'applique.
:::

![Vue de la page Identifications](/img/2.png)
![Vue de la page Identifications](/img/3.png)

## En-tête de la page

- **Champ de recherche** : recherche un bénéficiaire par son nom.
- **Bouton « Nouveau »** : ouvre le formulaire de création d'une [nouvelle fiche d'identification](./02-fiche-identification.md).
- **Bouton « Filtrer »** : ouvre une fenêtre modale avec les critères suivants :
  - Structure
  - Commune
  - Village / Secteur
  - Type d'handicap
  - Mode de saisine
  - Surnom
  - Sexe
  - Occupation
  - Lieu d'habitation
  - Statut d'orphelin
  - Enregistré par
  - Date de création (Min)
  - Date de création (Max)

  Trois boutons permettent de valider l'action : **Effacer** (réinitialise les critères), **Fermer** (ferme la fenêtre sans appliquer) et **Rechercher** (applique les filtres).
- **Boutons d'export** : **Copier**, **CSV**, **Excel**, **PDF**, pour exporter la liste affichée (en tenant compte des filtres et de la recherche en cours).

## Tableau des identifications

| Colonne | Description |
|---|---|
| Nom et prénom(s) | Identité du bénéficiaire |
| Sexe | Masculin / Féminin |
| Age | Âge du bénéficiaire |
| Handicap | Type(s) de handicap identifié(s) |
| Niv. scolar. | Niveau de scolarisation |
| Structure | Structure ayant enregistré la fiche |
| Crée le | Date de création de la fiche |
| Action | Actions disponibles sur la ligne |

### Actions disponibles

- **Voir** : ouvre la [page de détail](./03-details-identification.md) de la fiche.
- **Modifier** : ouvre le formulaire pré-rempli pour mettre à jour la fiche.
- **Supprimer** : supprime la fiche d'identification.
- **Ajouter un PRI** : ouvre le formulaire de création d'un [Plan PRI](./05-fiche-pri.md) pour ce bénéficiaire.
