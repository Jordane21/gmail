# IL FAUT TROUVER UN TITRE


## Introduction

Le projet du jour se déroule en 3 étapes. 
1- Création d’un programme va scraper les données de 3 départements, puis les mettre dans un Spreadsheet.
2 - Utiliser ce Spreadsheet nouvellement crée et envoyer un mail à toutes ces adresses e-mails récoltées.
3 - Création d’un bot Twitter qui a pour de chercher les comptes Twitter, les enregistrer dans ce même Spreadsheet et les follow !

## L’arborescence du dossier
Notre dossier Gmail est constitué en 4 grandes parties :

* database
* scrapper
* mailer
* twitter

## Comment se servir du programme et les gems utilisées

Pour faire tourner tous les fichiers, il est nécessaire d'installer plusieurs gems. 
Pour cela, rien de plus simple : une fois le dossier cloné sur l'ordinateur, 
```$ git clone https://github.com/Arak00/gmail.git```
il suffit d'accéder au dossier et de faire 
```$ bundle install```
Et voilà, toutes les gems sont installés !

Liens githubs des pré-requis : 
* [Nokogiri](https://github.com/sparklemotion/nokogiri)
* [Google Drive Ruby](https://github.com/gimite/google-drive-ruby)
* [Gem Gmail](https://github.com/gmailgem/gmail)
* [Dotenv](https://github.com/bkeepers/dotenv)

> :warning: IMPORTANT :warning:  
> N’oubliez pas de configurer votre config.json avec vos tokens pour que les programmes fonctionnent !

## Ce qui a été fait :

- [x] Scraping des données
- [x] Données enregistrées sur notre Spreadsheet
- [ ] Envoi des mails aux mairies
- [ ] Bot Twitter 

## La Team <3 :heart:

** Alex, Aude & Jordane

* Avec l'aide de...
* Visual Studio Code pour Aude & Alex
* Sublime Text pour Jordane

###### Nos Slacks :love_letter:

* Alex : @Alex_C
* Aude : @Aude
* Jordane : @Jordane

