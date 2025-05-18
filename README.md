<h1 align="center">🎨 Welcome to Structure-VSCode-SASS 👋</h1>

<p align="center">
  <img alt="Version" src="https://img.shields.io/badge/version-1.0-blue.svg?cacheSeconds=2592000" />
</p>

---

## 📂 Description

🇫🇷 Ce script vous permet de générer une **structure de fichiers et dossiers** pour vos projets Web utilisant **SASS**.

✅ Idéal si vous réalisez plusieurs projets Web et souhaitez partir d’une base propre.  
✅ Des fichiers de base dans les dossiers `Page`, `Layout`, etc. contiennent déjà les directives `@use`.  
✅ Les fichiers principaux `main.scss` et `styles.scss` sont également configurés.  
✅ Une fois le script exécuté, vous pourrez directement **ouvrir le projet dans VSCode** et **compiler avec SASS**.  
✏️ Le script PowerShell peut être modifié pour s’adapter à vos préférences.

---

🇬🇧 This script helps you generate a clean **file and folder structure** for your web projects using **SASS**.

✅ Ideal if you work on multiple web projects and want a clean base.  
✅ Includes `@use` directives in base files like `Page`, `Layout`, etc.  
✅ Both main files `main.scss` and `styles.scss` are preconfigured.  
✅ Once executed, just **open the project in VSCode** and **compile with SASS**.  
✏️ The PowerShell script is customizable to fit your environment.

---

## ⚙️ PowerShell Execution Policy

🇫🇷 Lors du lancement du script, un **message d'avertissement** concernant la stratégie d'exécution Windows peut apparaître :

<p align="center">
  <img alt="Restriction Windows Powershell" src="https://raw.githubusercontent.com/Dev-IT-Seb/Structure-VSCode-SASS/refs/heads/main/Restriction_Powershell.PNG" width="1000" />
</p>

🇬🇧 When launching the script, you might see a **Windows execution policy warning**.

---

## 🧩 Importing into VSCode

🇫🇷 VSCode peut afficher un **avertissement de sécurité** à l’ouverture du dossier. Cliquez sur “Faire confiance à ce dossier”.

<p align="center">
  <img alt="Warning VSCode" src="https://raw.githubusercontent.com/Dev-IT-Seb/Structure-VSCode-SASS/refs/heads/main/Warning_VSCode.PNG" width="700" />
</p>

🇬🇧 VSCode might show a **security warning** when opening the folder. Click "Trust this folder" to continue.

---

## 🛠️ Compile with SASS

🇫🇷 Une fois le script exécuté, installez Node.js et SASS :

1. Installez [**Node.js**](https://nodejs.org/)
2. Puis installez **SASS** via `npm` :

🇬🇧 After running the script, install Node.js and SASS:

1. Install [**Node.js**](https://nodejs.org/)
2. Then install **SASS** using `npm`:

### 🌍 Global install

```bash
npm install -g sass
```

### 📁 Local install (in your project)

```bash
npm install --save-dev sass
```

### ▶️ Compile `styles.scss` to `styles.css`

```bash
sass styles.scss styles.css
```

<p align="center">
  <img alt="Compilation en SASS" src="https://raw.githubusercontent.com/Dev-IT-Seb/Structure-VSCode-SASS/refs/heads/main/Compilation_SASS.png" width="1000" />
</p>

---

## 👤 Author / Auteur

**Sebastien C.**  
🔗 GitHub : [@DevTech-Solutions](https://github.com/DevTech-Solution)

---

## 🌟 Support

🇫🇷 Si ce projet vous a été utile, pensez à **laisser une étoile ⭐** sur le dépôt.  
🇬🇧 If you found this project helpful, consider leaving a **star ⭐** on the repository.

---
