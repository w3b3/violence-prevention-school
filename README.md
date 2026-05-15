# La santé sexuelle positive — tableau interactif

Page web mobile-friendly et inclusive pour ados — affiche les ressources de prévention et de soutien en santé sexuelle au Nouveau-Brunswick sous forme de tableau interactif (bento board), avec lignes d'écoute, services et liens éducatifs.

Adapté du dépliant *La santé sexuelle positive pour les parents* — Comité pour une éducation à la sexualité positive et inclusive, District scolaire francophone Sud, 2026.

## Aperçu

### Logo

![Logo](screenshots/logo.png)

### Desktop

![Desktop](screenshots/desktop.png)

### Mobile

![Mobile](screenshots/mobile.png)

## Caractéristiques

- **Bannière d'urgence** persistante (sticky) — un clic pour appeler le ministère du Développement social
- **Filtres** par catégorie : urgence, lignes d'écoute, services, info, 2ELGBTQIA+
- **Cartes dépliables** — chaque carte révèle les numéros et liens utiles
- **Liens `tel:` partout** — composer un numéro depuis mobile en un tap
- **Mobile-first** — grille bento qui se replie en colonne unique sous 760px
- **Palette pastel** reprise du dépliant original : rose, lilas, pêche, menthe, crème
- **Typographie distinctive** : *Caprasimo* (display) + *Nunito* (corps)
- **Respecte `prefers-reduced-motion`**

## Fichiers

| Fichier | Description |
| --- | --- |
| `index.html` | Page unique, autoportante (aucun build) |
| `logo.svg` | Logo complet avec wordmark |
| `favicon.svg` | Favicon vectoriel |
| `favicon-32.png` | Fallback 32×32 |
| `apple-touch-icon.png` | Icône iOS 180×180 |
| `screenshots/` | Captures d'écran |

## Utilisation

Ouvrir `index.html` dans un navigateur — c'est tout. Aucune dépendance, aucun serveur requis.

```bash
open index.html
```

Pour héberger : déposer le dossier complet sur n'importe quel hébergeur statique (GitHub Pages, Cloudflare Pages, Netlify).
