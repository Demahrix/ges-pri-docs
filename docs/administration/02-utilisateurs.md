---
id: utilisateurs
title: Utilisateurs
sidebar_position: 2
slug: /utilisateurs
---

# Utilisateurs (`/utilisateurs`)

Cette page affiche la liste des utilisateurs de la plateforme.

:::info[Permission requise]
L'accès à cette page nécessite la permission **Voir les paramètres d'administration** (`VIEW_ADMINISTRATION_SETTINGS`).
:::

![Page Utilisateurs](/img/21.png)
![Page Utilisateurs](/img/22.png)

## En-tête de la page

- **Champ de recherche** : recherche un utilisateur par son nom.
- **Bouton « Nouveau »** : ouvre le formulaire de création d'un nouvel utilisateur.
- **Bouton « Filtrer »** : ouvre une fenêtre modale avec les critères suivants :
  - Rôle
  - Adresse e-mail
  - Sexe
  - Numéro de téléphone
  - Statut
  - Date de création (Min)
  - Date de création (Max)
  - Enregistré par

  Trois boutons permettent de valider l'action : **Effacer** (réinitialise les critères), **Fermer** (ferme la fenêtre sans appliquer) et **Rechercher** (applique les filtres).
- **Boutons d'export** : **Copier**, **CSV**, **Excel**, **PDF**, pour exporter la liste affichée (en tenant compte des filtres et de la recherche en cours).

## Tableau des utilisateurs

| Colonne | Description |
|---|---|
| Utilisateur | Nom de l'utilisateur |
| Rôle | Rôle attribué (Facilitateur, Superviseur, Administrateur, etc.) |
| Email | Adresse e-mail de connexion |
| Sexe | Masculin / Féminin |
| Numéros | Numéro(s) de téléphone |
| Structure | Structure de rattachement |
| Statut | Statut du compte |
| Crée le | Date de création du compte |
| Action | Actions disponibles sur la ligne |

### Actions disponibles

- **Voir** : affiche le détail de l'utilisateur.
- **Modifier** : ouvre le formulaire pré-rempli pour mettre à jour l'utilisateur (rôle, structure, statut, informations personnelles, etc.).
- **Supprimer** : supprime l'utilisateur.

:::tip
C'est depuis cette page qu'un administrateur crée le compte (email + mot de passe) d'un nouvel utilisateur, voir [Connexion — Je n'ai pas encore de compte](../01-connexion.md).
:::
