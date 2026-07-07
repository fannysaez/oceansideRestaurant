# 03 — Structure du projet

## Arborescence complète

```text
reproduire-site-boostrap/
├── assets/
│   ├── img/
│   │   └── svg/
│   │       └── Logo.svg              # Logo du site (favicon / navbar)
│   ├── maquette/                     # Exports de la maquette Figma (référence visuelle)
│   │   ├── 01 Desktop Layers.png
│   │   ├── 02 Mobile Layers.png
│   │   └── variables css réutilisables.png
│   └── oceanside-restaurant/         # Documentation du projet (ce dossier)
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

## Rôle de chaque fichier principal

| Fichier | Rôle |
| --- | --- |
| `index.html` | Structure HTML5 de la page (Hero, About, Menu, Reserve, Footer) |
| `styles/globals.css` | Design tokens `:root`, surcharge des variables Bootstrap `--bs-*` |
| `styles/utilities.css` | Styles custom mobile first, par-dessus Bootstrap |
| `assets/img/svg/Logo.svg` | Logo utilisé dans la navbar |
| `assets/maquette/` | Exports de la maquette Figma (référence) |

> Le projet ne comporte pas de build tool (pas de npm/webpack) : Bootstrap est chargé via **CDN**, et les fichiers CSS custom sont liés directement dans `index.html`, **toujours après** `bootstrap.min.css` pour pouvoir le surcharger proprement.

---

<p align="center">
  <a href="02-maquette-figma.md"><img src="https://img.shields.io/badge/-PR%C3%89C%C3%89DENT-5A8F76?style=for-the-badge" alt="Précédent"></a> &nbsp;&nbsp; <a href="04-design-system.md"><img src="https://img.shields.io/badge/-SUIVANT-5A8F76?style=for-the-badge" alt="Suivant"></a>
</p>
