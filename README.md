# Veille Nanogis (OPML)

Un petit dépôt pour la veille technologique (Angular, TypeScript, MapLibre, LoopBack, MongoDB, Chart.js…).

## 📦 Contenu
- `opml/feedly_veille_mathieu.opml` : fichier opml.
- `templates/PRIORITIES.md` : exemples de règles **Leo Priorities** & **Mute Filters**.
- `README.md` : ce guide.

## 🚀 Utilisation rapide
1. **Importer dans Feedly** : *Add Content → Import OPML* et choisis `opml/feedly_veille_mathieu_clean.opml` (ou la version brute).
2. **Organiser** : vérifie les dossiers/collections et ajuste si besoin.
3. **Prioriser** : applique les règles proposées dans `templates/PRIORITIES.md`.
4. **Partager** :
   - **OPML** : envoie ce fichier ou le lien du repo.
   - **GitHub/Gist** : vois ci-dessous.

## 🔄 Mettre à jour l’OPML
- Ajoute/supprime des sources dans Feedly → **ré-exporte** l’OPML → remplace `opml/feedly_veille_mathieu.opml` → régénère la version clean.
- Astuce : garde une branche `main` (stable) et une `work` pour tester de nouveaux flux.

## 🌐 Partager publiquement
### Option A — GitHub (recommandé pour l’équipe)
```bash
git init
git add .
git commit -m "Init veille Nanogis"
git branch -M main
git remote add origin https://github.com/<org_ou_ton_compte>/veille-nanogis.git
git push -u origin main
```
- Donne le lien du repo à l’équipe.
- Quand tu mets à jour l’OPML, commit & push → tout le monde récupère.

### Option B — Gist (simple & léger)
1. Va sur https://gist.github.com, clique **New gist**.
2. Ajoute `feedly_veille_mathieu.opml` (nom de fichier) + colle le contenu.
3. Choisis **Secret** (non référencé) ou **Public**.
4. **Create secret gist** → partage l’URL.

## 🧰 Outils compatibles (lecture)
Feedly, Inoreader, NetNewsWire/Reeder, Fluent Reader, FreshRSS/TT-RSS/Miniflux, Thunderbird.


