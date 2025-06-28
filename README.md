# Dyma_html_CSS

base html et css

Pour modifier le navigateur du live server, il faut modifier le settings.json du vscode en allant dans les paramatrès et ajouter le navigateur par défaut que vous vouler :  
exemple :

```json
 "liveServer.settings.donotShowInfoMsg": true,
  "liveServer.settings.CustomBrowser": "microsoft-edge",
```

---

# Installation SASS

1. Installation de Node.js(pour npm)
2. Installation de Node-sass(grâce à npm)
3. Création d'un petit script pour transformer le Sass en CSS au fur et
   à mesur(grâce à npm)

4. Installer Git si c'est pas fait
5. faire dans visual Studio Code "CTRL+SHIFT+P", une invite de commande s'ouvre : taper "select default Shell" et là, choisir "Git Bash".
6. on ferme le terminal puis le réouvre
7. Comandes differentes

```bash
mkdir test // cree un fichier test
cd  // permet de naviguer dans les dossier
ls // liste les dossiers presents
touch monfichier.html  // cree un fichier

```

8. Installations de nodeJs sur Windows  
   prendre une version LTS

```bash
https://nodejs.org/fr/download
```

8. Initiatialisation de sass

```bash
npm init -y
npm i // install toute la librairie de npm.json
npm i sass //installation de sass

```

9. Mettre un script dans package.json

```bash
{
  "name": "dyma_html_css",
  "version": "1.0.0",
  "description": "base html et css",
  "main": "index.js",
  "scripts": {
    "sass": "sass -w scss:css" //  sur cette ligne
  },
  "keywords": [],
  "author": "",
  "license": "ISC",
  "dependencies": {
    "sass": "^1.89.2"
  }
}

```

10. Commande de lancement terminal

```bash
npm run sass
```

si tu as ça dans ton terminal c'est que tout vas bien

```bash
> sass@1.0.0 sass
> sass -w scss:css

Sass is watching for changes. Press Ctrl-C to stop.
```
