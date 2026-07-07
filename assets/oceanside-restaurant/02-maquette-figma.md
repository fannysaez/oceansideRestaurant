# 02 — Aperçu de la maquette Figma

Les captures de la maquette originale sont disponibles dans [`assets/maquette/`](../maquette) et servent de référence pixel-close tout au long du développement.

| Fichier | Contenu |
| --- | --- |
| [`01 Desktop Layers.png`](../maquette/01%20Desktop%20Layers.png) | Maquette desktop complète (calques Figma) |
| [`02 Mobile Layers.png`](../maquette/02%20Mobile%20Layers.png) | Maquette mobile complète (calques Figma) |
| [`variables css réutilisables.png`](../maquette/variables%20css%20réutilisables.png) | Page Figma listant les tokens couleur/typo réutilisables du design system |

---

## Méthode de vérification

Chaque valeur reprise dans le code (tailles de police, largeurs de boîtes, positions des formes décoratives) est vérifiée directement sur les calques Figma correspondants plutôt qu'estimée à l'œil — les commentaires du CSS (`styles/utilities.css`) référencent le nom du node Figma concerné (ex. `"Mobile hero title" (1:242)`).

---

<p align="center">
  <a href="01-presentation.md"><img src="https://img.shields.io/badge/-PR%C3%89C%C3%89DENT-5A8F76?style=for-the-badge" alt="Précédent"></a> &nbsp;&nbsp; <a href="03-structure-projet.md"><img src="https://img.shields.io/badge/-SUIVANT-5A8F76?style=for-the-badge" alt="Suivant"></a>
</p>
