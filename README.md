# 42zsh
Quelques variables, alias et fonctions shell utiles pour 42

## Variables

### git

**GIT_NAME**="Pseudo git";

**GIT_EMAIL**="Email git";

### header 42

**MAIL**="$USER@student.42.fr";

## Alias

alias **st**="open /Applications/Sublime\ Text.app"

alias **c**='clear';

alias **..1**="cd ..";

alias **..2**="cd ../..";

alias **..3**="cd ../../..";

alias **..4**="cd ../../../..";

alias **..5**="cd ../../../../..";

alias **now**="date +'%T'";

## Fonctions
### shell

**mkcd** *$1* -> Creer un dossier et rentrer dedans

**renamecurrentdir** *$1* -> Renommer le dossier courant

### git

**setmygitconfig** -> Configure un dossier git avec les idantifiants definis dans les variables de configuration git

**setgitconfig** *$1* *$2* -> Configure un dossier git avec le pseudo et l'email donné

**getgitconfig** -> Affiche la configuration d'un dossier git

### ldap

**getmobile** *$1* -> Affiche le numero de telephone d'un 42 avec un login donné

**getmail** *$1* -> Affiche le mail d'un 42 avec un login donné

**getname** *$1* -> Affiche le nom complet d'un 42 avec un login donné

**getstudent** *$1* -> Affiche les informations d'un 42 avec un login donné

### web

**web** *$1* -> Recherche une page web

**google** *$1* -> Execute une recherche google

**youtube** *$1* -> Execute une recherche youtube
