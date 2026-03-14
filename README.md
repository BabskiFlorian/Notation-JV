# 🎮 Notation de jeu vidéo

Site web permettant de **rechercher un jeu vidéo et générer automatiquement un classement détaillé par critères** grâce à une IA (LLM).

L’utilisateur entre simplement le nom d’un jeu et le site affiche :

* les informations du jeu
* un score par critère (gameplay, visuel, immersion…)
* un résumé généré par IA
* les avis récents des joueurs (moins de 48h)

---

# 🎯 Objectif du projet

Créer une plateforme capable de :

* analyser des avis récents de joueurs
* générer un score détaillé pour un jeu
* fournir une synthèse claire de l’opinion des joueurs
* classer les jeux selon différents critères

Ce projet sert aussi à **apprendre React et l'intégration d'une IA dans un site web.**

---

# 🧠 Fonctionnalités principales

### 🔎 Recherche de jeux

L'utilisateur entre un jeu dans la barre de recherche.

Exemple :

```
Elden Ring
```

Le site récupère automatiquement :

* description
* genre
* date de sortie
* images

---

### 📊 Analyse par critères

L’IA génère un score pour plusieurs critères :

* Gameplay
* Visuel
* Immersion
* Musique
* Interface / UI
* Histoire
* Durée de vie
* Difficulté
* Originalité
* Performance technique

Exemple :

```
Gameplay : 9/10
Visuel : 9/10
Immersion : 10/10
Interface : 7/10
Musique : 8/10
```

---

### 💬 Analyse des avis récents

Le système récupère des avis récents provenant de différentes sources et l’IA génère :

* un résumé global
* les points positifs
* les points négatifs
* la tendance récente

Exemple :

Points positifs :

* monde ouvert très immersif
* combats profonds

Points négatifs :

* optimisation PC critiquée


---

# 🧰 Stack technique

Frontend :

* React
* HTML / CSS
* JavaScript

Backend :

* Node.js ou Python

Base de données :

* PostgreSQL ou MongoDB

IA :

* LLM (OpenAI, Mistral, LLaMA)

API jeux :

* RAWG Video Games Database API

---

# 📦 Structure du projet

```
game-ranking/
│
├── frontend/
│   ├── components
│   ├── pages
│   └── search
│
├── backend/
│   ├── api
│   ├── services
│   └── llm
│
├── database/
│
└── README.md
```

---


# 🚀 Évolutions possibles

Fonctionnalités futures :

* comparaison entre deux jeux
* classement automatique des meilleurs jeux
* système de comptes utilisateurs
* recommandation de jeux

---

# 🎓 Objectif personnel

Ce projet a pour but de :

* apprendre React
* comprendre l’intégration d’un LLM
* créer un projet complet full-stack


---

# 📅 Roadmap

Version 1 :

* recherche de jeu
* affichage des informations
* génération des scores

Version 2 :

* analyse des avis récents
* résumé IA

Version 3 :

* classement global des jeux
* comparaison entre jeux

---


Projet personnel pour apprendre :

* React
* Scrapping (avis sur les jeux)
* IA
* Analyse de données
