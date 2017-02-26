# Editeur de pseudocode

## Description
Ce projet a pour objectif de créer un logiciel d'édition de pseudocode.  
Le pseudocode est un langage non normalisé qui permet de décrire des algorithmes indépendamment de tout langage de programmation.


_Exemple de pseudocode :_


![Un premier exemple de pseudocode]( https://github.com/jerome-9132/VisualStudioCodeTestConnect/blob/master/Documentation/Pictures/ExampleOfPseudoCode01Re.png?raw=true )


![Un deuxième exemple de pseudocode]( https://github.com/jerome-9132/VisualStudioCodeTestConnect/blob/master/Documentation/Pictures/ExampleOfPseudoCode02.png?raw=true )

Les technologies utilisées dans le cadre de ce projet sont le JavaScript (Ecma 6), l'HTML/CSS et Github's Electron.

***

## Comment essayer le projet ?

### Prérequis :
Il vous faut connaître les commandes de bases des shells Linux ou du powershell Windows
(cd, ls, ...)

### 1. Installer git
* Windows : chercher l'installateur sur internet
* Linux (Debian/Ubuntu/Mint) : `sudo apt-get install git-all`

### 2. Cloner le repository sur votre machine : 
`git clone https://github.com/jerome-9132/GraduationWork.git`  
Un tutoriel est disponible à cette adresse : https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository
 
### 3. Installer node.js :
* Windows : chercher l'installateur sur internet
* Linux (Debian/Ubuntu/Mint) : `sudo apt install nodejs-legacy`

### 4. Ouvrir une console/terminal et aller jusqu'à la racine du clone du repository.
Vous avez défini la localisation de la racine du repository _**au point 2**_.  
Sur windows utiliser Powershell plutôt que le prompt.

### 5. Installer electron via npm (node.js) :
Dans la console/terminal _**(ouverte au point 4)**_ taper au choix :
* (Pour installer en tant que dependance du projet) `npm install electron --save-dev`  
 	OU
* (Pour installer globalement sur la machine - ajouter au path) `sudo npm install electron -g`

### 6. Installer les modules nécessaires au programme :
Dans la console/terminal _**(ouverte au point 4)**_ taper  `npm install`

### 7. Lancer l'application :
Dans la console/terminal _**(ouverte au point 4)**_ taper  `npm start`
