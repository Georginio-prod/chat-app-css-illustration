# Chat app CSS illustration (Frontend Mentor)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3-06B6D4?logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-5-646CFF?logo=vite&logoColor=white)
![Frontend Mentor](https://img.shields.io/badge/Frontend_Mentor-Challenge-3F54A3)

🔗 **Démo en ligne** : <https://chat-app-css-illustration-cyan-mu.vercel.app>
📦 **Code source** : <https://github.com/Georginio-prod/chat-app-css-illustration>
🎯 **Défi** : [Chat app CSS illustration](https://www.frontendmentor.io/challenges/chat-app-css-illustration-O5auMkFqY) (niveau *Intermediate*)

---

## 📌 Présentation

Reproduction **en pur CSS** d'une illustration de téléphone affichant une conversation de chat : coque du téléphone, encoche, en-tête avec avatar, bulles de messages envoyés / reçus, images miniatures, offres avec bouton radio et champ de saisie. Aucune image n'est utilisée pour le téléphone lui-même — tout est construit avec des `div`, des bordures arrondies, des ombres et des dégradés.

Réalisé en **HTML sémantique + Tailwind CSS**, servi par **Vite** (rechargement à chaud et build optimisé),
sans framework JavaScript : l'objectif est la maîtrise du CSS et du responsive.

## ✨ Fonctionnalités

- Téléphone entièrement dessiné en CSS (cadre, encoche, écran, ombre portée).
- Bulles de discussion alignées à gauche / à droite avec coins asymétriques.
- Cartes d'offre avec dégradé violet → magenta et bouton radio circulaire.
- Fonds décoratifs (formes arrondies) positionnés en absolu derrière le contenu.
- Responsive : téléphone au-dessus du texte sur mobile, côte à côte sur desktop.

## 🛠️ Stack

| Élément | Détail |
|---|---|
| Structure | HTML5 sémantique |
| Styles | Tailwind CSS 3 (config personnalisée), PostCSS, Autoprefixer |
| Outils | Vite 5 (dev server + build) |
| Maquette | Frontend Mentor — mobile 375px / desktop 1440px |

## 📁 Structure

```
chat-app-css-illustration/
├── index.html              # Toute la structure de la page
├── style.css               # Directives Tailwind + styles complémentaires
├── main.js                 # Importe la feuille de style (point d'entrée Vite)
├── tailwind.config.js      # Couleurs / polices du style guide
├── postcss.config.*        # Tailwind + Autoprefixer
├── public/                 # Images, icônes, fonds de la maquette
└── package.json
```

## 🚀 Installation & lancement

```bash
git clone https://github.com/Georginio-prod/chat-app-css-illustration.git
cd chat-app-css-illustration
npm install
npm run dev          # http://localhost:5173
```

`npm run build` génère le site statique dans `dist/` ; `npm run preview` le prévisualise.

## 🌐 Déploiement

Déployé sur **Vercel** (framework Vite, sortie `dist/`). Aucune variable d'environnement.

## 🎓 Ce que ce projet démontre

Pseudo-éléments, `border-radius` asymétriques, dégradés linéaires, positionnement absolu et composition d'un objet complexe sans image.

---

## 👤 Auteur

**Komla Etonam Georges EKLOU** (Georginio) — Développeur Full Stack Web & Web3

[![GitHub](https://img.shields.io/badge/GitHub-Georginio--prod-181717?logo=github)](https://github.com/Georginio-prod)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profil-0A66C2?logo=linkedin)](https://www.linkedin.com/in/komla-etonam-georges-eklou-68518b23b)
[![Portfolio](https://img.shields.io/badge/Portfolio-georginio.w3frame.com-6C63FF)](https://georginio.w3frame.com/)

> 📚 Tous mes projets sont listés et documentés sur mon [profil GitHub](https://github.com/Georginio-prod).
