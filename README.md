# 👑 Quiz Queen

Une application de quiz interactive développée en JavaScript, avec suivi de progression en temps réel.

> 🎓 Projet réalisé dans le cadre de la formation développeur web chez **Ada Tech School**.
> Fork du projet [Stalissy/Gisel-adaquiz-Alicia-Off-Gewen](https://github.com/Stalissy/Gisel-adaquiz-Alicia-Off-Gewen)

## 📋 Description

**Quiz Queen** (nom interne : `adaquiz2`) est une petite application web permettant de répondre à une série de questions tout en visualisant sa progression grâce à une barre affichée en haut de l'écran (`0% de progression` → `100%`).

## ✨ Fonctionnalités

- Interface de quiz simple et rapide
- Barre de progression dynamique
- Design rétro avec les polices [Tiny5](https://fonts.google.com/specimen/Tiny5) et [VT323](https://fonts.google.com/specimen/VT323)
- Application 100% JavaScript (sans framework), buildée avec [Vite](https://vitejs.dev/)

## 🛠️ Stack technique

| Techno | Usage |
|--------|-------|
| JavaScript | Logique de l'application |
| CSS | Mise en forme |
| HTML | Structure |
| Vite | Bundler / serveur de développement |

## 📦 Installation

```bash
# Cloner le dépôt
git clone https://github.com/Offichigo/Quiz-Queen-.git
cd Quiz-Queen-

# Installer les dépendances
npm install
```

## 🚀 Utilisation

```bash
# Lancer le serveur de développement
npm run dev

# Construire le projet pour la production
npm run build

# Prévisualiser le build de production
npm run preview
```

L'application sera accessible sur `http://localhost:5173` (port par défaut de Vite).

## 📁 Structure du projet

```
Quiz-Queen-/
├── public/          # Fichiers statiques
├── src/             # Code source (logique + styles)
│   ├── main.js
│   └── style.css
├── index.html        # Point d'entrée
├── package.json
└── README.md
```

## 🎯 Contexte pédagogique

Ce projet a été réalisé dans le cadre d'un exercice de la formation **Ada Tech School**, visant à mettre en pratique :

- la manipulation du DOM en JavaScript
- la gestion d'état simple (avancement dans le quiz)
- l'utilisation de Vite comme outil de build
- le travail en groupe avec Git/GitHub

## 🤝 Contributeurs·rices

Projet réalisé en groupe dans le cadre de la formation Ada Tech School.

## 📄 Licence

Projet pédagogique réalisé dans le cadre de la formation Ada Tech School — usage éducatif.
