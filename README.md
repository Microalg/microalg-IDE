# Design de l’IDE de microalg

## Installation
0. Récuperer le projet : `git clone…`;
1. Ce projet utilise node qu’il faut installer : https://www.npmjs.org.
2. Avec Node s’installe NPM, le gestionnaire de dépendance de Node;
3. Dans un terminal : `npm install` dans le dossier du projet, là ou se trouve le fichier _package.json_;

Les dépendances du projet doivent être installées après une série de messages pour la plupart cryptiques.

## Commencer à développer

Dans le dossier du projet : `npm start`, les messages doivent défiler dans votre console jusqu’à ce que votre navigateur ouvre directement la page principale du projet.

## Distribuer et mettre à disposition en ligne

Seul le dossier _dist_ est à copier, distribuer, versioner… sur le serveur de destination. Si le projet est censé être à la _racine_ du serveur il suffit de copier l’ensemble des fichiers et dossiers qu’il comprend et de les copier au bon endroit.
