# Mots Mêlés — Jeux de grilles

Une collection de **jeux de grilles** en ligne : Mots mêlés, Sudoku et Mots croisés. Chaque jeu génère des grilles aléatoires et permet de les exporter en PDF prêtes à imprimer.

---

## 🎮 Les jeux

### 🔤 Mots mêlés (`wordsearch/`)
Composez votre grille ou choisissez parmi **30+ thèmes** (animaux, pays, fruits, sciences…). La grille est générée automatiquement et exportable en PDF.

### 🔢 Sudoku (`sudoku/`)
Générez des grilles de Sudoku à **solution unique** avec **4 niveaux de difficulté** (Facile, Moyen, Difficile, Expert). Mode notes, pavé numérique, détection d'erreurs et timer intégrés. Export PDF avec grille + solution.

### ✏️ Mots croisés (`crossword/`)
Générez des grilles de mots croisés avec **mots et définitions** par thème. Numérotation automatique, indices horizontaux et verticaux. Export PDF en 2 pages : grille à jouer + solution.

---

## 🚀 Features

- **Génération automatique** : algorithmes de placement intelligent pour chaque type de jeu
- **Aperçu visuel** : prévisualisation en temps réel avant export
- **Export PDF** : téléchargement d'un PDF optimisé pour l'impression
- **Thèmes** : 30+ catégories de mots pré-chargés (Mots mêlés et Mots croisés)
- **Dictionnaire unifié** : `themes.json` partagé entre Mots mêlés et Mots croisés — 935 mots avec définitions sur 31 thèmes
- **Difficultés** : 4 niveaux pour le Sudoku
- **Mode notes** : Sudoku avec gestion des candidats
- **Navigation clavier** : flèches + chiffres pour le Sudoku

---

## 📝 Todo / Améliorations

- **Choisir une langue** (ouvrir le projet à plus de personnes via la multilinguisation)
- **Passer sur Tailwind CSS** (remplacer le CSS personnalisé par des classes Tailwind)
- **Dissocier JS et CSS du HTML** (réorganiser le code en fichiers séparés)
- **Sauvegarde locale** (reprendre une partie en cours)
- **Nouveaux jeux** (Kakuro, Scrabble…)

---

## 🛠️ Utilisation

Ouvrez `index.html` dans un navigateur — aucune installation nécessaire. La page d'accueil propose les trois jeux.

### Mots mêlés
1. Cliquez sur **🔤 Mots mêlés**
2. Choisissez un thème ou entrez vos propres mots
3. Ajustez la taille de la grille
4. Cliquez sur **Générer** puis **Exporter en PDF**

### Sudoku
1. Cliquez sur **🔢 Sudoku**
2. Choisissez un niveau de difficulté
3. Jouez directement ou cliquez sur **Exporter en PDF**

### Mots croisés
1. Cliquez sur **✏️ Mots croisés**
2. Choisissez un thème
3. Cliquez sur **Générer** puis **Exporter en PDF**

---

## 📁 Structure

```
index.html          ← Page d'accueil (choix du jeu)
wordsearch/         ← Jeu de mots mêlés
  index.html
  themes.json
  dico.txt
sudoku/             ← Jeu de Sudoku
  index.html
crossword/          ← Jeu de mots croisés
  index.html
  themes.json
  dico.txt
themes.json         ← Référence (racine)
dico.txt            ← Référence (racine)
```

---

## 📐 Tech Stack

- HTML5 / CSS3 (en ligne)
- JavaScript vanilla
- [JSPDF](https://github.com/jspdf/jspdf) pour la génération de PDF

---

## Licence

Ce projet est distribué sous licence **GNU GPL-3.0**.

---

*Built with ❤️ for language learners & puzzle enthusiasts.*
