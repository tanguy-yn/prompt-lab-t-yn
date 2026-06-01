---
name: optimize-prompt
description: Améliore un prompt GPT marketing existant en gardant son intention. Déclenche-toi quand l'utilisateur dit "/optimize-prompt", "améliore ce prompt", "optimise mon prompt", "rends ce prompt meilleur", "réécris ce prompt", ou colle un prompt existant en demandant un upgrade.
---

# Optimize prompt

Réécris un prompt existant pour le rendre plus efficace, sans dénaturer son intention.

## Méthode

1. **Lis** le prompt fourni en entier avant toute action.
2. **Identifie** au maximum 3 faiblesses parmi : persona absent ou flou, contexte manquant, objectif imprécis, format de sortie non spécifié, contraintes vagues, verbosité, ambiguïté, exemples manquants.
3. **Choisis** le framework le plus adapté au livrable : CO-STAR (texte long), RISEN (tâche cadrée), XML tagging (multimodal ou Claude).
4. **Réécris** le prompt en intégrant les corrections.
5. **Justifie** en 3 bullets max ce qui change et pourquoi.

Si le prompt est déjà solide, dis-le franchement et propose une seule variante alternative (angle différent, framework différent, ou plus court/plus long selon le contexte).

Patterns d'optimisation détaillés et anti-patterns récurrents : voir `references/optimization-patterns.md`.

## Sortie

```
## Diagnostic
- Faiblesse 1 : [...]
- Faiblesse 2 : [...]
- Faiblesse 3 : [...]

## Prompt optimisé
[bloc copiable]

## Ce qui a changé
- [...]
- [...]
- [...]
```

Reste concis. Pas de blabla introductif.
