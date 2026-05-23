# Festival OFF Avignon 2026 — Mockups Écocup

Catalogue de visuels écocup personnalisés pour les théâtres du Festival OFF Avignon 2026.

## En ligne
- [Théâtre du Train Bleu](57 mockups) → https://thierrybismuth.github.io/festoff-2026/train-bleu.html

## Structure
- `mockups/<slug-theatre>/<id-spectacle>.jpg` — visuels écocup
- `database.json` — base complète (1863 spectacles, 163 théâtres)
- `<slug-theatre>.html` — page de catalogue par théâtre

## Pipeline
1. Scraping festivaloffavignon.com (pagination /programme)
2. Génération mockup wrap intégral (skill-mockup-ecocup)
3. Push GitHub Pages

Contact : thierry@thierrybismuth.com
