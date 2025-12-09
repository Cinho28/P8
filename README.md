# Projet 8 - Nina Carducci (Optimisation SEO & Accessibilité)

Ce projet s'inscrit dans le parcours "Intégrateur Web" d'OpenClassrooms. L'objectif était d'optimiser un site existant pour améliorer ses performances, son référencement (SEO) et son accessibilité.

## 🚀 Objectifs atteints

- **Performance :** Score Lighthouse passé de **75** à **99/100**.
- **SEO :** Score passé à **100/100**.
- **Accessibilité :** Site entièrement navigable au clavier et compatible lecteurs d'écran.

## 🛠 Actions Techniques Réalisées

### 1. Optimisation des Images

- Conversion de toutes les images au format **WebP** (gain de poids > 80%).
- Mise en place de l'attribut `srcset` pour servir des images adaptées à la taille de l'écran (Mobile / Tablette / Desktop).
- Ajout des attributs `width` et `height` pour éviter le **CLS** (Cumulative Layout Shift).

### 2. Optimisation du Chargement (LCP)

- Utilisation de `loading="lazy"` pour les images sous la ligne de flottaison.
- Utilisation de `fetchpriority="high"` pour l'image principale du slider (LCP).
- Scripts JS différés avec `defer`.

### 3. Sémantique & Accessibilité

- Restructuration du HTML (`<header>`, `<main>`, `<footer>`).
- Ajout des textes alternatifs (`alt`) sur toutes les images.
- Correction des contrastes et de la navigation.

### 4. Débuggage

- Correction du script de la galerie (`maugallery.js`) pour afficher les images HD dans la lightbox au lieu des miniatures.

## 📂 Structure du Projet

- `assets/` : Contient les images optimisées (WebP), le CSS et le JS.
- `SEO/` : Contient le rapport d'intervention détaillé et les preuves d'audit.
- `index.html` : Le code source optimisé.

## 📄 Rapport Détaillé

Pour voir le détail des interventions et les preuves "Avant/Après", consultez le rapport complet :
👉 [Voir le Rapport d'Optimisation](./SEO/Rapport_Final_Optimisation.pdf)

---

Projet réalisé par Marcio Lacourcelle - 09-12-2025
