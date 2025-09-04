# Veille Nanogis (OPML)

*Dépôt de veille technologique (Angular, TypeScript, MapLibre, LoopBack, MongoDB, Chart.js…).*


---

## 🚀 Démarrage rapide

1. **Télécharge** le fichier OPML : `opml/veille_mathieu.opml`.

2. **Importe** le dans ton lecteur RSS :

   - **Feedly** : *Add Content → Import OPML* → choisis le fichier.

   - **Inoreader** : *Preferences → Import/Export → Import OPML*.

   - **NetNewsWire/Reeder** : *File → Import Subscriptions…* et choisis l’OPML.

   - **Fluent Reader** : *File → Import Feeds*.

   - **FreshRSS / Tiny Tiny RSS / Miniflux** : page d’administration → *Import OPML*.

   - **Thunderbird** : crée un compte **Blogs & News Feeds** → *Manage Subscriptions…* → **Import** (OPML).


> 💡 **Depuis GitHub** : ouvre `opml/veille_mathieu.opml`, clique **Raw**, puis **Download**. Ensuite importe le fichier.


## 📦 Contenu du dépôt

- `opml/veille_mathieu.opml` — liste des flux (export OPML).

- `templates/PRIORITIES.md` — exemples de règles **Feedly Leo** (Priorities & Mute Filters).

- `README.md` — ce guide.


## 🗂️ Sources incluses


### Angular & TypeScript

- [Angular Blog](https://blog.angular.dev?source=rss----447683c3d9a3---4) — `https://blog.angular.io/feed/`
- [Angular Material Releases](https://github.com/angular/components/releases) — `https://github.com/angular/components/releases.atom`
- [DEV Community: This is Angular](https://dev.to/this-is-angular) — `https://dev.to/feed/this-is-angular`
- [RxJS Releases](https://github.com/ReactiveX/rxjs/releases) — `https://github.com/ReactiveX/rxjs/releases.atom`
- [TypeScript](https://devblogs.microsoft.com/typescript/) — `http://blogs.msdn.com/b/typescript/rss.aspx`

### Backend & Data

- [LoopBack 4 (loopback-next) Releases](https://github.com/loopbackio/loopback-next/releases) — `https://github.com/loopbackio/loopback-next/releases.atom`
- [MongoDB Blog](https://www.mongodb.com/blog) — `https://www.mongodb.com/blog/rss`
- [Studio 3T Blog](https://studio3t.com/) — `https://studio3t.com/feed/`

### ChartJS

- [Chart.js Releases](https://github.com/chartjs/Chart.js/releases) — `https://github.com/chartjs/Chart.js/releases.atom`

### MapLibre

- [MapLibre GL JS Releases](https://github.com/maplibre/maplibre-gl-js/releases) — `https://github.com/maplibre/maplibre-gl-js/releases.atom`
- [MapLibre News](https://maplibre.org/) — `https://maplibre.org/news/index.xml`

### Platform & Tooling

- [Chrome Developers Blog](https://developer.chrome.com/blog/) — `https://developer.chrome.com/static/blog/feed.xml`
- [GitHub Blog](https://github.blog/) — `https://github.blog/feed/`
- [Node.js Blog](https://nodejs.org/en) — `https://nodejs.org/en/feed/blog.xml`
- [Visual Studio Code - Code Editing. Redefined.](https://code.visualstudio.com/) — `https://code.visualstudio.com/feed.xml`

---

## 🔄 Mettre à jour l’OPML

- Ajoute/supprime des sources dans ton lecteur → **ré-exporte** un nouvel OPML.

- Remplace `opml/veille_mathieu.opml` dans le dépôt.

- (Optionnel) Crée une **Release** GitHub (tag `vX.Y.Z`) et attache l’OPML.


## 🛠️ Dépannage

- **“Empty OPML file”** : vérifie que le fichier n’est pas vide et que les caractères spéciaux (`&`) sont bien échappés dans le XML.

- **Doublons** : certains lecteurs affichent des flux en double si le même `xmlUrl` est dans plusieurs dossiers.

- **Import partiel** : certains services ignorent les dossiers vides.


---

*Dernière mise à jour : 2025-09-04 16:40 UTC*
