# Patterns d'optimisation

Référence détaillée chargée à la demande. Anti-patterns marketing courants + transformations à appliquer.

## Les 8 anti-patterns récurrents

### 1. Persona absent ou générique

**Symptôme** : « Tu es un expert en marketing. »

**Pourquoi c'est faible** : aucun ancrage stylistique, le modèle régresse vers la moyenne.

**Transformation** :
> Tu es head of content pour une SaaS B2B 50–200 employés, ancien journaliste tech, tu écris dans un style proche de [référence]. Tu as 8 ans d'expérience SEO et tu détestes le jargon creux.

### 2. Audience floue

**Symptôme** : « pour des professionnels » / « pour des entrepreneurs ».

**Transformation** : ajouter rôle exact + maturité + douleur + niveau d'expertise sur le sujet.

> Audience : Heads of Demand Gen en SaaS B2B 100–500 employés, qui gèrent un budget paid de 50k–200k €/mois et n'arrivent pas à attribuer correctement leurs leads MQL.

### 3. Objectif non mesurable

**Symptôme** : « écris un bon article ».

**Transformation** : ajouter au minimum un attribut mesurable (longueur, mots-clés, structure, métrique cible).

> Article de 1500 mots qui ranke top 3 sur "[KW]" en France. Doit obtenir au moins 60 secondes de temps de lecture moyen.

### 4. Format de sortie absent

**Symptôme** : aucune contrainte sur la structure → output imprévisible.

**Transformation** : décrire la structure attendue avec précision.

```
Format :
- Title tag (60 car max)
- Meta description (155 car max)
- H1 unique
- 4-6 H2 dont 2 minimum en question
- FAQ finale (3 Q/R)
- Tableau récapitulatif si pertinent
```

### 5. Contraintes en positif uniquement

**Symptôme** : on dit ce qu'on veut, jamais ce qu'on ne veut pas.

**Transformation** : ajouter une section « Éviter ».

```
Éviter :
- Phrases qui commencent par "Dans un monde où"
- Le mot "révolutionnaire"
- Les listes à puces de plus de 5 items
- "J'espère que cet article vous a plu"
- Tout emoji décoratif
```

### 6. Pas d'exemples

**Symptôme** : le ton et le style restent abstraits.

**Transformation** : ajouter 1-2 exemples du résultat attendu, ou une référence concrète (newsletter, marque, auteur).

> Style proche de Lenny's Newsletter : phrases courtes, exemples chiffrés tirés d'entreprises connues, sous-titres en question, transitions explicites.

### 7. Tâche multiple non décomposée

**Symptôme** : « Écris un article SEO + 5 posts LinkedIn + une newsletter à partir de ça. »

**Transformation** : découper en étapes ou demander un seul livrable. Si tâche multiple voulue, structurer en steps RISEN.

### 8. Verbosité parasite

**Symptôme** : « Je voudrais que tu m'aides à essayer de... »

**Transformation** : impératif direct.

> « Rédige... » / « Génère... » / « Liste... »

## Transformations par livrable

### Article SEO

| Avant | Après |
|---|---|
| Persona vague | Rédacteur SEO senior + référence éditoriale |
| Pas de keywords | KW principal + 3-5 secondaires explicites |
| Longueur absente | Mots cibles + temps de lecture cible |
| Format implicite | Structure H1/H2/H3 + meta + FAQ |

### Post LinkedIn

| Avant | Après |
|---|---|
| « post engageant » | Hook explicite, pivot, CTA implicite |
| Pas de format | 800–1200 caractères, 1 idée par ligne |
| Pas d'anti-patterns | Liste « éviter » : emojis décoratifs, hashtags, "J'espère..." |

### Prompt image (Midjourney/DALL-E)

| Avant | Après |
|---|---|
| Description en français long | Tags anglais courts, ordonnés |
| Pas de paramètres MJ | `--ar`, `--style`, `--v`, `--s` explicites |
| Pas de negative prompt | `negative` pour éviter AI-look, watermark, deformed |
| Pas de référence | Photographe / mouvement / palette nommée |

### Newsletter

| Avant | Après |
|---|---|
| Sujet générique | Subject line < 50 car, preview text complémentaire |
| Pas de structure | Hook → idée centrale → 1 lien → PS |
| Pas de métrique cible | Open rate cible + CTR cible explicites |

## Règles de réécriture

- **Garder** l'intention initiale et le sujet — on optimise, on ne détourne pas.
- **Préserver** la voix de l'utilisateur si elle est exprimée.
- **Ne jamais** ajouter plus de 3 contraintes nouvelles d'un coup, sinon le prompt devient rigide.
- **Toujours** finir par un format de sortie explicite — c'est le levier #1 d'amélioration.
- **Tester mentalement** : si je relisais ce prompt dans 3 mois sans contexte, saurais-je quoi en attendre ?
