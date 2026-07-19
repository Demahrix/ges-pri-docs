---
id: actions
title: Historique des actions
sidebar_position: 1
slug: /audit-logs/actions
---

# Historique des actions (`/audit-logs/actions`)

Cette page affiche les journaux (logs) de toutes les actions effectuées sur la plateforme.

:::info[Permission requise]
L'accès à cette page nécessite la permission **Voir les journaux d'audit** (`READ_AUDIT_LOG`).
:::

![Page Historique des actions](/img/24.png)
![Page Historique des actions](/img/25.png)

## En-tête de la page

- **Bouton « Filtrer »** : ouvre une fenêtre modale avec les critères suivants :
  - Action
  - Donnée
  - Date de création (Min)
  - Date de création (Max)
  - Enregistré par

  Trois boutons permettent de valider l'action : **Effacer** (réinitialise les critères), **Fermer** (ferme la fenêtre sans appliquer) et **Rechercher** (applique les filtres).
- **Boutons d'export** : **Copier**, **CSV**, **Excel**, **PDF**, pour exporter la liste affichée (en tenant compte des filtres en cours).

## Tableau de l'historique

| Colonne | Description |
|---|---|
| Action | Type d'action effectuée (création, modification, suppression, etc.) |
| Utilisateur | Utilisateur ayant effectué l'action |
| Date | Date et heure de l'action |
| Action *(colonne d'actions)* | Action disponible sur la ligne |

### Action disponible

- **Voir** : affiche le détail de l'entrée du journal. Ce bouton n'est disponible que pour certains types d'action ; il n'apparaît pas systématiquement sur toutes les lignes.
