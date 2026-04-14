# LVL IA — Site Vitrine

Site vitrine de **LVL IA**, agence d'automatisation et d'intelligence artificielle basée à Caen, Normandie.

## Stack

- HTML5 / CSS3 / Vanilla JS — aucune dépendance à installer
- Fonts : Instrument Serif (display) + DM Sans (body) via Google Fonts
- Icons : Lucide via CDN
- Déploiement : Netlify

## Structure

```
lvl-ia-website/
├── index.html        ← Page unique (all-in-one)
├── netlify.toml      ← Config Netlify (headers, cache)
└── README.md
```

## Sections

1. **Hero** — Accroche + stats clés
2. **Services** — 4 cartes services avec visuels
3. **Méthode** — 4 étapes en langage client
4. **Pourquoi nous** — 6 arguments différenciants
5. **Témoignages** — 3 avis clients
6. **FAQ** — 6 questions/réponses (accordéon)
7. **Contact** — Formulaire de prise de RDV diagnostic

## Déploiement sur Netlify

1. Aller sur [netlify.com](https://netlify.com)
2. "Add new site" → "Import an existing project"
3. Connecter GitHub → sélectionner `lvl-ia-website`
4. Build command : *(laisser vide)*
5. Publish directory : `.`
6. Deploy ✅

## Personnalisation rapide

- **Email** : rechercher `vidaluca77@gmail.com` dans `index.html`
- **Tarifs** : rechercher `price-value` dans `index.html`
- **Témoignages** : bloc `.testimonial`
- **Couleur primaire** : variable `--color-primary` en haut du CSS
