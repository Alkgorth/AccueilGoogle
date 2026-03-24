# Reproduction de la page d'accueil Google (HTML/CSS)

Ce projet est un exercice de reproduction visuelle de la page d'accueil de Google (`google.fr`) en **HTML5** et **CSS3**, sans framework et sans JavaScript.

## Objectif

- Recréer une interface proche de Google avec une structure propre et semantique.
- Travailler la mise en page avec Flexbox.
- Organiser le code de maniere lisible et reutilisable.

## Fonctionnalites integrees

- Header colle en haut de la page.
- Navigation principale avec liens gauche/droite.
- Bouton "applications Google" (grille de points) avec panneau visible au survol.
- Bouton avatar circulaire avec pictogramme.
- Zone principale centree (logo + barre de recherche + boutons d'action).
- Barre de recherche avec:
  - icone loupe a gauche,
  - icone microphone a droite.
- Footer colle en bas avec:
  - une ligne dediee a "France",
  - une deuxieme ligne avec les autres liens/informations.
- Effets `hover` sur les liens et boutons.

## Structure du projet

```text
google-homepage/
├─ index.html
├─ README.md
└─ assets/
   ├─ css/
   │  └─ styles.css
   ├─ img/
   └─ js/
      └─ main.js
```

## Fichiers principaux

- `index.html` : structure de la page (header, main, footer, formulaire de recherche).
- `assets/css/styles.css` : styles globaux, mise en page, icones, boutons et footer.

## Lancer le projet

1. Ouvrir le dossier `google-homepage` dans ton editeur.
2. Ouvrir `index.html` dans le navigateur (double-clic ou extension Live Server).

## Notes

- Projet volontairement simple, sans framework.
- Le rendu est fait pour se rapprocher de Google, sans rechercher un clone pixel-perfect.
