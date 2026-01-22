
## Exercice 1
✔ = support natif
⚠ = support partiel / via configuration
✖ = non supporté 


| Technologie           | CSR | SSR | SSG | ISR | Streaming | Server Components | Islands / Partial | Resumability |
| --------------------- | :-: | :-: | :-: | :-: | :-------: | :---------------: | :---------------: | :----------: |
| **Next.js**           |  ✔  |  ✔  |  ✔  |  ✔  |     ✔     |         ✔         |         ⚠         |       ✖      |
| **Nuxt.js**           |  ✔  |  ✔  |  ✔  |  ✔  |     ⚠     |         ✖         |         ⚠         |       ✖      |
| **NestJS**            |  ✖  |  ✖  |  ✖  |  ✖  |     ✖     |         ✖         |         ✖         |       ✖      |
| **SvelteKit**         |  ✔  |  ✔  |  ✔  |  ✖  |     ✔     |         ✖         |         ⚠         |       ✖      |
| **Remix**             |  ✔  |  ✔  |  ✖  |  ✖  |     ✔     |         ✖         |         ⚠         |       ✖      |
| **Gatsby**            |  ✔  |  ✖  |  ✔  |  ⚠  |     ✖     |         ✖         |         ✖         |       ✖      |
| **Astro**             |  ⚠  |  ⚠  |  ✔  |  ✖  |     ✖     |         ✖         |         ✔         |       ✖      |
| **Angular Universal** |  ✔  |  ✔  |  ✖  |  ✖  |     ✖     |         ✖         |         ✖         |       ✖      |
| **Vue.js (Vite)**     |  ✔  |  ✖  |  ✖  |  ✖  |     ✖     |         ✖         |         ✖         |       ✖      |
| **Qwik**              |  ✔  |  ✔  |  ✖  |  ✖  |     ✔     |         ✖         |         ✔         |       ✔      |


## Exercice 2 

⭐⭐⭐ = usage principal / natif
⭐⭐ = usage possible / courant
⭐ = usage limité / indirect
✅ = oui (vert)
❌ = non (rouge)

| Framework      | Frontend | Backend | Full-stack |
| -------------- | :------: | :-----: | :--------: |
| **Next.js**    |   ✅ ⭐⭐⭐  |   ✅ ⭐⭐  |    ✅ ⭐⭐⭐   |
| **Nuxt.js**    |   ✅ ⭐⭐⭐  |   ✅ ⭐⭐  |    ✅ ⭐⭐⭐   |
| **NestJS**     |     ❌    |  ✅ ⭐⭐⭐  |      ❌     |
| **React**      |   ✅ ⭐⭐⭐  |    ❌    |      ❌     |
| **Angular**    |   ✅ ⭐⭐⭐  |    ❌    |     ⚠ ⭐    |
| **Vue.js**     |   ✅ ⭐⭐⭐  |    ❌    |      ❌     |
| **Svelte**     |   ✅ ⭐⭐⭐  |    ❌    |      ❌     |
| **Express.js** |     ❌    |  ✅ ⭐⭐⭐  |      ❌     |
| **Remix**      |   ✅ ⭐⭐⭐  |   ✅ ⭐⭐  |    ✅ ⭐⭐⭐   |
| **Astro**      |   ✅ ⭐⭐   |    ❌    |     ⚠ ⭐    |


# Exercice 3 

⭐⭐⭐ = très adapté / choix recommandé
⭐⭐ = adapté / viable
⭐ = possible mais non optimal
✅ = oui (vert)
❌ = non (rouge)

| Framework      | Petit projet | Projet moyen | Grand projet |
| -------------- | :----------: | :----------: | :----------: |
| **Next.js**    |     ✅ ⭐⭐     |     ✅ ⭐⭐⭐    |     ✅ ⭐⭐⭐    |
| **Nuxt.js**    |     ✅ ⭐⭐     |     ✅ ⭐⭐⭐    |     ✅ ⭐⭐⭐    |
| **NestJS**     |      ⚠ ⭐     |     ✅ ⭐⭐     |     ✅ ⭐⭐⭐    |
| **React**      |     ✅ ⭐⭐     |     ✅ ⭐⭐⭐    |     ⚠ ⭐⭐     |
| **Angular**    |       ❌      |      ⚠ ⭐     |     ✅ ⭐⭐⭐    |
| **Vue.js**     |     ✅ ⭐⭐⭐    |     ✅ ⭐⭐     |      ⚠ ⭐     |
| **Svelte**     |     ✅ ⭐⭐⭐    |     ✅ ⭐⭐     |      ⚠ ⭐     |
| **Express.js** |     ✅ ⭐⭐⭐    |     ✅ ⭐⭐     |      ⚠ ⭐     |
| **Remix**      |     ✅ ⭐⭐     |     ✅ ⭐⭐⭐    |     ✅ ⭐⭐⭐    |
| **Astro**      |     ✅ ⭐⭐⭐    |     ✅ ⭐⭐     |       ❌      |


# Exercice 4 

| Critère                    | Next.js                                                                                          | Nuxt.js                                                                           |
| -------------------------- | ------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------- |
| **Écosystème**             | Basé sur l’écosystème React, très riche et largement adopté dans l’industrie, soutenu par Vercel | Basé sur l’écosystème Vue, plus simple et cohérent, soutenu par la communauté Vue |
| **Type de framework**      | Framework full-stack orienté React avec rendu hybride                                            | Framework full-stack orienté Vue avec rendu hybride                               |
| **Langage / UI**           | JavaScript / TypeScript avec React (JSX, Server Components)                                      | JavaScript / TypeScript avec Vue (Single File Components)                         |
| **SSR**                    | Support natif du rendu côté serveur, configurable par page ou composant                          | Support natif du rendu côté serveur, très bien intégré                            |
| **SSG**                    | Génération statique au build, pages totalement statiques possibles                               | Génération statique complète via Nuxt generate                                    |
| **ISR**                    | Régénération incrémentale des pages après le build, très mature                                  | Régénération incrémentale disponible dans Nuxt 3                                  |
| **Backend intégré**        | API Routes et Server Actions permettant de créer un backend léger                                | Nitro Server permettant routes API et logique serveur                             |
| **Routing**                | Basé sur le système de fichiers, App Router ou Pages Router                                      | Basé sur le système de fichiers, très intuitif                                    |
| **Courbe d’apprentissage** | Plus élevée, surtout avec App Router et Server Components                                        | Plus douce, particulièrement pour les développeurs Vue                            |
| **Déploiement**            | Optimisé pour Vercel, fonctionne aussi sur Node, Docker, Edge                                    | Compatible Node, Docker, serverless, plateformes cloud                            |
