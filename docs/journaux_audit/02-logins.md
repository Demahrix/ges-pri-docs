---
id: logins
title: Historique des connexions
sidebar_position: 2
slug: /audit-logs/logins
---

# Historique des connexions (`/audit-logs/logins`)

Cette page affiche les journaux (logs) de toutes les connexions effectuées sur la plateforme.

:::info[Permission requise]
L'accès à cette page nécessite la permission **Voir les journaux d'audit** (`READ_AUDIT_LOG`).
:::

![Page Historique des actions](/img/26.png)
![Page Historique des actions](/img/27.png)

## En-tête de la page

- **Bouton « Filtrer »** : ouvre une fenêtre modale avec les critères suivants :
  - Type (Connexion, Rafraîchissement du token)
  - Résultat (Succès, Échec)
  - Adresse IP
  - Enregistré par
  - Date de création (Min)
  - Date de création (Max)

  Trois boutons permettent de valider l'action : **Effacer** (réinitialise les critères), **Fermer** (ferme la fenêtre sans appliquer) et **Rechercher** (applique les filtres).
- **Boutons d'export** : **Copier**, **CSV**, **Excel**, **PDF**, pour exporter la liste affichée (en tenant compte des filtres en cours).

## Tableau de l'historique

| Colonne | Description |
|---|---|
| Type | Connexion ou Rafraîchissement du token |
| Utilisateur | Utilisateur concerné |
| Identifiant | Identifiant (email) utilisé pour la tentative |
| Adresse IP | Adresse IP à l'origine de la connexion |
| Adresse (Localisation) | Localisation approximative déduite de l'adresse IP |
| Navigateur | Navigateur / appareil utilisé |
| Résultat | Succès ou Échec |
| Date | Date et heure de la connexion |
