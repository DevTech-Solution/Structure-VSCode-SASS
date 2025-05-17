<h1 align="center">📁 Structure VSCode + SASS</h1>

<p align="center">
  <img alt="Version" src="https://img.shields.io/badge/version-1.0-blue.svg?cacheSeconds=2592000" />
  <img alt="Status" src="https://img.shields.io/badge/status-Stable-brightgreen.svg" />
</p>

---

## 🎯 Description

🇫🇷 Ce script PowerShell vous permet de créer automatiquement une **structure de fichiers et dossiers propre** pour vos projets web utilisant **SASS**.  
Il inclut une organisation modulaire (`@use`) dans les fichiers clés : `main.scss`, `styles.scss`, `layout`, `pages`, etc.  
Une fois la structure générée, vous pouvez importer le projet dans **VSCode** et le compiler avec **SASS**.  
> Bien sûr, le script est **modifiable** pour s'adapter à votre propre environnement.

🇬🇧 This PowerShell script auto-generates a clean **folder structure** for your web projects using **SASS**.  
It includes base `@use` directives in key SCSS files (`main.scss`, `styles.scss`, layout, pages, etc.).  
After generation, you can import the project into **VSCode** and compile it using **SASS**.  
> The script is **customizable** for your specific setup.

---

## ⚙️ Prérequis | Requirements

- ✅ VSCode installé  
- ✅ Node.js installé (pour utiliser `sass` via npm)  
- ✅ Powershell autorisé à exécuter des scripts

---

## 💡 Exécution du script

> Lors de la première exécution, Windows peut afficher un **avertissement sur la stratégie d'exécution** :

<p align="center">
  <img alt="Restriction Windows Powershell" src="https://raw.githubusercontent.com/schatel-dev/Structure-VSCode-SASS/refs/heads/main/Restriction_Powershell.PNG" width="1000" />
</p>

🔓 Vous pouvez temporairement autoriser les scripts PowerShell avec :

```powershell
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
