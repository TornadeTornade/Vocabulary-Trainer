# 🇬🇧 English Vocabulary Trainer

Petit site web en **HTML / JavaScript / TailwindCSS** pour réviser efficacement son vocabulaire anglais à partir de listes de mots au format JSON.

L’objectif est simple :
tu choisis une fiche de vocabulaire, le site t’affiche un mot et tu dois saisir sa traduction dans le bon sens.

---

## ✨ Fonctionnalités

* Choix du **mode d’entraînement**

  * FR → EN
  * EN → FR
  * Mode mix (aléatoire)

* Sélection de **plusieurs listes de vocabulaire** (fichiers JSON)

* **Import** de tes propres listes personnalisées

* **Export** de ta liste actuelle

* Suivi du **score en temps réel**

* Système de **détection des erreurs**

* Mode **révision automatique** basé sur tes fautes récentes

* Navigation rapide au clavier (touche **Entrée**)

* Interface responsive, simple et lisible

---

## 🗂️ Format des fichiers JSON

Chaque liste de vocabulaire doit respecter ce format :

```json
[
  { "fr": "pays", "en": "country" },
  { "fr": "peuple autochtone", "en": "indigenous people" }
]
```

---

## 🚀 Lancer le projet

Aucune installation nécessaire.

1. Télécharge le projet
2. Ouvre le fichier `index.html` dans ton navigateur

ou utilise une extension type **Live Server**.

---

## ➕ Ajouter une nouvelle fiche de vocabulaire

1. Crée un nouveau fichier JSON en respectant le format
2. Place-le dans le dossier du projet
3. Ajoute son nom dans le `<select>` :

```html
<option value="MA_LISTE.json">Ma liste</option>
```

---

## 📚 Utilisation

1. Choisis le mode d’entraînement
2. Sélectionne la fiche de mots
3. Traduis les mots affichés
4. Consulte tes erreurs et active le **mode révision**

---

## 🧠 Logique pédagogique

Le site ne se contente pas d’afficher des mots aléatoires :

* Les fautes sont mémorisées
* Un bouton permet de réviser uniquement les mots ratés
* Les mots correctement retraduits disparaissent de la liste d’erreurs
* Les 10 dernières erreurs sont conservées en mémoire

Cela permet une **révision ciblée et efficace**.

---

## 🛠️ Technologies utilisées

* HTML
* TailwindCSS
* JavaScript (vanilla)

---

## 🎯 Objectif du projet

Fournir un outil minimaliste, rapide et efficace pour apprendre du vocabulaire sans distraction, directement depuis le navigateur.

---

## 📌 Idées d’amélioration

* Sauvegarde du score en local (LocalStorage)
* Ajout d’un minuteur
* Gestion de synonymes multiples
* Système de niveaux / progression
* Interface pour créer ses listes sans passer par le JSON

---

## 📄 Licence

Projet libre d’utilisation et modifiable.
