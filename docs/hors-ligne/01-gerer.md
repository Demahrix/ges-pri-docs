---
id: gerer
title: Gérer
sidebar_position: 1
slug: /hors-ligne/gerer
---

# Gérer (`/hors-ligne/gerer`)

Cette page permet de synchroniser les données saisies hors ligne avec le serveur, ainsi que les référentiels nécessaires à la saisie hors ligne.

:::info[Permission requise]
L'accès à cette page nécessite la permission **Gérer les données hors ligne** (`HANDLE_OFFLINE_DATA`), en plus de `READ_OFFLINE_DATA`.
:::

![Page Gérer (hors ligne)](/img/5.png)

La page comporte deux boutons.

## Envoyer en ligne

Le bouton **Envoyer en ligne** permet d'envoyer au serveur les fiches d'identification qui ont été enregistrées hors ligne.

Juste au-dessus du bouton, un compteur **« X enregistrement(s) »** indique le nombre de fiches **« En attente d'envoi »**, c'est-à-dire saisies hors ligne mais pas encore synchronisées avec le serveur.

## Référentiels distants

Le bouton **Référentiels distants** permet de synchroniser localement les données de référence suivantes, indispensables pour pouvoir saisir une fiche d'identification hors ligne :

- Type d'handicap
- Régions
- Provinces
- Communes
- Villages / Secteurs
- Structures

:::tip
Il est recommandé de synchroniser les référentiels distants **avant** de partir sur le terrain sans connexion, afin de disposer des listes à jour (Régions, Provinces, Communes, Villages/Secteurs, Structures, Types d'handicap) au moment de la saisie.
:::
