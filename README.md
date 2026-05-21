# Assistant Matis Clouet — Projet Claude

Un assistant conversationnel qui incarne la connaissance, les idées et la manière de penser de **Matis Clouet** — entrepreneur français, fondateur de The Ecosystem et Archimède Capital, spécialiste du scaling d'offres high-ticket pour agences, coachs et consultants.

Ce repo contient tout ce qu'il faut pour recréer le projet dans Claude.

---

## Ce que contient ce repo

### `instructions.md`
Les instructions système du projet. C'est le prompt qui définit l'identité, le ton, la posture et les règles de l'assistant. À coller dans les "Instructions" du projet Claude.

### `tone_of_voice_matis_clouet.md`
Analyse complète du tone of voice de Matis Clouet, basée sur l'ensemble de ses transcripts YouTube et posts LinkedIn. Couvre :
- Identité et positionnement
- Style d'écriture et de parole
- Structure de ses contenus
- Posture et personnalité
- Exemples verbatim
- Synthèse pour réplication

Ce document fait partie de la knowledge base du projet (à uploader aussi dans Claude).

### `documents/`
La knowledge base brute. Contient :
- **Transcripts YouTube** : toutes les vidéos de Matis Clouet jusqu'à début mai 2026
- **Posts LinkedIn** : le contenu textuel de tous ses posts LinkedIn depuis le début jusqu'à début mai 2026
- **`tone_of_voice_matis_clouet.md`** : l'analyse du tone of voice (doublon avec le fichier à la racine, présent ici pour être uploadé dans le projet)

---

## Comment installer le projet dans Claude

### Étape 1 — Télécharger les fichiers
Clone ou télécharge ce repo en local sur ton ordi.

```bash
git clone https://github.com/[ton-username]/[nom-du-repo].git
```

Ou clique sur le bouton vert **"Code" → "Download ZIP"** sur GitHub.

### Étape 2 — Créer un nouveau projet dans Claude
- Va sur [claude.ai](https://claude.ai)
- Dans la sidebar gauche, clique sur **"Projects"** → **"New project"**
- Donne-lui un nom (ex: `Matis Clouet Assistant`)

### Étape 3 — Coller les instructions
- Dans ton nouveau projet, clique sur **"Set custom instructions"** (ou "Instructions du projet")
- Ouvre `instructions.md` de ce repo
- Copie tout le contenu et colle-le dans le champ instructions
- Sauvegarde

### Étape 4 — Uploader la knowledge base
- Dans ton projet Claude, va sur **"Add content"** (ou "Project knowledge")
- Upload **tous les fichiers du dossier `documents/`** d'un coup (drag & drop fonctionne)
- Attends que Claude finisse d'indexer

### Étape 5 — C'est clean
Lance une conversation dans le projet et teste avec une question type :
- *"Quelle est la méthode de Matis pour passer de 5k à 50k/mois ?"*
- *"Comment Matis structure son offre hybride ?"*
- *"Qu'est-ce qu'un Value Asset selon Matis ?"*

L'assistant doit répondre dans le ton de Matis, en citant les sources.

---

## Précisions sur les sources

- Les transcripts YouTube vont **du début de la chaîne jusqu'à début mai 2026 (vidéo + shorts)**
- Les posts LinkedIn couvrent **tout l'historique du compte jusqu'à début mai 2026**
- Le tone of voice a été extrait par analyse de l'ensemble de ces contenus

Si tu veux mettre à jour le projet avec du contenu plus récent, il suffit d'ajouter les nouveaux fichiers `.txt` dans le dossier `documents/` et de les uploader dans le projet Claude.

---

## Ce que cet assistant fait

- Répond à des questions sur le scaling high-ticket, les offres hybrides, le funnel, le closing, le recrutement, le marketing organique, etc.
- Cite ses sources (vidéo, post LinkedIn)
- Croise plusieurs sources quand l'info est traitée à plusieurs endroits
- Extrapole à partir de la logique de Matis si le sujet n'est pas directement couvert (en le précisant)

## Ce qu'il ne fait pas

- Il n'est **pas Matis Clouet lui-même**. Il ne prend pas de décisions personnelles, n'envoie pas de messages, ne représente pas officiellement The Ecosystem
- Il **n'invente pas** de chiffres, de noms de clients ou de résultats
- Il **ne donne pas** de conseils financiers, juridiques ou fiscaux au nom de Matis

---

## Disclaimer

Ce projet est un outil pédagogique non-officiel basé sur du contenu public publié par Matis Clouet sur YouTube et LinkedIn. Il n'est pas affilié à The Ecosystem ni à Archimède Capital.
