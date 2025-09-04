# PRIORITIES & MUTE FILTERS (Feedly Leo)

Modele prêt à copier pour configurer, dans Feedly, ce qui doit remonter en priorité (Leo Priorities) et ce qui doit être masqué (Mute filters).
En bref : ça transforme ton flux RSS en signal utile (moins de bruit “jobs / meetups / weekly recap”, plus d’articles “breaking changes Angular”, “perfs MapLibre”, etc.).


---

## 🎯 Priorities par dossier

### Angular & TypeScript

**Sources dans ce dossier :**
  - Angular Blog
  - Angular Material Releases
  - DEV Community: This is Angular
  - RxJS Releases
  - TypeScript

**Priorities (proposées)**  
Mots-clés : `Angular 18, Angular 19, signals, standalone, zoned/zoneless, breaking change, deprecation, a11y, material, SSR, hydration`

**Scope conseillé :** appliquer ces Priorities **au dossier** “Angular & TypeScript” plutôt qu’à tous les flux.

### Backend & Data

**Sources dans ce dossier :**
  - LoopBack 4 (loopback-next) Releases
  - MongoDB Blog
  - Studio 3T Blog

**Priorities (proposées)**  
Mots-clés : `Aggregation, index, query performance, explain, TTL, compound index, schema, migration, LoopBack 4, REST, OpenAPI`

**Scope conseillé :** appliquer ces Priorities **au dossier** “Backend & Data” plutôt qu’à tous les flux.

### ChartJS

**Sources dans ce dossier :**
  - Chart.js Releases

**Priorities (proposées)**  
Mots-clés : `Chart.js, adapter-date-fns, timeseries, zoom plugin, breaking, bugfix, performance`

**Scope conseillé :** appliquer ces Priorities **au dossier** “ChartJS” plutôt qu’à tous les flux.

### MapLibre

**Sources dans ce dossier :**
  - MapLibre GL JS Releases
  - MapLibre News

**Priorities (proposées)**  
Mots-clés : `MapLibre GL JS, vector tiles, performance, fps, WebGL, WebGPU, rendering, symbol, raster, terrain`

**Scope conseillé :** appliquer ces Priorities **au dossier** “MapLibre” plutôt qu’à tous les flux.

### Platform & Tooling

**Sources dans ce dossier :**
  - Chrome Developers Blog
  - GitHub Blog
  - Node.js Blog
  - Visual Studio Code - Code Editing. Redefined.

**Priorities (proposées)**  
Mots-clés : `Node.js, LTS, V8, TurboFan, Ignition, Garbage Collector, WebAssembly, Chrome, DevTools, Performance`

**Scope conseillé :** appliquer ces Priorities **au dossier** “Platform & Tooling” plutôt qu’à tous les flux.


---

## 🔕 Mute Filters (réduction de bruit)

Ajoute ces filtres (FR + EN) au niveau global ou par dossier :
- `job`, `hiring`, `recruiting`, `offre`, `poste`, `recrute`
- `meetup`, `event`, `webinar`, `conference`, `talk`, `call for papers`, `CFP`
- `weekly`, `roundup`, `recap`, `newsletter`, `digest`
- `podcast`, `video`

## 🔎 Saved Searches (à épingler)

- `"breaking change" OR deprecation` (Across all feeds)
- `"performance" OR perf OR benchmark` (dossier **Platform/Node/V8**)
- `"MapLibre GL JS" performance OR "vector tiles"` (dossier **Mapping/Geo**)
- `"Angular" signals OR standalone OR hydration` (dossier **Angular & TypeScript**)
- `"MongoDB" Aggregation OR index OR explain` (dossier **Backend & Data**) 

## 🧭 Comment appliquer dans Feedly

1. Ouvre Feedly (web) → **Create a Leo Priority**.
2. Colle quelques **mots-clés** de la section du dossier qui t'intéresse.
3. Choisis le **Scope** : *In a specific Feed/Folder* → sélectionne le **dossier**.
4. Sauvegarde. Répète pour les autres dossiers.
5. Pour le bruit : **Create a Mute Filter** → colle la liste ci-dessus.
