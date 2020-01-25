class: middle, center, inverse, title

# `SQL` en ligne

## Ou comment s'affranchir des outils 

François-Xavier Jollois

.footnote[lien vers le [site](https://github.com/jncharon/cours-sql/)]

---

# Présentation

### En quelques mots

- Interface d'enseignement du `SQL`
    - Partie *DML* : *Data Manipulation Language*
    - Requêtage avec `SELECT` uniquement 

- Intégration, dans une même application, de :
	- Contenu du cours et exercices
	- Interface de programmation

- Utilisation en DUT STID 1ère année
    - Module **M1302** : *Exploitation de données*


---

# Besoins

- Outil simple d'interrogation de données

- Utilisation du langage `SQL` primordial
	- pas d'outil *clic-bouton* 
	- pas d'assistant de requêtage

- Disponibilité maximale de l'outil pour les étudiants

- Pas de nécessité d'installer un logiciel sur leur ordinateur personnel pour le travail à la maison

- Simplification maximale de l'utilisation 
	- pas de fichier de données
	- pas de script sauvegardé
	- concentration de tout le cours (contenus et outil) 

---

class: middle, center, inverse

La solution ?

# Une application **web** et **dédiée**

---

# Et dans le détail

- Programmation en `JavaScript`

- Contenu écrit en [`markdown`](https://daringfireball.net/projects/markdown/)
    - Découpage de celui-ci en notions
    - Une notion par TP
    - Intégration de deux TP récapitulatifs
    - Sujet de TP noté intégré

- Bases de données au format [`sqlite`](https://www.sqlite.org/)

- Utilisation des librairies `JS` :
    - [`sql.js`](https://github.com/kripken/sql.js/) : traduction de `sqlite` en `JS`
    - [`jQuery`](https://jquery.com/) (et du plugin [`DataTables`](https://datatables.net/)) : manipulation des éléments de la page
    - [`ace`](https://ace.c9.io/) : zone de saisie de la requête
    - [`marked`](https://github.com/chjj/marked) : traduction `markdown` vers `HTML`
    - [`highlight`](https://highlightjs.org/) : mise en valeur des mots-clés

---

# Utilisation

- Accès au site web en début de TP

- Indication de la notion à voir

- Contenu d'une notion :
    - Explication de la notion
    - Exemples d'utilisation
    - Petits exercices simples à chaque sous-notion
    - Exercices à réaliser

- Etudiants en quasi autonomie durant le TP
    - aide à ceux en difficulté


---

class: middle, center, inverse

Une démonstration ?

# [Lien vers l'application web](https://www.charon.org/sql/index.html) 

---

# Et après ?

### En projet pour l'année prochaine

- Coloration des éléments de la base de données (noms des tables et des champs de celles-ci)

- Utilisation du framework [`bootstrap`]() pour amélioration du design de l'application

### En réflexion pour le futur

- Intégration de l'enseignement des autres parties du langage `SQL` (?)

- Possibilité de création de comptes (?)
    - passage en mode client/serveur
    - peut-être trop complexe à réaliser

---

class: middle, center, inverse

# Merci

## N'hésitez pas à utiliser et à participer éventuellement

### [Projet Github](http://github.com/jncharon/cours-sql)
