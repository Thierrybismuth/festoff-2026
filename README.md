# Festival OFF Avignon 2026 — Mockups Écocup

Catalogue de **1863 visuels d'écocup personnalisés** pour les **163 théâtres** du Festival OFF Avignon 2026.

## 🌐 En ligne

- **Index général** : https://thierrybismuth.github.io/festoff-2026/
- **Par théâtre** : https://thierrybismuth.github.io/festoff-2026/theatre/{slug}.html
- **Mockup direct** : https://thierrybismuth.github.io/festoff-2026/mockups/{slug}/{id}.jpg

## 📂 Structure

```
.
├── index.html                  # Catalogue général de tous les théâtres
├── theatre/<slug>.html         # Page de catalogue par théâtre
├── mockups/<slug>/<id>.jpg     # Mockup individuel (1200×1400)
└── database.json               # Base complète enrichie
```

## 📊 database.json — Schéma

Chaque entrée :
```json
{
  "id": "9216",
  "titre": "Molière et ses masques",
  "theatre": "TRAIN BLEU (THÉÂTRE DU)",
  "theatre_slug": "train-bleu-theatre-du",
  "affiche_url": "https://cdn.festivaloffavignon.com/spectacles/...webp",
  "spectacle_url": "https://www.festivaloffavignon.com/spectacles/9216-...",
  "mockup_url": "https://thierrybismuth.github.io/festoff-2026/mockups/train-bleu-theatre-du/9216.jpg"
}
```

## 🛠 Pipeline de génération

1. **Scraping** : pagination de festivaloffavignon.com/programme
2. **Mockup** : skill `skill-mockup-ecocup` (wrap intégral, ombrage cylindrique)
3. **Push** : ce repo, GitHub Pages

Contact : thierry@thierrybismuth.com
