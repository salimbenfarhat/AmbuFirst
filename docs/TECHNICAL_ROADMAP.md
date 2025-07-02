# Roadmap Technique - AmbuFirst MVP

Ce document décrit les étapes techniques prévues pour le développement du MVP d'AmbuFirst.

## V0 : Définition des Besoins (Phase actuelle)

- [x] Initialisation du repository Git.
- [x] Définition des features du MVP.
- [x] Création des spécifications fonctionnelles (`SPECIFICATIONS_FONCTIONNELLES.md`).
- [x] Création de la roadmap technique (`ROADMAP_TECHNIQUE.md`).

## V1 : Initialisation du Projet & Setup de Base

- **Branche Git :** `v1-init-project`
- **Objectifs :**
    - Initialiser un projet **Next.js** avec **TypeScript**.
    - Configurer **Tailwind CSS** pour le styling.
    - Mettre en place **ESLint** et **Prettier** pour la qualité du code.
    - Créer la structure de base des dossiers (`components`, `app`, `lib`, etc.).

## V2 : Base de Données et Authentification

- **Branche Git :** `v2-auth-database`
- **Objectifs :**
    - Choisir et intégrer une solution BaaS (Backend-as-a-Service) comme **Supabase** ou **Firebase**.
        - **Tables à créer :** `users`, `transports`.
    - Mettre en place le système d'authentification (inscription / connexion par email-mot de passe).
    - Mettre en place les pages de connexion, d'inscription et la protection des routes.

## V3 : Fonctionnalités Côté Patient

- **Branche Git :** `v3-patient-features`
- **Objectifs :**
    - Créer le formulaire de demande de transport.
    - Créer la page listant l'historique des transports du patient.
    - Développer les appels API pour créer et lire les transports.

## V4 : Fonctionnalités Côté Ambulancier

- **Branche Git :** `v4-ambulance-features`
- **Objectifs :**
    - Créer le tableau de bord affichant les nouvelles demandes.
    - Implémenter les actions "Accepter" / "Refuser" une course.
    - Créer la vue "Planning" des courses acceptées.
    - Développer les appels API pour mettre à jour et lister les transports.

## V5 : Déploiement

- **Branche Git :** `v5-deployment`
- **Objectifs :**
    - Configurer le déploiement continu avec **Vercel**.
    - Mettre en place les variables d'environnement.
    - Lancer une première version accessible en ligne pour les tests.