# skill-claude-note-exec-deck-chu

Skill Claude pour produire des **notes executives** et **decks exécutifs** dans le style visuel du CHU de Québec — Université Laval, selon la méthode de présentation de Johanne Martel ([presenterautrement.com](https://www.presenterautrement.com)).

Produit deux livrables complémentaires :
1. Une fiche synthèse 1 page (note executive)
2. Une structure de deck slide par slide, avec notes du présentateur

---

## Installation

### Claude Code (CLI)

```bash
cp commands/deck-executif.md ~/.claude/commands/deck-executif.md
```

Puis dans une conversation Claude Code :

```
/deck-executif [ton sujet et contexte]
```

### Claude.ai (web)

Colle le contenu de `commands/deck-executif.md` au début d'une nouvelle conversation, puis décris ton sujet.

---

## Assets

Le dossier `assets/` contient les logos officiels CHU de Québec :

| Fichier | Usage |
|---------|-------|
| `LOGO_CHU_Blanc.svg` | Fond foncé (#01264F) — usage principal |
| `LOGO_CHU_couleurs.svg` | Fond clair |

Place ces fichiers dans ton dossier de projet PowerPoint / Google Slides pour les insérer dans tes slides.

---

## Ce que ça produit

### Note executive
Structure en 4 blocs : Contexte · Situation actuelle · Proposition · Décisions demandées

### Deck exécutif
Arc narratif en 7 temps :
1. Ouverture — capter l'attention
2. Pourquoi — l'impératif
3. Situation — ce qui se passe aujourd'hui
4. Proposition — ce qu'on propose
5. Développement — 1 concept par slide
6. Décisions — actions demandées, numérotées
7. Clôture — tagline + image émotionnelle

Chaque slide inclut : titre · visuel suggéré · contenu affiché (mots-clés) · notes du présentateur

---

## Principes (méthode Johanne Martel)

- Une slide = 1 concept, compris en 3 secondes
- 3-4 éléments maximum par slide
- Double codage : visuel + auditif
- Le deck soutient le présentateur — il ne le remplace pas
- La note executive et le deck sont deux documents distincts et complémentaires

---

## Palette CHU

| Couleur | Hex | Usage |
|---------|-----|-------|
| Bleu foncé | `#01264F` | Fond slides |
| Turquoise | `#00ABC4` | Accent primaire |
| Corail | `#D25D66` | Deadlines, call to action |
| Gris pâle | `#EFEFEF` | Texte sur fond foncé |
| Turquoise foncé | `#357E94` | Éléments secondaires |

---

Développé par la DPVDTN — CHU de Québec – Université Laval
