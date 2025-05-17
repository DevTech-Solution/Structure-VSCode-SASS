<h1 align="center">🎨 Welcome to Structure-VSCode-SASS 👋</h1>

<p align="center">
  <img alt="Version" src="https://img.shields.io/badge/version-1.0-blue.svg?cacheSeconds=2592000" />
</p>

---

## 📂 Description

Ce script vous permet de générer une **structure de fichiers et dossiers** pour vos projets Web utilisant **SASS**.

✅ Idéal si vous réalisez plusieurs projets Web et souhaitez partir d’une base propre.  
✅ Des fichiers de base dans les dossiers `Page`, `Layout`, etc. contiennent déjà les directives `@use`.  
✅ Les fichiers principaux `main.scss` et `styles.scss` sont également configurés.  
✅ Une fois le script exécuté, vous pourrez directement **ouvrir le projet dans VSCode** et **compiler avec SASS**.  
✏️ Le script PowerShell peut être modifié pour s’adapter à vos préférences.

---

## ⚙️ Stratégie d'exécution PowerShell

> Lors du lancement du script, un **message d'avertissement** lié à la stratégie d'exécution de Windows peut apparaître :

<p align="center">
  <img alt="Restriction Windows Powershell" src="https://raw.githubusercontent.com/Dev-IT-Seb/Structure-VSCode-SASS/refs/heads/main/Restriction_Powershell.PNG" width="1000" />
</p>

---

## 🧩 Importation dans VSCode

> Lors de l'ouverture du dossier dans **Visual Studio Code**, un **avertissement de sécurité** peut s’afficher.  
> Cliquez simplement sur **"Faire confiance à ce dossier"** (project folder ou Desktop selon votre choix) :

<p align="center">
  <img alt="Warning VSCode" src="https://raw.githubusercontent.com/Dev-IT-Seb/Structure-VSCode-SASS/refs/heads/main/Warning_VSCode.PNG" width="700" />
</p>

---

## 🛠️ Compilation avec SASS

Une fois le script exécuté et le projet ouvert dans VSCode :

1. Installez [**Node.js**](https://nodejs.org/)
2. Puis installez **SASS** avec `npm` :

### 🔧 Installation globale

```bash
npm install -g sass
