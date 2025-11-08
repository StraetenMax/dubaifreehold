# 📧 DubaiFreehold MJML Conversion

> Reproduction fidèle d’un email HTML en MJML, automatisée avec Pug et Gulp.

---

## 🎯 Objectif du projet

Ce projet vise à recréer un email HTML existant en MJML tout en conservant son apparence originale. Il utilise **Pug** pour simplifier la structure HTML et **Gulp** pour automatiser les tâches de compilation. Le but est d’obtenir un rendu responsive, maintenable et compatible avec les principaux clients mail.

---

## 🧰 Technologies utilisées

- **MJML** : Framework pour emails responsives
- **Pug** : Templating HTML
- **Gulp** : Automatisation des tâches
- **Node.js** : Environnement d’exécution

---

## 📁 Structure du projet
dubaifreehold/
├── src/
│   ├── index.pug
│   ├── templates/
│   │   └── layout.pug
│   ├── includes/
│   │   ├── header.pug
│   │   ├── offre.pug
│   │   └── footer.pug
│   └── mjml/
│       └── index.mjml
├── dist/
│   ├── image/
│   ├── index.html
│   └── index.min.html
├── gulpfile.js
├── package.json
└── README.md            

---

## ⚙️ Installation et utilisation

1. **Installer les dépendances**
   ```bash
   npm install
