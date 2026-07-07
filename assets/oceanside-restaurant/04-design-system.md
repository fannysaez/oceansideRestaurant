# 04 — Design system / variables CSS

Les tokens de couleur et de typographie de la maquette Figma sont centralisés dans [`styles/globals.css`](../../styles/globals.css), puis réinjectés dans les variables `--bs-*` de Bootstrap 5.3 afin que tous ses composants (boutons, navbar…) héritent automatiquement de la charte, sans surcharger chaque composant un par un.

## Palette de couleurs

| Variable | Couleur | Usage |
| --- | --- | --- |
| `--color-ivoire` | `#EEE8B2` | Fond clair, `--bs-light` |
| `--color-sable` | `#C18D52` | Accent principal, `--bs-primary` |
| `--color-abysse` | `#081B1B` | Fond sombre, `--bs-dark` |
| `--color-algue` | `#203B37` | Fond sections sombres (menu, cartes) |
| `--color-mineral` | `#5A8F76` | Accent secondaire, `--bs-secondary` |
| `--color-ecume` | `#96CDB0` | Accent clair (bande décorative) |
| `--color-brume` | `#D7EFE3` | Texte clair (nav, corps du hero) |
| `--color-blanc` | `#FFFFFF` | Blanc pur |

## Typographies

| Variable | Police | Usage |
| --- | --- | --- |
| `--font-display` | Cormorant Garamond (+ Georgia en fallback) | Titres, poids Bold |
| `--font-body` | Inter (+ system-ui en fallback) | Texte courant |

Les deux polices sont chargées depuis Google Fonts directement dans `index.html`.

---

<p align="center">
  <a href="03-structure-projet.md"><img src="https://img.shields.io/badge/-PR%C3%89C%C3%89DENT-5A8F76?style=for-the-badge" alt="Précédent"></a> &nbsp;&nbsp; <a href="05-technologies.md"><img src="https://img.shields.io/badge/-SUIVANT-5A8F76?style=for-the-badge" alt="Suivant"></a>
</p>
