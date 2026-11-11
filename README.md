# Eventify — Event Discovery & Management Platform

**Auteur :** Rayen Essayeb  
**Année :** 2026  
**Version :** 1.0 — Front-end prototype

## 1. Présentation du concept

Eventify est un concept de plateforme web de découverte et de gestion d'événements. Son objectif est de proposer une expérience claire et premium pour explorer des événements, rechercher des activités par nom ou localisation, consulter leurs informations et enregistrer ses favoris.

Le projet est conçu comme un prototype de portfolio informatique. Les événements affichés sont des **données fictives de démonstration** et ne représentent pas des événements réellement disponibles.

## 2. Fonctionnalités front-end disponibles

- Page d'accueil avec présentation de la plateforme.
- Navigation responsive pour ordinateur, tablette et téléphone.
- Recherche par nom, catégorie et localisation.
- Filtres : Music, Technology, Art & Culture, Sports et Business.
- Cartes d'événements avec visuel, date, lieu, horaire et prix indicatif.
- Fenêtre de détails pour chaque événement.
- Favoris enregistrés localement dans le navigateur via `localStorage`.
- Tri des événements par date.
- Section de présentation destinée aux organisateurs.
- Fenêtres modales informatives pour les actions qui nécessitent un backend.
- Mise en page adaptée aux préférences de réduction des animations du système.

## 3. Technologies

- **HTML5** — structure sémantique des pages.
- **CSS3** — design responsive, animations, transitions et mise en page.
- **JavaScript Vanilla** — recherche, filtres, favoris, tri, navigation et fenêtres modales.
- **Google Fonts** — typographies Manrope et DM Sans.
- **Unsplash** — images distantes utilisées comme illustrations de démonstration.

Aucun framework JavaScript ou CSS n'est utilisé. Aucun serveur, PHP, base de données ou service backend n'est requis pour ouvrir cette version.

## 4. Installation et lancement

1. Télécharger et extraire `Eventify_Rayen_Essayeb.zip`.
2. Ouvrir le dossier `Eventify`.
3. Double-cliquer sur `index.html` pour lancer le site dans un navigateur moderne.

### Avec XAMPP Lite (facultatif)

1. Copier le dossier `Eventify` dans le dossier `www` de XAMPP Lite.
2. Démarrer Apache depuis le panneau XAMPP.
3. Ouvrir `http://localhost/Eventify/` dans le navigateur.

Le projet reste entièrement front-end : Apache sert simplement les fichiers statiques. Il n'est pas nécessaire de configurer MySQL.

## 5. État actuel du projet et limites

Cette livraison est un **prototype front-end uniquement**.

Les fonctions suivantes ne sont pas connectées à un backend et ne doivent pas être considérées comme opérationnelles : création réelle d'événements, authentification, inscription, réservation, paiement, gestion de billets, notifications et synchronisation de données entre utilisateurs.

Lorsqu'une action nécessite ces services, Eventify affiche le message suivant :

> This feature is currently under development. Eventify has not been officially launched yet. Backend integration is coming soon.

Les favoris sont conservés uniquement dans le stockage local du navigateur utilisé. Ils ne sont pas synchronisés entre appareils ou comptes.

Les images distantes et les polices nécessitent une connexion Internet. Si elles ne se chargent pas, les cartes conservent leur structure et leurs couleurs de fond.

## 6. Améliorations futures

- Développer une API backend et une base de données.
- Ajouter l'inscription, la connexion et les profils utilisateurs.
- Construire un tableau de bord organisateur avec création, modification et suppression d'événements.
- Ajouter une gestion réelle des réservations et des billets.
- Intégrer un prestataire de paiement sécurisé.
- Ajouter une carte interactive et des filtres avancés.
- Mettre en place des notifications et des rappels.
- Ajouter une modération, une validation des événements et des outils d'administration.
- Améliorer l'accessibilité, les tests et l'optimisation des performances.

## 7. Structure du projet

```text
Eventify/
├── index.html
├── style.css
├── script.js
└── README.md
```

## 8. Auteur

**Rayen Essayeb — 2026**

Eventify est un projet personnel de démonstration destiné à un portfolio informatique et à un dossier de candidature académique. Il présente une interface et des interactions côté client sans prétendre fournir des services backend ou transactionnels.
