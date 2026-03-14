# HUNTER Tarot OS

Interface expérimentale du module **Tarot** du système **HUNTER_OS**.

Ce projet propose une interface web minimaliste permettant d’ouvrir un espace de consultation symbolique (tarot / terminal narratif) à partir d’une architecture simple basée sur **GitHub Pages**.

---

## Architecture

Le projet sépare volontairement :

- **Interface web** (hébergée sur GitHub Pages)
- **Médias audio / vidéo** (hébergés en externe)

Cela permet de garder un dépôt léger et compatible avec les limites de GitHub.

GitHub Pages
(interface HTML)
↓
Boutons / interactions
↓
Médias externes (audio / vidéo)

---

## Structure du projet

tarot/
│
├─ index.html
├─ interface/
│   ├─ tarot.html
│   └─ terminal.html
│
├─ .gitignore
└─ README.md

### Description

| fichier | rôle |
|------|------|
| `index.html` | point d’entrée de l’interface |
| `interface/tarot.html` | interface principale du module tarot |
| `interface/terminal.html` | interface terminal / invocation |
| `.gitignore` | empêche les fichiers lourds d’être versionnés |

---

## Médias

Les fichiers suivants **ne sont pas stockés dans le dépôt** :

- `.mp3`
- `.mp4`
- autres médias lourds

Ils sont chargés depuis un stockage externe afin de respecter les limites GitHub.

---

## Déploiement

Le projet est conçu pour fonctionner directement avec **GitHub Pages**.

URL :

https://hunter-sh.github.io/tarot/

---

## Objectif

Ce dépôt sert de **prototype d’interface pour un module du système HUNTER_OS** :

- interface rituelle / narrative
- expérience interactive
- expérimentation interface + symbolique

Le projet est volontairement **minimal et modulaire** afin de pouvoir être intégré dans d'autres modules du système.

---

## Licence

Projet expérimental — usage narratif / artistique.


⸻

![Hunter Tarot OS](hunter.png)
