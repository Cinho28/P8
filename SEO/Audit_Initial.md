# Audit SEO Initial - Nina Carducci

Cet audit recense les problèmes techniques, sémantiques et de performance identifiés sur le site avant intervention. Il est trié par ordre de priorité (impact sur le référencement et l'expérience utilisateur).

---

## 🚨 1. Performance : Images non optimisées

**Description :** Plusieurs images de la galerie sont trop lourdes (format inadapté, dimensions excessives), ce qui ralentit considérablement le chargement.

- **Temps de chargement (LCP) :** 9.4 secondes (Critique).
- **Objectif recommandé :** < 2.5 secondes.

**Recommandations :**

- Convertir les images en format nouvelle génération (**WebP**).
- Redimensionner les images aux dimensions d'affichage réelles.
- Mettre en place des images responsives (`srcset`).

> **Impact SEO :** Majeur (Core Web Vitals). Un site lent est pénalisé par Google et fait fuir les visiteurs.

---

## 🏷️ 2. SEO Technique : Balises Meta manquantes

**Description :** Certaines pages clés manquent de balises `<title>` et `<meta description>`, ou celles-ci sont génériques.

**Recommandations :**

- Rédiger des titres uniques et accrocheurs pour chaque page.
- Ajouter une meta description pertinente incluant les mots-clés locaux ("Photographe Bordeaux").

> **Impact SEO :** Majeur. Ces balises sont essentielles pour le classement et le taux de clic (CTR) dans les résultats de recherche.

---

## 🏗️ 3. Sémantique : Structure HTML incorrecte

**Description :** La hiérarchie des titres est non respectée.

- Exemple : Utilisation de balises `<h1>` pour des citations décoratives au lieu de titres principaux.

**Recommandations :**

- Utiliser un seul `<h1>` par page (le titre principal).
- Structurer le contenu logiquement avec `<h2>`, `<h3>`, etc.
- Utiliser des balises sémantiques (`<header>`, `<main>`, `<footer>`) au lieu de `<div>` génériques.

> **Impact SEO :** Moyen. Une bonne structure aide les robots de Google à comprendre le contenu de la page.

---

## ♿ 4. Accessibilité : Attributs Alt manquants

**Description :** La majorité des images de la galerie n'ont pas d'attribut `alt` ou celui-ci est vide.

**Recommandations :**

- Ajouter un texte alternatif descriptif à toutes les images significatives (ex: "Concert de rock en noir et blanc").

> **Impact SEO :** Moyen. Améliore l'accessibilité (lecteurs d'écran) et le référencement sur Google Images.

---

## ⚡ 5. Performance : Scripts bloquants

**Description :** Les scripts JavaScript (`jquery`, `bootstrap`, `maugallery`) sont chargés de manière synchrone dans le `<head>`, bloquant l'affichage du reste de la page.

**Recommandations :**

- Ajouter l'attribut `defer` ou `async` aux scripts pour qu'ils se chargent en parallèle sans bloquer le rendu visuel.

> **Impact SEO :** Moyen. Améliore le "First Contentful Paint" (FCP).

---

## 📍 6. Contenu : Mots-clés et SEO Local

**Description :** Le contenu textuel est pauvre en mots-clés stratégiques. Le ciblage géographique (Bordeaux) est insuffisant.

**Recommandations :**

- Enrichir les textes avec un champ lexical pertinent (photographe, shooting, mariage, portrait, Bordeaux, Gironde).
- Intégrer ces mots-clés naturellement dans les titres et les paragraphes.

> **Impact SEO :** Moyen. Permet de se positionner sur les requêtes locales des clients potentiels.
