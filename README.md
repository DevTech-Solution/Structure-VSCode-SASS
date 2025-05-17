<h1 align="center">📁 Structure VSCode + SASS</h1>

<p align="center">
  <img alt="Version" src="https://img.shields.io/badge/version-1.0-blue.svg?cacheSeconds=2592000" />
  <img alt="Status" src="https://img.shields.io/badge/status-Stable-brightgreen.svg" />
</p>

---

## 🎯 Description

🇫🇷 Ce script PowerShell vous permet de créer automatiquement une **structure de fichiers/dossiers** pour vos projets web utilisant **SASS**.  
Il inclut l'organisation avec `@use` dans les fichiers principaux (`main.scss`, `styles.scss`, `layout`, `pages`...).

> Une fois la structure créée, vous pourrez importer votre dossier dans **VSCode** et compiler avec **SASS**.  
> Le script est personnalisable pour s’adapter à votre environnement.

🇬🇧 This PowerShell script generates a clean **folder structure** for your SASS-based web projects.  
It includes `@use` structure in key files like `main.scss`, `styles.scss`, `layout`, `pages`...

> Once generated, you can import the folder into **VSCode** and compile with **SASS**.  
> The script can be customized for your workflow.

---

## ⚙️ Stratégie d'exécution PowerShell

> Lors du lancement du script, Windows peut afficher un **message d'avertissement** sur la stratégie d'exécution PowerShell :

<p align="center">
  <img alt="Restriction Windows Powershell" src="https://raw.githubusercontent.com/schatel-dev/Structure-VSCode-SASS/refs/heads/main/Restriction_Powershell.PNG" width="1000" />
</p>

💡 Pour contourner ce message temporairement :

```powershell
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
