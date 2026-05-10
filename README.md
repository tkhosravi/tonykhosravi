# Blog d'un Persan chinois 🇮🇷🇨🇳🏃‍♂️🌍💻

[![GitHub Pages](https://img.shields.io/badge/GitHub-Pages-blue?logo=github)](https://tonykhosravi.github.io/tony-blog/)
[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC_BY--SA_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)

Un un simpe espace de partage de mes expériences et passions :
- **Course à pied** (trails, marathons)
<!--- - **Voyages** (commuting, aventures)
**Musique** (commuting, aventures)
- **Tech** (projets open source, développement web)-->

🔗 **[Lire le blog](https://tkhosravi.github.io/tonykhosravi/)**

---

## 📂 Structure du repo
```
tony-blog/
├── _posts/          # Articles en Markdown (ex: 2026-04-12-mon-ulatrail.md)
├── _config.yml      # Configuration Jekyll
├── assets/          # Images, CSS, JS
│   └── images/
├── _includes/       # Composants réutilisables (header, footer)
├── _layouts/        # Mises en page (default.html)
├── _pages/          # Pages statiques (ex: À propos)
└── index.md         # Page d'accueil
```
---

## 🚀 Comment contribuer ?

### Ajouter un article
1. Crée un fichier Markdown dans `_posts/` avec le format :
   ```bash
   YYYY-MM-DD-titre-de-l-article.md
Utilise ce template pour le front matter (en-tête) :


---
title: "Titre de l'article"
date: YYYY-MM-DD
categories: [cat1, cat2]  # Ex: [course, tech]
strava: "lien_activite_strava"  # Optionnel
spotify: "lien_playlist"        # Optionnel
---
# {{ page.title }}

Ton contenu ici (en Markdown).


Ajoute des liens Strava/Spotify si pertinent.

Prévisualiser localement

Installe Jekyll (si ce n'est pas déjà fait) :
bash
Copier

gem install bundler jekyll
bundle install




Lance le serveur local :
bash
Copier

bundle exec jekyll serve




Ouvre http://localhost:4000/tony-blog dans ton navigateur.
Déployer

Toute modification poussée sur la branche main est automatiquement déployée sur GitHub Pages.

🔧 Configuration
Thème
Ce blog utilise Minimal Mistakes.
Pour le personnaliser, modifie _config.yml :
yaml
Copier

title: "Tony’s Blog"
description: "Course à pied, voyages et tech"
theme: minimal-mistakes-jekyll
remote_theme: mmistakes/minimal-mistakes
minimal_mistakes_skin: "default"  # dark, air, aqua, etc.



Plugins
Les plugins Jekyll utiles sont déjà configurés dans _config.yml :
yaml
Copier

plugins:
  - jekyll-feed
  - jekyll-seo-tag
  - jekyll-sitemap




📖 Exemples d’articles
1. Récit de course
_posts/2026-04-12-mon-ulatrail-oléron.md
markdown
Copier

---
title: "Mon ultra-trail à Oléron : 50 km de vent et de sable"
date: 2026-04-12
categories: [course, voyage]
strava: "https://www.strava.com/activities/XXXX"
---

# {{ page.title }}

Ce week-end, j’ai couru **50 km** sous la pluie et le vent sur l’île d’Oléron.
**[Voir mon activité sur Strava]({{ page.strava }})**.

## Pourquoi ce trail ?
- Paysages à couper le souffle
- Défi personnel pour mon semi-marathon
- Rencontres avec des coureurs locaux

## Matériel utilisé
- **Montre** : Garmin Forerunner 955
- **Chaussures** : Hoka Speedgoat 5
- **Playlist** : [Mon mix running sur Spotify](https://open.spotify.com/playlist/XXXX)



2. Article technique
_posts/2026-05-01-integrer-strava-avec-jekyll.md
markdown
Copier

---
title: "Intégrer Strava à un blog Jekyll"
date: 2026-05-01
categories: [tech]
---

# {{ page.title }}

Comment afficher tes activités Strava sur un blog Jekyll ?

## Méthode 1 : Lien direct
```markdown
[Voir mon activité](https://www.strava.com/activities/XXXX)



Méthode 2 : Embed (avec JavaScript)
Ajoute ce code dans ton fichier Markdown ou HTML :
html
Copier

<div class="strava-embed" data-embed-type="activity" data-embed-id="XXXX"></div>
<script src="https://strava-embeds.com/embed.js"></script>



text
Copier

---

## 🌐 Lien vers le blog
👉 [Lire mes articles](https://tonykhosravi.github.io/tony-blog/)

---

## 📜 Licence
Ce contenu est sous licence **[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)**.
Tu peux partager et adapter le contenu, à condition de me créditer et de partager sous la même licence.

---

## 🤝 Contact
- **Mastodon** : [@tony@framapiaf.org](https://framapiaf.org/@tony)
- **Plume** : [plume.libreho.st/tony](https://plume.libreho.st/tony)
- **GitHub** : [@tonykhosravi](https://github.com/tonykhosravi)



