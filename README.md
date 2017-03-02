# Configurations
Ce dépot permet de configurer cygwin (git bash) pour windows
### Pré-requis
* Avoir node / npm d'installer
* Installer git pour windows

### Dependance
1. git Credential
[Depot git](https://github.com/Microsoft/Git-Credential-Manager-for-Windows/releases) pour récupérer l'installeur
2. [Installer meld](http://meldmerge.org/) pour gérer les conflits

## Installation
1. Il faut cloner le répertoire 
```$ git clone https://github.com/LouisLaval/Configurations```
2. Copier tous les fichiers du dépot dans le dossier d'utilisateur /!\ Ceci remplacera toutes vos précédente configuration Git 
```$ cp .* /c/Users/NomUtilisateur```
3. Parametrer l'utilisateur par défaut de git
```$ git config --global user.name "John DOE"```
```$ git config --global user.email "John DOE"```

