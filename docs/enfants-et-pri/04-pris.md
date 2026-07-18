---
id: pris
title: Plans PRI
sidebar_position: 4
slug: /pris
---

# Plans PRI (`/pris`)

Cette page liste l'ensemble des Plans de Réadaptation Individuels (PRI) créés sur la plateforme.

:::info[Permission requise]
L'accès à cette page nécessite la permission **Voir les PRI** (`READ_PRI`).
:::

## En-tête de la page

- **Champ de recherche** : recherche un bénéficiaire par son nom.
- **Bouton « Filtrer »** : ouvre une fenêtre modale avec les critères suivants :
  - Structure
  - Commune
  - Village / Secteur
  - Mode de saisine
  - Surnom
  - Sexe
  - Occupation
  - Lieu d'habitation
  - Statut d'orphelin
  - Date de création (Min)
  - Date de création (Max)
  - Enregistré par

  Trois boutons permettent de valider l'action : **Effacer**, **Fermer** et **Rechercher**.
- **Boutons d'export** : **Copier**, **CSV**, **Excel**, **PDF**.

:::note
Contrairement à la page Identifications, un PRI se crée toujours **à partir d'une fiche d'identification existante** (bouton « Ajouter un PRI » sur celle-ci), il n'y a donc pas de bouton « Nouveau » directement sur cette page.
:::

## Tableau des PRI

| Colonne | Description |
|---|---|
| Enfant | Nom du bénéficiaire concerné |
| Structure | Structure ayant élaboré le PRI |
| Objectifs | Aperçu des objectifs du plan d'accompagnement |
| Etat | En attente, Validé ou Rejeté |
| Crée le | Date de création du PRI |
| Action | Actions disponibles sur la ligne |

### Actions disponibles

- **Voir** : ouvre la [page de détail](./details-pri.md) du PRI.
- **Modifier** : ouvre le formulaire pré-rempli.
- **Supprimer** : supprime le PRI.
- **Valider** — *visible uniquement pour le rôle Superviseur* : fait passer l'état du PRI à « Validé ».
- **Rejeter** — *visible uniquement pour le rôle Superviseur* : fait passer l'état du PRI à « Rejeté ».
- **Faire une évaluation** : ouvre le formulaire de création d'une [évaluation](./fiche-evaluation.md) pour ce PRI.
- **Voir la fiche d'identification** : ouvre la fiche d'identification du bénéficiaire concerné.
- **Voir l'évaluation** : ouvre l'évaluation associée au PRI, si elle existe.
