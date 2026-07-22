# Portfolio — Akrem Rhaimi

Site statique (HTML/CSS/JS, aucune dépendance) prêt à déployer gratuitement sur GitHub Pages.

## Structure

```
portfolio/
├── index.html
├── styles.css
├── images/
│   └── akrem1.png     ← remplace par ta propre photo si tu veux (même nom de fichier)
└── cv/
    └── Akrem_Rhaimi_CV.pdf   ← remplace par la dernière version de ton CV si besoin
```

## Déployer gratuitement sur GitHub Pages

1. Crée un nouveau dépôt sur GitHub, par exemple `akrem-portfolio` (public).
2. Sur ton ordinateur, dans ce dossier `portfolio/` :
   ```bash
   git init
   git add .
   git commit -m "Portfolio initial"
   git branch -M main
   git remote add origin https://github.com/Akremrhaimi99/akrem-portfolio.git
   git push -u origin main
   ```
3. Sur GitHub : va dans **Settings → Pages** de ton dépôt.
4. Sous **Build and deployment**, choisis **Source: Deploy from a branch**, puis **Branch: main / (root)**, et clique **Save**.
5. Après 1–2 minutes, ton site sera en ligne à l'adresse :
   `https://akremrhaimi99.github.io/akrem-portfolio/`

Aucune étape de build n'est nécessaire — le site est en HTML/CSS pur.

## Nom de domaine personnalisé (optionnel, gratuit)

Si tu as un domaine (ex. `akremrhaimi.dev`), ajoute un fichier `CNAME` à la racine contenant ton domaine,
puis configure un enregistrement DNS de type `CNAME` pointant vers `akremrhaimi99.github.io`.

## Personnalisation rapide

- **Photo** : remplace `images/akrem1.png` par ton image (garde le même nom, ou change le chemin dans `index.html`).
- **CV téléchargeable** : remplace `cv/Akrem_Rhaimi_CV.pdf` par ta dernière version.
- **Couleurs** : les variables sont en haut de `styles.css` (`--ink`, `--accent`, `--accent-2`, etc.).
- **Contenu** : tout le texte (expérience, projets, compétences) est directement dans `index.html`.
