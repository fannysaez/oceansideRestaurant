# 07 — Approche responsive / mobile first

Le fichier [`styles/utilities.css`](../../styles/utilities.css) suit strictement la méthode **mobile first** :

1. Les styles **sans media query** ciblent le mobile en premier (tailles de police, empilement des visuels décoratifs, etc.), avec les valeurs vérifiées directement sur les calques Figma mobile.
2. Les breakpoints Bootstrap `@media (min-width: 768px)` (tablette/desktop) et `@media (min-width: 992px)` (grand desktop) viennent ensuite **enrichir** ces styles — jamais de `max-width`.
3. Le fichier `bootstrap.min.css` n'est **jamais modifié directement** : tout le custom vient le surcharger par-dessus, dans `globals.css` et `utilities.css`.

## Exemple concret

Le titre du Hero passe de 54px (mobile, node Figma `"Mobile hero title"`) à 84px (desktop ≥ 992px, node Figma `"Hero title"`), et le visuel décoratif passe d'un positionnement `absolute` (superposé derrière le texte, mobile) à un comportement de colonne Bootstrap classique (`col-md-5`) à partir de 768px.

---

<p align="center">
  <a href="06-lancer-en-local.md"><img src="https://img.shields.io/badge/-PR%C3%89C%C3%89DENT-5A8F76?style=for-the-badge" alt="Précédent"></a> &nbsp;&nbsp; <a href="../../README.md"><img src="https://img.shields.io/badge/-RETOUR%20AU%20SOMMAIRE-C18D52?style=for-the-badge" alt="Retour au sommaire"></a>
</p>
