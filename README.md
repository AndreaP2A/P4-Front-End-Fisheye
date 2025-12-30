<div align="center">
  <img src="https://andreap2a.github.io/P4-Front-End-Fisheye/assets/images/logo.png" alt="FishEye Logo" width="200">
</div>

# 📸 FishEye — Plateforme de Photographes Freelance
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

FishEye est un site web dynamique et accessible permettant aux photographes indépendants de présenter leur portfolio de manière professionnelle. Le projet repose sur une architecture JavaScript modulaire et une conformité stricte aux normes d'accessibilité.

## 📌 Présentation du Projet
FishEye est une plateforme permettant aux photographes indépendants de présenter leurs travaux. L'objectif de ce projet était de refondre un site existant pour construire une interface fluide et performante tout en garantissant une expérience inclusive. L'accent a été mis sur la programmation système (Design Patterns) et le respect strict des critères **WCAG 2.1** pour permettre une navigation optimale à tous les utilisateurs.

## 🎯 Objectifs techniques
- **Design Patterns :** Mise en œuvre du pattern *Factory* pour la création dynamique des composants média (Images et Vidéos).
- **Accessibilité (A11y) :** Gestion avancée du focus, navigation clavier complète, et utilisation sémantique des attributs ARIA.
- **JavaScript ES6+ :** Utilisation de la programmation orientée objet (classes), des modules, et de la manipulation dynamique du DOM via Fetch API.
- **Interactivité :** Développement d'une Lightbox immersive, de systèmes de tri personnalisés et de formulaires dynamiques.

## ✨ Fonctionnalités & Accessibilité
Le projet a été conçu pour être à la fois esthétique et fonctionnel, avec une attention particulière portée aux détails techniques :

### ♿ Accessibilité Web (WCAG 2.1)
Conformité totale aux technologies d'assistance : navigation par tabulation, étiquettes ARIA descriptives et contrastes optimisés.

### 🖼️ Galerie Dynamique & Patterns
Utilisation d'une "Factory" pour générer les cartes des photographes et leurs médias respectifs à partir de données JSON.

### 🔍 Système de Tri
Filtres intelligents permettant d'organiser les médias par popularité (likes), date ou titre, avec mise à jour instantanée du DOM.

### 🎞️ Lightbox Immersive
Une visionneuse plein écran permettant de naviguer entre les médias à l'aide des flèches du clavier ou de la souris.

### ❤️ Compilation des Likes
Un compteur global en temps réel qui s'actualise lors de l'interaction avec le bouton "Like" de chaque média.

## 🚀 Installation et Utilisation
### Prérequis
- Un navigateur web moderne (Chrome, Firefox, Edge, Safari).

### Installation locale
1. Clonez le dépôt :
   ```bash
   git clone https://github.com/AndreaP2A/P4-Front-End-Fisheye.git
   ```
2. Accédez au dossier :
   ```bash
   cd Front-End-Fisheye
   ```
3. Ouvrez le fichier `index.html` dans votre navigateur.

## 🛠️ Structure du projet
L'architecture suit une logique modulaire pour assurer la maintenabilité du code :

```text
.
├── assets/             # Images, icônes et logos
├── css/                # Feuilles de style CSS3
├── data/               # Fichier JSON des photographes et médias
├── scripts/            # Logique JavaScript (Modules ES6)
│   ├── factories/      # Factory Pattern (Media & Photographer)
│   ├── pages/          # Logique spécifique aux pages
│   ├── templates/      # Génération dynamique du HTML
│   └── utils/          # Modales, Lightbox, et gestionnaires d'événements
├── index.html          # Page d'accueil (Liste des photographes)
└── photographer.html   # Page de profil détaillée
```

## 🌐 Aperçu en ligne
Le projet est accessible en ligne via GitHub Pages : 
👉 [Consulter la démo FishEye](https://andreap2a.github.io/P4-Front-End-Fisheye/index.html)

## 🎓 Contexte Pédagogique
Ce projet constitue le **4ème projet pratique** de mon parcours **Développeur d'application (CDA) JavaScript / React (Bac+3/+4)** chez OpenClassrooms. Il m'a permis de perfectionner mes compétences en JavaScript modulaire, de maîtriser les **Design Patterns** (notamment le pattern Factory) et d'intégrer les enjeux critiques de l'**accessibilité numérique (WCAG)** au cœur du développement frontend.

---

## 👨‍💻 Auteur
**Andréa PORCHE**

- **GitHub :** [@AndreaP2A](https://github.com/AndreaP2A)
- **LinkedIn :** [Andrea Porche](https://www.linkedin.com/in/andrea-porche-763445173/)
- **Email :** andrea.porche2a@gmail.com
