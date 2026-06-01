# prompt-lab

Atelier de prompts pour le marketing digital. Trois skills légers pour créer, optimiser et auditer des prompts GPT — pensés pour Chef de Projet IA et créateurs de GPT personnalisés.

## Skills

| Skill | Quand l'invoquer |
|---|---|
| `/build-prompt` | Construire un prompt from scratch pour un livrable marketing (article SEO, post LinkedIn, carrousel Instagram, prompt Midjourney, newsletter, copywriting) |
| `/optimize-prompt` | Améliorer un prompt existant en gardant son intention |
| `/audit-prompt` | Diagnostiquer un prompt sans le réécrire (note /25 sur 5 axes) |

## Frameworks utilisés

- **CO-STAR** — Context, Objective, Style, Tone, Audience, Response. Pour textes longs.
- **RISEN** — Role, Instructions, Steps, End goal, Narrowing. Pour tâches cadrées.
- **XML tagging** — Tags structurés. Pour Claude et prompts multimodaux.

## Optimisation tokens

Chaque `SKILL.md` reste sous 200 mots. Les frameworks détaillés, templates marketing et checklists vivent dans `references/` et ne se chargent qu'à la demande, quand le skill en a besoin.

## Structure

```
prompt-lab/
├── .claude-plugin/plugin.json
├── skills/
│   ├── build-prompt/
│   │   ├── SKILL.md
│   │   └── references/frameworks.md
│   ├── optimize-prompt/
│   │   ├── SKILL.md
│   │   └── references/optimization-patterns.md
│   └── audit-prompt/
│       ├── SKILL.md
│       └── references/audit-checklist.md
└── README.md
```

## Inspirations

Patterns sélectionnés depuis `danielmiessler/fabric` (rédaction, écriture, optimisation) et `f/prompts.chat` (templates marketing, copywriting, réseaux sociaux).
