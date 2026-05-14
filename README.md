# Concordancier multilingue
Application de concordancier multilingue développée en vibe-coding en R et Shiny dans le cadre d’un travail de fin d'études de Master de spécialisation en linguistique appliquée.

## Objectif

Ce concordancier a été développé dans le cadre d’un travail de recherche en linguistique de corpus et traitement automatique du langage (TAL), afin d’explorer :

- Les fréquences lexicales 
- Les collocations 
- La visualisation de mots-clés en contexte (KWIC) 
- L’alignement bilingue

---

## Fonctionnalités

- Analyse de fréquences 
- Concordancier KWIC 
- Extraction des collocations 
- Génération de graphes 
- Nuage de mots 
- Alignement de corpus parallèles 
- Export des résultats en Excel

---

## Technologies utilisées

- R
- Shiny
- DT
- openxlsx
- stringi
- showtext
- sysfonts

---

## Format de texte supporté

UTF-8.

---

## Installation

### 1. Cloner le repository

```bash
git clone https://github.com/USERNAME/concordancier-memoire.git
```

### 2. Installer les dépendances

```r
source("requirements.R")
```

### 3. Lancer l'application

```r
shiny::runApp()
```

---

# License

MIT License

Copyright (c) 2026 EloNoni

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
