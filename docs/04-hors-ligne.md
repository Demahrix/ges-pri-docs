---
id: hors-ligne
title: Hors ligne
sidebar_position: 5
slug: /hors-ligne
---

# Hors ligne

Cette section permet de saisir des fiches d'identification sur le terrain **sans connexion internet**, puis de les synchroniser avec la plateforme une fois la connexion rétablie.

:::info[Permission requise]
L'accès à cette section nécessite la permission **Voir les données hors ligne** (`READ_OFFLINE_DATA`).
:::

## Gérer (`/hors-ligne/gerer`)

Page de gestion des fiches saisies hors ligne : suivi de leur état de synchronisation, envoi manuel vers le serveur, résolution des éventuels conflits.

:::info[Permission requise]
L'accès à cette page nécessite la permission **Gérer les données hors ligne** (`HANDLE_OFFLINE_DATA`), en plus de `READ_OFFLINE_DATA`.
:::

## Identifications (`/hors-ligne/identifications`)

Liste des fiches d'identification saisies en mode hors ligne, avec leur statut (en attente de synchronisation, synchronisée, en erreur). C'est également depuis cette page que ces fiches, une fois remontées sur la plateforme, apparaissent parmi les « fiches hors ligne en attente » signalées sur le [tableau de bord](./dashboard.md).
