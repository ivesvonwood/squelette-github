Ce projet est un squelette de projet open source de l'État de Genève à publier sur GitHub.
Il contient les fichiers recommandés par GitHub pour réaliser une mise en open source harmonieuse du projet.

# Usage

L'usage le plus simple est de copier (avec ou sans git clone) les fichiers de ce projet dans votre projet.

Ensuite, apporter les modifications ci-dessous.

## Fichier README.md

Ce document fournit la description fonctionnelle et technique de votre projet. Il est obligatoire.
Remplacer le contenu de ce fichier par un contenu plus adéquat.

## Fichier LICENSE.txt

Ce document définit la licence sous laquelle votre projet est posé sur GitHub. Le choix de l'État s'est porté
sur la licence AGPL 3.0.

Aucune modification nécessaire : copier le fichier `LICENSE.txt` tel quel, à la racine de votre projet.

## Fichier LICENSE-sources.txt

- Ouvrir le fichier `LICENSE-sources.txt` et modifier les champs à changer : 
  - `Nom du logiciel`
  - `Date`. Remplacer par exemple par `2015 - 2018`.

- Dans chaque fichier source du projet, introduire en en-tête le contenu du fichier `LICENCE-source.txt` 
ainsi modifié.

- Détruire le fichier `LICENSE-sources.txt`.

## Fichier CONTRIBUTING.md

Ce document founit aux développeurs de la communauté des instructions sur la manière de collaborer à votre projet.
Il est facultatif, mais recommandé.

Selon que votre projet est en français ou en anglais, renommez le fichier `CONTRIBUTING-fr.md` ou le fichier
`CONTRIBUTING-en.md` en `CONTRIBUTING.md`, puis détruisez l'autre fichier. Votre fichier `CONTRIBUTING.md` est à
laisser à la racine de votre projet.

Ces fichiers ne sont que des exemples : vous êtes libre de choisir un autre contenu.
Vous pouvez en particuliuer consulter les références proposées par GitHub au bas de sa page d'
[instructions](https://help.github.com/articles/setting-guidelines-for-repository-contributors).
Si le format `.md` (markdown) vous rebute, vous être libre de créer un fichier `CONTRIBUTING.txt` en format texte.

## Fichier CODE_OF_CONDUCT.md

Ce document fournit aux développeurs de la communauté les attentes de l'État sur l'attitude des participants
au projet. Il vise à établir une atmosphère positive et respecteuse.
Il est facultatif.

Pour l'instant nous ne proposons qu'une version en anglais.

Ce fichier `CODE_OF_CONDUCT.md` est à laisser à la racine de votre projet.

Pour en savoir davantage sur le sujet, voir par exemple [ici](https://opensource.guide/code-of-conduct).

## Fichiers ISSUE_TEMPLATE

Ces fichiers 

## Pages github.io

...


## Fichier .gitignore

Si votre projet est un projet Java, le fichier `gitignore_java` peut vous intéresser. Renommez-le simplement
en `.gitignore` (sans oublier le `.` en préfixe) et laissez-le à la racine du projet.

Si votre projet n'est pas un projet Java, vous pouvez détruire le fichier `gitignore_java`. 


## GitHub

Dans GitHub, n'oubliez pas d'ajouter une description en une ligne de votre projet (bouton `Edit` sur la page
du projet).

Une fois que tous ces fichiers ont été intégrés à votre projet sur GitHub, pour vérifier qu'ils sont adéquats, 
allez sur l'onglet `Insights`, puis sur l'option `Community`, et vérifiez que les voyants sont au vert.
Vous devez être connecté à GitHub pour voir l'option `Community`.

Vérifiez que vous êtes bien observateur de votre propre projet (bouton `Watch`).
Sans cela, si un développeur de la communauté soumet une pull request ou une "issue", vous ne serez pas averti
par courriel.
