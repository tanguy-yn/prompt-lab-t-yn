---
name: audit-prompt
description: Analyse les faiblesses d'un prompt GPT marketing digital sans le réécrire. Déclenche-toi quand l'utilisateur dit "/audit-prompt", "audite ce prompt", "analyse ce prompt", "qu'est-ce qui cloche dans ce prompt", "diagnostique mon prompt", "donne-moi un retour sur ce prompt", ou demande un avis critique sans réécriture.
---

# Audit prompt

Diagnostique un prompt sans le réécrire. L'utilisateur veut comprendre ce qui cloche, pas recevoir une nouvelle version.

## Méthode

Évalue le prompt sur 5 axes, note chacun de 0 à 5 :

1. **Clarté de l'objectif** — sait-on précisément ce qu'on attend en sortie ?
2. **Contexte & persona** — le rôle du modèle et l'audience sont-ils définis ?
3. **Format de sortie** — la structure attendue est-elle spécifiée (longueur, sections, type de fichier) ?
4. **Contraintes** — ton, style, exclusions, mots-clés sont-ils explicites ?
5. **Activabilité marketing** — un GPT pourrait-il produire un livrable utilisable tel quel ?

Calcule la note globale /25.

Checklist détaillée par axe et par livrable marketing : voir `references/audit-checklist.md`.

## Sortie

```
## Audit /25 : [score]

| Axe | Note | Verdict |
|---|---|---|
| Clarté objectif | x/5 | [1 phrase] |
| Contexte & persona | x/5 | [1 phrase] |
| Format de sortie | x/5 | [1 phrase] |
| Contraintes | x/5 | [1 phrase] |
| Activabilité marketing | x/5 | [1 phrase] |

## 3 risques majeurs
1. [...]
2. [...]
3. [...]

## 3 améliorations prioritaires
1. [...]
2. [...]
3. [...]
```

**Ne réécris pas le prompt.** Reste en mode diagnostic. Si l'utilisateur veut une réécriture après, il invoquera `/optimize-prompt`.
