# Introduction à Python pour les profils TI et développement

Kit de formation complet de **2 h 15 (135 minutes)** conçu pour initier des étudiants et professionnelles/professionnels ayant déjà des bases dans un autre langage de programmation (C#, Java ou JavaScript).

Aucune installation logicielle n'est requise pour les étudiants : tous les ateliers pratiques s'exécutent directement dans le navigateur via **Google Colab**.

---

## 📁 Structure du projet

```text
sf-intro-python/
├── slides/
│   └── index.html                     # Présentation interactive complète (22 diapos)
├── colab/
│   ├── atelier_python_etudiant.ipynb   # Carnet interactif prêt à rouler pour les étudiants
│   └── atelier_python_corrige.ipynb    # Carnet de référence complet
├── docs/
│   ├── cahier_du_participant.pdf      # Résumé théorique et aide-mémoire de 2 pages pour l'étudiant
│   └── cahier_du_participant.html     # Source HTML du cahier participant
└── README.md                          # Guide d'utilisation du matériel de formation
```

---

## 🚀 Guide d'utilisation des supports

### 1. La présentation HTML (`slides/index.html`)
Ouvrez simplement le fichier `slides/index.html` dans n'importe quel navigateur moderne (Chrome, Edge, Firefox, Safari).

* **Commandes au clavier :**
  * `Flèche droite` / `Espace` / `Page bas` : Diapositive suivante
  * `Flèche gauche` / `Page haut` : Diapositive précédente
  * `Touche F` : Basculer en mode plein écran
  * `Début` / `Fin` : Première ou dernière diapositive

### 2. Le carnet Google Colab (`colab/`)
* **`atelier_python_etudiant.ipynb`** : Carnet complet où **tout le code est pré-écrit, testé et prêt à rouler**. Les étudiants n'ont pas à taper de blocs complexes ni à copier-coller (ce qui casserait l'indentation). Ils exécutent simplement les cellules de haut en bas avec `Maj + Entrée` et peuvent modifier de petites valeurs dans les blocs « 💡 À essayer ».
* **`atelier_python_corrige.ipynb`** : Version de référence identique avec toutes les sorties pré-générées.

**Lien direct Google Colab pour les étudiants :**
Vous pouvez leur partager directement ce lien pour ouvrir le carnet en un clic :  
[Ouvrir l'atelier dans Google Colab](https://colab.research.google.com/github/martindufresne/intro-python/blob/main/colab/atelier_python_etudiant.ipynb)

### 3. Les documents PDF (`docs/`)
* **`docs/cahier_du_participant.pdf`** : Document de synthèse imprimable recto-verso de 2 pages à remettre aux étudiants au début ou à la fin du cours. Il inclut un **tableau de correspondance syntaxique complet (C#/Java/JS vers Python)**, le rappel des 4 structures de données et des idiomes clés.

---

## 🛠 Régénérer le cahier du participant en PDF

Si vous apportez des modifications au texte du fichier `docs/cahier_du_participant.html`, vous pouvez réexporter la version PDF en ligne de commande avec Google Chrome :

```bash
"/Applications/Google Chrome.app/Contents/MacOS/Google Chrome" --headless --disable-gpu --no-pdf-header-footer --print-to-pdf="docs/cahier_du_participant.pdf" "file://$(pwd)/docs/cahier_du_participant.html"
```
