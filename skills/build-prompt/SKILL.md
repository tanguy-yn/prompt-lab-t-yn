---
name: build-prompt
description: Construit un prompt GPT marketing digital from scratch en appliquant CO-STAR, RISEN ou XML tagging. Déclenche-toi quand l'utilisateur dit "/build-prompt", "crée-moi un prompt", "construis un prompt", "j'ai besoin d'un prompt pour", ou décrit un livrable marketing à produire (article SEO, post LinkedIn/Instagram/Facebook, prompt Midjourney/DALL-E, bannière, copywriting, newsletter).
---

# Build prompt

Génère un prompt GPT prêt à l'emploi pour un livrable marketing digital.

## Avant de générer

Pose au maximum 3 questions ciblées, et seulement pour les infos absentes du brief :

1. **Livrable** — quoi exactement ? (ex : article SEO 1500 mots / post LinkedIn carrousel / prompt Midjourney portrait)
2. **Audience & ton** — pour qui ? quel registre ? (B2B SaaS expert / B2C lifestyle décontracté / etc.)
3. **Contraintes clés** — mots-clés SEO, longueur, format de sortie, ce qu'il faut éviter

Ne re-demande jamais une info déjà donnée.

## Choix du framework

- **CO-STAR** → texte long, persona important, contexte riche (articles, newsletters, copywriting)
- **RISEN** → tâche cadrée et itérable (posts sociaux, légendes, variations A/B)
- **XML tagging** → prompt destiné à Claude, ou multimodal (Midjourney, DALL-E, briefs visuels)

Détails frameworks + templates marketing prêts à adapter : voir `references/frameworks.md`.

## Sortie

1. Le prompt complet dans un bloc markdown copiable.
2. Une ligne « Framework : X — pourquoi : ... » (15 mots max).
3. Si pertinent, 1 variante alternative en bullet.

Reste concis. Pas de préambule, pas de conclusion verbeuse.
