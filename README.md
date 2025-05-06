<h1 align="center">Welcome to Structure-VSCode-SASS 👋</h1>
<p align="left">
  <img alt="Version" src="https://img.shields.io/badge/version-1.0-blue.svg?cacheSeconds=2592000" />
</p>

> Ce script vous permettra de créer une structure de fichiers/dossiers pour vos projets Web avec SASS.  
> Si vous réalisez plusieurs projets Web et que vous souhaitez une base propre, ce script est pour vous !  
> Les @use sont également présents dans les fichiers de base de certains dossiers (Page, Layout...) et les 2 plus importants, le main.scss et le styles.scss.  
> A la fin du script, vous pourrez importer le dossier de votre projet dans VSCode et le compiler avec SASS.
> Bien entendu, vous pourrez si besoin modifier le script Powershell pour personnaliser votre environnement.

## Strategie d'execution Powershell 
> Au lancement du script, vous pouvez obtenir un message d'avertissement concernant une modification de la stratégie d'execution Windows.
<p align="center">
  <img alt="Restriction Windows Powershell" src="" width="1000" />
</p>  

## Importation dans VSCode  
> Au moment de l'importation de votre projet, VSCode peut vous afficher un avertissement de sécurité.
> Définissez si vous souhaitez faire confiance au dossier de votre projet ou votre dossier Desktop.

<p align="center">
  <img alt="Warning VSCode" src="" width="700" />
</p>  

## Compilation avec SASS  
> Après d'avoir executé le script puis importé votre projet dans VSCode, vous pourrez désormais compiler avec SASS.  
> Bien entendu, vous aurez besoin de node.js.
> Après d'avoir téléchargé et installé node.js, installé les packages NPM en local (dans votre projet) ou global avec un terminal (cmd, Powershell...).  
> Installation en global :
```
npm install -g sass
```
> Installation en local :
```
 npm install --save-dev sass
```
> Après d'avoir compilé votre fichier styles.scss en styles.css, et ayant mis du code dans un fichier SASS (par exemple: Header), cela devrait fonctionner parfaitement pour vous !  
> Pour compiler votre fichier Styles.scss :
```
sass styles.scss styles.css 
```
<p align="center">
  <img alt="Compilation en SASS" src="https://raw.githubusercontent.com/Dev-IT-Seb/Structure-VSCode-SASS/refs/heads/main/Compilation_SASS.png" width="1000" />
</p>

## Author

👤 **Sebastien C.**

***
