# Kévin Fruchon — Développeur Python

Développeur Python freelance spécialisé dans la conception d'applications métier. Je développe principalement des API REST, des outils internes et des applications permettant d'automatiser des processus, centraliser des données et faciliter le travail d'utilisateurs non techniques.

Stack principale : **Python, FastAPI, Flask, PostgreSQL, SQLAlchemy/SQLModel, Pydantic**, avec une expérience complémentaire en **Next.js/React** côté frontend.

---

## Projets

### 🚗 GLF Auto — Plateforme garage automobile *(en production)*

Plateforme web complète pour un garage automobile : catalogue de véhicules et pièces d'occasion, formulaires de contact et de reprise, espace d'administration protégé pour la gestion du catalogue.

- **Statut** : déployé et utilisé par un client réel
- **Site** : [glf-auto.vercel.app](https://glf-auto.vercel.app/)
- **Stack** : FastAPI, PostgreSQL (Supabase), JWT, Next.js, Tailwind CSS
- **Backend** : [github.com/sangoaz/GLF-auto](https://github.com/sangoaz/GLF-auto)
- **Frontend** : [github.com/sangoaz/GLF-auto-Frontend](https://github.com/sangoaz/GLF-auto-Frontend)

Ce projet couvre l'ensemble du cycle : conception de l'API, modélisation des données, authentification, gestion de fichiers (photos), et un frontend connecté à l'API, déployé en production de bout en bout.

#### Apprentissage:
- **Déploiement d'une application complète**
- **Authentification JWT**
- **Gestion de fichiers**
- **Architecture frontend/backend**

#### Aperçu:
<img
  src="https://raw.githubusercontent.com/sangoaz/GLF-auto-Frontend/main/images/Accueil.png"
  width="900"
/>

<img
  src="https://raw.githubusercontent.com/sangoaz/GLF-auto-Frontend/main/images/Dashboard_Admin.png"
  width="900"
/>

<img
  src="https://raw.githubusercontent.com/sangoaz/GLF-auto-Frontend/main/images/Gestion_Vehicule.png"
  width="900"
/>


---

### 🚙 Car Fleet Management — API de gestion de flotte multi-entreprises

API backend pour la gestion d'une flotte de véhicules : suivi des entretiens, des pleins de carburant, alertes automatiques de maintenance. Architecture **multi-tenant** (plusieurs entreprises isolées) avec un système de **rôles et permissions** fin par ressource.

- - **Tests** : Pytest (tests automatisés couvrant les principaux cas métier)
- **Stack** : FastAPI, SQLModel/SQLAlchemy, PostgreSQL, Pydantic
- **Dépôt** : [github.com/sangoaz/Car-Fleet-Managment](https://github.com/sangoaz/Car-Fleet-Managment)

Le projet illustre une problématique proche de l'intégration de systèmes d'entreprise : isolation stricte des données entre organisations, contrôle d'accès vérifié à chaque opération sensible, et une suite de tests automatisés conséquente.

#### Apprentissage:
- **Architecture multi-tenant**
- **Rôles Complexes**
- **Tests**
- **PostgreSQL**

---

### 🎮 Brian's Buzzer — Application temps réel (WebSockets - en production)

Application de buzzer en temps réel pour quiz et blind-tests : plusieurs joueurs rejoignent une salle, et le système synchronise instantanément qui a buzzé en premier.

- **Démo** : [brian-s-buzzer.vercel.app](https://brian-s-buzzer.vercel.app)
- **Stack** : FastAPI, WebSockets, Next.js, React, Tailwind CSS
- **Dépôt** : [github.com/sangoaz/Brian-s-Buzzer](https://github.com/sangoaz/Brian-s-Buzzer)

Ce projet met en œuvre une architecture temps réel basée sur WebSockets permettant de synchroniser instantanément les actions des utilisateurs. Il illustre la gestion de connexions persistantes, la synchronisation d'état et la communication bidirectionnelle entre plusieurs clients.

#### Apprentissage:
- **Websocket**
- **Temps réel**
- **Synchronisation**
- **Gestion d'état**

---

## Autres projets

- **Loki Escape Game** — mini API FastAPI pour un escape game ludique (faux chat interactif), avec une architecture soignée malgré le format léger : séparation routes/logique métier/scénario, schémas Pydantic, store isolé. [Dépôt](https://github.com/sangoaz/Escape-Loki)

---

## Compétences techniques

| Domaine | Outils |
|---|---|
| Backend | Python, FastAPI, Flask |
| Bases de données | PostgreSQL, SQLAlchemy, SQLModel |
| Validation / API | Pydantic, REST, WebSockets |
| Authentification | JWT, gestion de rôles et permissions |
| Frontend | Next.js, React, Tailwind CSS |
| Tests | Pytest, pytest-cov |
| Déploiement | Render, Vercel, Supabase |

## Contact

- **GitHub** : [github.com/sangoaz](https://github.com/sangoaz)
- **Malt** : *https://www.malt.fr/profile/kevinfruchon*
- **Email** : kevin.fruchon@gmail.com
