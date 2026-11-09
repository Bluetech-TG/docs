---
layout: ../../layouts/Legal.astro
title: Politique de confidentialité — HotelPilot Suite
project: HotelPilot Suite
published: 16 septembre 2026
updated: 16 septembre 2026
description: Politique de confidentialité de la plateforme HotelPilot Suite.
---

## Qui sommes-nous

HotelPilot Suite est une plateforme SaaS de gestion hôtelière (PMS) éditée
par Bluetech TG, destinée aux hôtels et groupes hôteliers pour gérer leurs
réservations, leur facturation et leurs opérations quotidiennes. Contact :
bluetechtg@gmail.com.

## Deux publics concernés par cette politique

Cette politique s'adresse à deux publics différents :

- **Le personnel de l'hôtel abonné** (administrateurs, réceptionnistes,
  gouvernantes...), qui dispose d'un compte utilisateur sur HotelPilot
  Suite. Pour ces données, **HotelPilot Suite est responsable de
  traitement**.
- **Les clients de l'hôtel**, dont les informations (réservation, contact,
  pièce d'identité...) sont saisies par le personnel de l'hôtel dans le
  logiciel. Pour ces données, **l'hôtel reste responsable de traitement**
  et **HotelPilot Suite agit en tant que sous-traitant**, au sens du RGPD,
  pour le compte de l'hôtel.

## Les données que nous traitons

- **Compte utilisateur (personnel de l'hôtel)** : nom, email, téléphone,
  rôle et hôtel(s) rattaché(s), mot de passe (haché), et si activée, une
  clé d'authentification à deux facteurs (MFA/TOTP).
- **Données de facturation de l'abonnement hôtel** : plan souscrit,
  historique de facturation. Les moyens de paiement eux-mêmes (numéro de
  carte, identifiants Mobile Money) ne sont **jamais stockés sur nos
  serveurs** : ils transitent directement chez nos prestataires de
  paiement, Stripe (carte bancaire) et FedaPay (T-Money, Flooz, Orange
  Money).
- **Données opérationnelles saisies par le personnel de l'hôtel**, pour le
  compte de l'hôtel : réservations et séjours, fiches clients (nom,
  contact, et le cas échéant une photo de pièce d'identité prise à
  l'accueil), notes et extras facturés, mouvements de stock, messages
  échangés entre membres du personnel, journal d'activité.

## Hébergement et sous-traitants

- **Hébergement applicatif et base de données** : Render (infrastructure
  cloud), avec les données stockées dans une base PostgreSQL dédiée à
  HotelPilot Suite.
- **Paiement par carte** : Stripe.
- **Paiement Mobile Money** : FedaPay.
- **Mises à jour de l'application mobile compagnon** (à venir) : Expo,
  comme n'importe quelle application qui se met à jour.

Ces prestataires ne reçoivent que les données strictement nécessaires à
leur fonction (paiement, hébergement) et n'ont pas le droit de les
réutiliser à d'autres fins.

## Sécurité

- Connexions chiffrées (HTTPS) de bout en bout.
- Cloisonnement des données par hôtel (architecture multi-établissements) :
  le personnel d'un hôtel n'a accès qu'aux données de son propre
  établissement, selon son rôle.
- Authentification à deux facteurs disponible pour les comptes du
  personnel.
- Journal d'audit horodaté des actions effectuées dans le logiciel.

## Conservation des données

Les données sont conservées tant que le compte de l'hôtel est actif. En
cas de résiliation, l'hôtel peut demander la suppression ou l'export de
ses données à bluetechtg@gmail.com, sous réserve des durées de conservation
imposées par la réglementation comptable applicable (référentiel OHADA)
pour certaines pièces comptables et de facturation.

## Vos droits

Pour exercer un droit d'accès, de rectification ou de suppression sur tes
propres données de compte (personnel de l'hôtel), contacte
bluetechtg@gmail.com.

Si tu es un client d'un hôtel utilisant HotelPilot Suite et que tu
souhaites exercer ces droits sur les données saisies à ton sujet lors
d'une réservation ou d'un séjour, adresse ta demande directement à
l'hôtel concerné, qui reste responsable de traitement ; HotelPilot Suite
l'assiste dans le traitement de ta demande.

## Application mobile compagnon

Une application mobile pour le personnel de l'hôtel (messagerie interne,
gestion rapide des extras, etc.) est en cours de développement et n'est
pas encore publiée sur les stores. Cette politique de confidentialité
s'appliquera également à elle une fois disponible ; cette page sera mise
à jour en conséquence.

## Enfants

HotelPilot Suite est un outil professionnel destiné au personnel hôtelier
; il n'est pas destiné aux enfants et ne collecte pas sciemment de
données les concernant.

## Modifications de cette politique

Si cette politique change, la date de mise à jour en haut de la page sera
actualisée.

## Contact

Pour toute question sur cette politique ou sur le traitement de tes
données : **bluetechtg@gmail.com**.
