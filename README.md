# Odilon Hugonnot

Développeur full-stack senior basé à Besançon. Je travaille principalement sur des architectures backend Go et PHP/Symfony, avec Vue.js côté front. J'aime les projets où la contrainte technique est réelle — streaming vidéo, encodage temps réel, systèmes distribués. Ancien formateur développeur web, j'ai conçu et dispensé des formations sur la POO, le développement web et les bonnes pratiques.

## Stack

**Backend** — Go · PHP 8 · Symfony · FFmpeg
**Frontend** — Vue.js 3 · JavaScript · HTML/CSS
**Infra** — Docker · Linux · Apache/Nginx · PostgreSQL · SQLite
**Streaming** — HLS · VAAPI · NVENC · WebVTT · ffprobe

## Projet phare

### [ShareBox](https://github.com/ohugonnot/sharebox) — Alternative légère à Plex/Jellyfin

Media server self-hosted en PHP pur. Zéro dépendance, tourne sur un Raspberry Pi.

- Streaming adaptatif (HLS, transcode à la volée, GPU auto-détecté)
- Interface Netflix-style avec posters TMDB
- Partage de liens avec mot de passe et expiration
- 441 tests (dont cas de sécurité), tests e2e Playwright et CI GitHub Actions
- [Démo en ligne](https://demo.anime-sanctuary.net/dl/browse?p=Films&view=grid) · MIT

## Autres projets

| Projet | Description |
|--------|-------------|
| [go-api-observability](https://github.com/ohugonnot/go-api-observability) | Observabilité d'une API Go : slog avec trace_id, métriques RED Prometheus, traces OpenTelemetry, laboratoire Docker testé |
| [mtls-refuse](https://github.com/ohugonnot/mtls-refuse) | Serveur mTLS en Go, mini-CA et matrice de tests : chaque mauvais client est refusé, pour la bonne raison |
| [gcm-nonce-budget](https://github.com/ohugonnot/gcm-nonce-budget) | AES-GCM à nonces aléatoires : refuse de chiffrer au-delà de 2^32 messages par clé (Go, tests de mutation) |
| [golazo](https://github.com/ohugonnot/golazo) | Moteur de prédiction de scores de football : Dixon-Coles, Monte-Carlo, stdlib seule |
| [mes-mots](https://github.com/ohugonnot/mes-mots) | Application de communication par pictogrammes, hors ligne et sans compte, pour un enfant non lecteur |
| [claude-skills](https://github.com/ohugonnot/claude-skills) | Skills Claude Code : livraison par étapes, revue de code senior, rédaction technique |
| [citecheck](https://github.com/ohugonnot/citecheck) | Vérifie mécaniquement les citations et chiffres d'un résumé de livre contre son texte (Python) |
| [claudegate](https://github.com/ohugonnot/claudegate) | HTTP gateway qui expose Claude Code CLI comme API REST |
| [citoyen.anime-sanctuary.net](https://github.com/ohugonnot/citoyen.anime-sanctuary.net) | Portail civic-tech d'évaluation des services publics locaux |
| [claude-code-statusline](https://github.com/ohugonnot/claude-code-statusline) | Suivi temps réel des quotas Claude Code dans le terminal |
| [coder-proprement](https://github.com/ohugonnot/coder-proprement) | Synthèse personnelle de Clean Code — SOLID, nommage, tests, architecture |

## Cours, outils & blog

- Le portail : [web-developpeur.com](https://www.web-developpeur.com/)
- Cours interactifs gratuits (21 cours, 185 leçons, dont [coder avec l'IA](https://www.web-developpeur.com/apprendre/coder-avec-ia/)) : [web-developpeur.com/apprendre](https://www.web-developpeur.com/apprendre/)
- Outils web gratuits (TJM, contraste WCAG, cURL...) : [web-developpeur.com/outils](https://www.web-developpeur.com/outils/)
- Blog technique (Go, PHP, IA, DevOps) : [web-developpeur.com/blog](https://www.web-developpeur.com/blog/)
- Bibliothèque de fiches de lecture dev : [web-developpeur.com/bibliotheque](https://www.web-developpeur.com/bibliotheque/)
- CV : [web-developpeur.com/cv](https://www.web-developpeur.com/cv/)
