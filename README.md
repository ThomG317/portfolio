# Portfolio — Thomas Gaubert

## Structure
```
portfolio/
├── index.html          ← Page d'accueil (hero + case studies + à propos + contact)
├── arcs.html           ← Case study ARCS
├── zenipark.html       ← Case study Zenipark
├── maintenance.html    ← Page "en construction"
├── css/
│   └── style.css       ← Styles (palette, layout, responsive)
├── js/
│   └── main.js         ← Navigation mobile, scroll reveal, interactions
└── images/
    ├── photo-thomas.jpg          ← Ta photo (utilisée dans hero, à propos, contact)
    ├── arcs/
    │   ├── logo-arcs.png         ← Logo ARCS (carré, ~48px affiché)
    │   ├── card-preview.png      ← Screenshot pour la carte résumé (tableau de bord)
    │   ├── lot-abonnements.png   ← Screenshot lot Abonnements (step 3)
    │   ├── lot-activites.png     ← Screenshot lot Activités (step 3)
    │   ├── lot-partenaires.png   ← Screenshot lot Partenaires (step 3)
    │   └── tableau-de-bord.png   ← Screenshot tableau de bord complet (step 4)
    └── zenipark/
        ├── logo-zenipark.png     ← Logo Zenipark (carré, ~48px affiché)
        ├── card-preview.png      ← Screenshot pour la carte résumé
        ├── avant-1.png           ← App mobile "avant" — écran 1 (step 1)
        ├── avant-2.png           ← App mobile "avant" — écran 2 (step 1)
        ├── audit-grille.png      ← Grille d'évaluation (step 2)
        ├── audit-parcours.png    ← Parcours connexion détaillé (step 2)
        ├── resultat-reservation.png  ← Maquette finale — réservation (step 4)
        ├── resultat-detail.png       ← Maquette finale — détail place (step 4)
        └── resultat-covoiturage.png  ← Maquette finale — covoiturage (step 4)
```

## Images à fournir

Exporte depuis Figma en **PNG @2x** pour la netteté sur écrans Retina.

| Fichier | Source | Taille recommandée |
|---------|--------|--------------------|
| `photo-thomas.jpg` | Ta photo de profil | 200x200px min |
| `arcs/logo-arcs.png` | Logo de l'asso ARCS | 96x96px |
| `arcs/card-preview.png` | Tableau de bord ARCS (crop) | ~600px large |
| `arcs/lot-*.png` | Screenshots des 3 lots | ~600px large chacun |
| `arcs/tableau-de-bord.png` | Screenshot complet du dashboard | ~1200px large |
| `zenipark/logo-zenipark.png` | Logo Zenipark (la voiture) | 96x96px |
| `zenipark/card-preview.png` | Écran principal Zenipark | ~600px large |
| `zenipark/avant-*.png` | Screens app mobile avant refonte | ~240px large (format mobile) |
| `zenipark/audit-*.png` | Screenshots de l'audit Excel | ~600px large |
| `zenipark/resultat-*.png` | Maquettes finales (3 écrans) | ~240px large (format mobile) |

## Déploiement sur GitHub Pages

1. Crée un repo GitHub (ex: `thomas-gaubert.github.io`)
2. Push tout le dossier `portfolio/` à la racine du repo
3. Va dans Settings → Pages → Source: `main` branch, `/ (root)`
4. Ton site sera live à `https://thomas-gaubert.github.io`

### Avec un domaine custom
1. Achète un domaine (Namecheap, OVH, etc.)
2. Dans ton repo, crée un fichier `CNAME` avec ton domaine dedans
3. Configure les DNS chez ton registrar (CNAME vers `thomas-gaubert.github.io`)

## Déploiement sur Netlify (alternative)

1. Crée un compte sur netlify.com
2. Drag & drop le dossier `portfolio/` sur le dashboard Netlify
3. C'est en ligne

## Personnalisation

- **Palette** : toutes les couleurs sont en CSS variables dans `css/style.css`
- **Typos** : Playfair Display (serif) + DM Sans (sans-serif), chargées via Google Fonts
- **Contenu** : tout le texte est directement dans les fichiers HTML
- **CV** : place ton PDF `CV_Thomas_Gaubert.pdf` à la racine du dossier
