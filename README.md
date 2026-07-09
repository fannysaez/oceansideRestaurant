<div align="center">

# 🌊 Oceanside Restaurant — Reproduction Bootstrap d'une maquette Figma

**HTML5 · CSS3 · Bootstrap 5** — Projet réalisé dans le cadre de la formation **CDA (Simplon)**, 2026.

Reproduction pixel-close, **mobile first**, d'une maquette Figma « Oceanside Restaurant » à l'aide du framework **Bootstrap 5**, surchargé par un design system CSS personnalisé (variables, typographies, composants).

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3.3-7952B3?style=flat&logo=bootstrap&logoColor=white)
![Mobile First](https://img.shields.io/badge/Approche-Mobile%20First-96CDB0?style=flat)

🔗 **Démo en ligne :** [oceanside-restaurant.vercel.app](https://oceanside-restaurant.vercel.app/)

</div>

---

## 📑 Table des matières

Toute la documentation détaillée du projet est découpée en pages, dans [`assets/oceanside-restaurant/`](assets/oceanside-restaurant), avec navigation précédent/suivant en bas de chaque page.

| # | Page | Contenu |
| --- | --- | --- |
| 01 | [Présentation du projet](assets/oceanside-restaurant/01-presentation.md) | Contexte, objectif, sections du site à reproduire |
| 02 | [Aperçu de la maquette Figma](assets/oceanside-restaurant/02-maquette-figma.md) | Captures desktop/mobile, méthode de vérification |
| 03 | [Structure du projet](assets/oceanside-restaurant/03-structure-projet.md) | Arborescence complète, rôle de chaque fichier |
| 04 | [Design system / variables CSS](assets/oceanside-restaurant/04-design-system.md) | Palette de couleurs, typographies |
| 05 | [Technologies utilisées](assets/oceanside-restaurant/05-technologies.md) | HTML5, CSS3, Bootstrap 5.3.3, Google Fonts |
| 06 | [Lancer le projet en local](assets/oceanside-restaurant/06-lancer-en-local.md) | Clone, ouverture, serveur local |
| 07 | [Approche responsive / mobile first](assets/oceanside-restaurant/07-responsive-mobile-first.md) | Méthode mobile first, exemple concret |

---

## 🖼️ Maquette (desktop, mobile & variables CSS)

Exports de la maquette Figma utilisés comme référence visuelle pour la reproduction pixel-close, disponibles dans [`assets/maquette/`](assets/maquette).

<div align="center">
  <img src="assets/maquette/01%20Desktop%20Layers.webp" alt="Maquette Desktop" width="280" align="top">
  <img src="assets/maquette/02%20Mobile%20Layers.webp" alt="Maquette Mobile" width="130" align="top">
  <img src="assets/maquette/variables%20css%20r%C3%A9utilisables.webp" alt="Variables CSS réutilisables" width="200" align="top">
  <br>
  <sub><b>Desktop</b> · <b>Mobile</b> · <b>Variables CSS réutilisables</b></sub>
</div>

Palette de couleurs, typographies et espacements extraits de la maquette, repris dans [`styles/globals.css`](styles/globals.css).

---

## 🗂️ Structure du projet

```text
reproduire-site-boostrap/
├── assets/
│   ├── img/
│   │   └── svg/
│   │       └── Logo.svg              # Logo du site (favicon / navbar)
│   ├── maquette/                     # Exports de la maquette Figma (référence visuelle)
│   │   ├── 01 Desktop Layers.webp
│   │   ├── 02 Mobile Layers.webp
│   │   └── variables css réutilisables.webp
│   └── oceanside-restaurant/         # Documentation paginée du projet
│       ├── 01-presentation.md
│       ├── 02-maquette-figma.md
│       ├── 03-structure-projet.md
│       ├── 04-design-system.md
│       ├── 05-technologies.md
│       ├── 06-lancer-en-local.md
│       └── 07-responsive-mobile-first.md
├── styles/
│   ├── globals.css                   # Design tokens : couleurs, typographies, surcharge des variables Bootstrap (--bs-*)
│   └── utilities.css                 # Styles custom du projet, mobile first, par-dessus Bootstrap
├── index.html                        # Page unique (Hero, About, Menu, Reserve, Footer)
└── README.md
```

---

<p align="center">
  <a href="assets/oceanside-restaurant/01-presentation.md"><img src="https://img.shields.io/badge/-COMMENCER-C18D52?style=for-the-badge" alt="Commencer"></a>
</p>
