# Rapport d'Optimisation SEO - Nina Carducci

Ce rapport détaille l'ensemble des actions correctives menées sur le site de Nina Carducci pour améliorer ses performances, son référencement naturel (SEO) et son accessibilité.

---

## 🚀 1. Optimisation des Performances

L'objectif était de réduire drastiquement le temps de chargement (LCP) pour améliorer l'expérience utilisateur et le score Core Web Vitals.

### Actions réalisées :

- **Compression et Conversion des Images :**
  - Toutes les images de la galerie et du slider ont été converties au format **WebP** (plus léger que le JPG/PNG).
  - Redimensionnement des images aux tailles d'affichage réelles pour éviter de charger des fichiers inutilement lourds.
- **Images Responsives (`srcset`) :**
  - Mise en place de l'attribut `srcset` pour servir l'image la plus adaptée à la taille de l'écran de l'utilisateur (Mobile, Tablette, Desktop).
- **Lazy Loading :**
  - Ajout de l'attribut `loading="lazy"` sur les images en dessous de la ligne de flottaison pour différer leur chargement.
- **Scripts Non-Bloquants :**
  - Ajout de l'attribut `defer` sur les scripts JavaScript (`bootstrap`, `jquery`, `maugallery`) pour ne pas bloquer le rendu initial de la page.

---

## 🏗️ 2. Sémantique et Structure HTML

Le code HTML a été restructuré pour respecter les standards du W3C et aider les robots d'indexation à mieux comprendre le contenu.

### Actions réalisées :

- **Structure Sémantique :**
  - Remplacement des `<div>` génériques par des balises sémantiques : `<header>`, `<main>`, `<section>`, `<footer>`.
  - Création de la section `#contact` à l'intérieur de la balise `<main>` pour le SEO local.
- **Hiérarchie des Titres :**
  - Correction de la hiérarchie des titres (`h1`, `h2`, `h3`) pour une structure logique.
  - Un seul `<h1>` unique par page définissant le sujet principal.

---

## 📍 3. SEO Local et Contenu

Pour améliorer la visibilité sur les recherches locales ("Photographe Bordeaux").

### Actions réalisées :

- **Balisage Local (`<address>`) :**
  - Intégration des coordonnées (adresse, téléphone) dans une balise `<address>`.
  - Ajout de liens cliquables pour le téléphone (`href="tel:..."`).
- **Meta Tags :**
  - Rédaction d'une **Meta Description** unique et pertinente incluant les mots-clés locaux.
  - Optimisation du **Title** de la page.

---

## ♿ 4. Accessibilité

Pour rendre le site utilisable par tous, y compris les personnes utilisant des lecteurs d'écran.

### Actions réalisées :

- **Attributs Alt :**
  - Ajout de descriptions textuelles pertinentes (attribut `alt`) sur toutes les images de la galerie et du slider.
- **Contraste et Lisibilité :**
  - Vérification de la lisibilité des textes.

---

## ✅ Conclusion

Le site est désormais techniquement optimisé pour les moteurs de recherche.

- **Performance :** Chargement rapide grâce au format WebP et au Lazy Loading.
- **SEO :** Structure sémantique claire et balisage local en place.
- **Accessibilité :** Images décrites et navigation logique.

Ces interventions garantissent une meilleure indexation par Google et une expérience utilisateur fluide.
