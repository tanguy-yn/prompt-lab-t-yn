# Frameworks et templates marketing

Référence détaillée chargée à la demande. Trois frameworks, suivis de templates marketing prêts à adapter.

## 1. CO-STAR

Pour textes longs et nuancés (articles, newsletters, pages de vente).

| Section | Rôle | Exemple |
|---|---|---|
| **C** ontext | Cadre de la mission | « Tu rédiges pour une SaaS B2B en croissance qui cible des CMO. » |
| **O** bjective | Résultat attendu | « Produire un article SEO de 1500 mots sur l'attribution marketing. » |
| **S** tyle | Style d'écriture | « Style éditorial type Lenny's Newsletter, exemples concrets, zéro jargon creux. » |
| **T** one | Registre | « Confiant, factuel, légèrement provocateur. » |
| **A** udience | Cible | « CMO et Heads of Growth en SaaS B2B 50–500 employés. » |
| **R** esponse | Format de sortie | « Markdown : H1, 4 H2, intro 80 mots, conclusion avec CTA. » |

Template :

```
# Contexte
[1-2 phrases de cadre]

# Objectif
[Livrable précis et mesurable]

# Style
[Référence concrète + 2-3 attributs stylistiques]

# Ton
[2-3 adjectifs]

# Audience
[Persona précis : rôle, secteur, niveau d'expertise, douleur]

# Format de sortie
[Structure exacte attendue]
```

## 2. RISEN

Pour tâches cadrées et itératives (posts sociaux, légendes, variations).

| Section | Rôle |
|---|---|
| **R** ole | Persona du modèle |
| **I** nstructions | Action principale |
| **S** teps | Étapes ordonnées |
| **E** nd goal | Résultat final |
| **N** arrowing | Contraintes (longueur, ton, exclusions) |

Template :

```
Rôle : Tu es [persona spécifique].
Instructions : [Action principale en une phrase].
Étapes :
1. [Étape 1]
2. [Étape 2]
3. [Étape 3]
Objectif final : [Résultat attendu].
Contraintes :
- Longueur : [...]
- Ton : [...]
- Éviter : [...]
```

## 3. XML tagging (Claude / multimodal)

Pour prompts destinés à Claude, ou prompts multimodaux (Midjourney, DALL-E, briefs visuels).

```xml
<role>Directeur artistique senior, spécialisé en photographie de marque B2C lifestyle.</role>

<task>Génère un prompt Midjourney pour une bannière LinkedIn.</task>

<context>
- Marque : [nom]
- Produit : [description]
- Mood : [3 adjectifs]
- Référence visuelle : [si dispo]
</context>

<constraints>
- Format : 1584x396 (LinkedIn banner)
- Style : photographie éditoriale, lumière naturelle
- Éviter : illustration, texte dans l'image, IA-look
- Paramètres MJ : --ar 4:1 --style raw --v 6
</constraints>

<output_format>
Un seul prompt Midjourney sur une ligne, suivi des paramètres.
</output_format>
```

## Templates marketing prêts à adapter

### Article de blog SEO (CO-STAR)

```
# Contexte
Tu es rédacteur SEO senior pour [secteur]. Le site cible [persona].

# Objectif
Article de [N] mots sur le mot-clé principal "[KW]", optimisé pour ranker top 3 sur Google FR.

# Style
Type [référence éditoriale]. Exemples chiffrés. H2/H3 en question. Listes courtes.

# Ton
Expert mais accessible. Directif. Zéro fluff.

# Audience
[Rôle], [maturité], cherche [intention de recherche].

# Format
- Title tag (60 car) + meta description (155 car)
- H1 + intro 80 mots avec promesse
- 4-6 H2 (au moins 2 en question)
- FAQ finale (3 Q/R)
- CTA conclusion
- Mots-clés secondaires à intégrer naturellement : [...]
```

### Post LinkedIn (RISEN)

```
Rôle : Copywriter LinkedIn pour [persona émetteur, ex : fondateur SaaS B2B].
Instructions : Écris un post LinkedIn qui raconte [angle/insight].
Étapes :
1. Hook en 1 ligne qui crée la friction (chiffre, contre-intuition, mini-histoire).
2. 3-5 lignes courtes qui développent (1 idée par ligne).
3. Pivot ou retournement.
4. CTA implicite ou question ouverte.
Objectif final : Générer commentaires de pairs, pas likes superficiels.
Contraintes :
- 800-1200 caractères
- Aucun emoji décoratif (1 seul autorisé en hook)
- Pas de "J'espère que ce post vous a plu"
- Pas de hashtags en bas
```

### Carrousel Instagram (RISEN)

```
Rôle : Social media manager pour marque [niche].
Instructions : Crée un carrousel Instagram de 8 slides sur [sujet].
Étapes :
1. Slide 1 : hook visuel + promesse
2. Slides 2-7 : un point clé par slide, 1 phrase max
3. Slide 8 : récap + CTA (save / partage)
Objectif final : Sauvegardes maximales (signal d'engagement IG).
Contraintes :
- Max 12 mots par slide
- Ton [...]
- Caption 100-150 mots avec 1 question
- 5-8 hashtags pertinents
```

### Prompt Midjourney bannière (XML)

```xml
<role>Directeur artistique en photographie commerciale.</role>
<task>Génère le prompt Midjourney d'une bannière [plateforme].</task>
<subject>[sujet principal — produit, scène, personne]</subject>
<style>
- Photographie [type : éditoriale / studio / lifestyle]
- Lumière [naturelle / contre-jour / golden hour]
- Composition [règle des tiers / centrée / minimaliste]
- Palette [...]
</style>
<negative>illustration, 3D render, texte, watermark, deformed, AI-look</negative>
<params>--ar [ratio plateforme] --style raw --v 6 --s [stylize]</params>
```

### Newsletter (CO-STAR + structure)

```
# Contexte
Tu es l'auteur de [nom newsletter], lue par [audience]. Édition #[N].

# Objectif
Email de [N] mots, taux d'ouverture cible 45%+, CTR cible 8%+.

# Style
Conversationnel, "you". Une idée principale, exemples concrets, lien clair.

# Ton
Comme un message d'un pair compétent à un autre.

# Audience
[Persona précis, abonné depuis [...], attend [valeur]].

# Format
- Subject line (50 car) — pas de clickbait
- Preview text (100 car) qui complète, ne répète pas
- Hook en 2 lignes
- Idée centrale : 3 paragraphes max
- 1 lien sortant principal
- PS qui tease la prochaine édition
```

### Prompt copywriting (CO-STAR resserré)

```
Tu es copywriter direct response, école Eugene Schwartz/Halbert.
Écris [livrable : email cold / landing hero / ad Meta].
Audience : [persona], au stade [awareness level].
Promesse principale : [bénéfice mesurable].
Preuves : [proof points concrets].
CTA : [action unique].
Contraintes : [longueur, plateforme, ton de marque, exclusions].
```

## Quel framework choisir — règle rapide

| Livrable | Framework |
|---|---|
| Article 800+ mots | CO-STAR |
| Newsletter | CO-STAR |
| Page de vente | CO-STAR |
| Post LinkedIn / X / Threads | RISEN |
| Légende Instagram | RISEN |
| Carrousel | RISEN |
| Email court | RISEN |
| Prompt Midjourney / DALL-E | XML |
| Brief visuel pour designer | XML |
| Prompt destiné à Claude | XML |
