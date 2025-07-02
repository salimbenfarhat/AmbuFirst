# Spécifications Fonctionnelles - AmbuFirst MVP

Ce document détaille les fonctionnalités du MVP sous forme de "User Stories".

## Profil : Patient

**Objectif :** Permettre à un patient de commander un transport médicalisé simplement.

- **US1 (Création de compte) :** En tant que patient, je veux pouvoir créer un compte avec mon nom, email et mot de passe afin de sécuriser mes informations et réserver un transport.
- **US2 (Demande de transport) :** En tant que patient connecté, je veux pouvoir remplir un formulaire avec une adresse de départ, une adresse d'arrivée, une date et une heure, afin de soumettre une demande de transport.
- **US3 (Suivi de demande) :** En tant que patient, je veux pouvoir consulter une page qui liste mes demandes passées et en cours avec leur statut (En attente, Confirmée, Refusée), afin de savoir où en est ma réservation.

## Profil : Ambulancier

**Objectif :** Permettre à un ambulancier de gérer les demandes de transport efficacement.

- **US4 (Tableau de bord) :** En tant qu'ambulancier, je veux accéder à un tableau de bord qui affiche toutes les nouvelles demandes de transport en attente, afin de les traiter rapidement.
- **US5 (Gestion de demande) :** En tant qu'ambulancier, sur chaque demande, je veux pouvoir cliquer sur "Accepter" ou "Refuser", afin de mettre à jour le statut de la course et informer le patient.
- **US6 (Planning) :** En tant qu'ambulancier, je veux consulter une vue simple (type calendrier ou liste) de toutes les courses que j'ai acceptées, afin d'organiser ma journée.