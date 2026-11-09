---
layout: ../../../layouts/Legal.astro
title: Politique de confidentialité — Deliv
project: Deliv
published: 16 septembre 2026
updated: 16 septembre 2026
description: Politique de confidentialité de l'application Deliv.
---

## Qui sommes-nous

Deliv est une application mobile éditée par Bluetech TG, destinée aux
livreurs indépendants pour organiser leurs tournées de livraison. Contact :
bluetechtg@gmail.com.

## Ce que Deliv ne fait pas

- Deliv **n'a pas de compte utilisateur** et ne demande ni email ni mot de
  passe.
- Deliv **n'a pas de serveur central** : il n'existe aucune base de données
  distante appartenant à Deliv qui reçoive ou stocke tes données.
- Deliv **ne contient aucune régie publicitaire** et **ne vend aucune
  donnée**.
- Deliv **ne suit pas ta position en continu** : la localisation n'est
  utilisée que lorsque tu appuies explicitement sur "Ma position" pour
  renseigner l'adresse d'un colis ou d'un marchand.

## Les données que tu saisis

Tout ce que tu saisis dans Deliv (noms et téléphones de tes clients et
marchands, adresses, montants, notes, photos de colis et preuves de
livraison) est stocké **uniquement sur ton téléphone**, dans une base de
données locale (SQLite). Ces informations ne quittent ton appareil que si
**tu** décides explicitement de les partager (par exemple le bouton
"Partager", qui ouvre le sélecteur natif du téléphone pour envoyer un
récapitulatif à un marchand par WhatsApp).

Si tu désinstalles l'application ou utilises la fonction "Réinitialiser"
dans Réglages, ces données sont supprimées définitivement — Deliv n'en
garde aucune copie ailleurs, puisqu'il n'y a pas d'ailleurs.

## Les services externes utilisés

Deliv communique avec deux services externes, uniquement pour assurer
certaines fonctionnalités :

- **Calcul d'itinéraire** (OSRM, `router.project-osrm.org`) : quand tu
  demandes à Deliv de calculer le meilleur ordre de passage pour tes
  colis, les coordonnées géographiques de tes points de livraison
  (latitude/longitude uniquement, aucun nom ni numéro de téléphone) sont
  envoyées à ce service public, en connexion chiffrée (HTTPS), pour
  obtenir les distances et durées. Ce service ne reçoit aucune
  information permettant de t'identifier.
- **Résolution de liens Google Maps raccourcis** : quand tu colles un
  lien court (type `maps.app.goo.gl`), Deliv suit ce lien pour en
  extraire les coordonnées, comme le ferait un navigateur.
- **Mises à jour de l'application** (Expo) : Deliv vérifie et télécharge
  ses propres mises à jour via l'infrastructure d'Expo, comme n'importe
  quelle application qui se met à jour.

Aucun de ces services ne reçoit tes données personnelles (noms,
téléphones, photos).

## Permissions demandées sur ton téléphone

- **Position (GPS)** : pour renseigner rapidement la localisation d'un
  colis ou d'un marchand sans avoir à coller un lien. Optionnelle — tu
  peux toujours coller un lien Google Maps à la place.
- **Appareil photo et photos** : pour joindre une photo du colis ou une
  preuve de livraison. Optionnel.
- **Notifications** : pour un rappel de fin de journée que tu peux
  activer/désactiver dans Réglages. Ces notifications sont programmées
  localement sur ton téléphone, rien n'est envoyé à un serveur pour ça.

Tu peux refuser ou révoquer chacune de ces permissions à tout moment dans
les réglages de ton téléphone ; l'app reste utilisable, avec juste la
fonctionnalité concernée en moins.

## Enfants

Deliv est un outil professionnel destiné aux livreurs ; il n'est pas
destiné aux enfants et ne collecte pas sciemment de données concernant des
enfants.

## Modifications de cette politique

Si cette politique change, la date de mise à jour en haut de la page sera
actualisée. Aucune notification séparée n'est prévue puisqu'il n'y a pas
de compte utilisateur pour t'écrire.

## Contact

Pour toute question sur cette politique ou sur tes données :
**bluetechtg@gmail.com**.
