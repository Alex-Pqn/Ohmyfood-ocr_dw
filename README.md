## Dynamisez une page web avec des animations CSS
### P3 - OpenClassrooms "Développeur Web"
#### Projet conçu et destiné à reproduire les modèles d'un site de préparation et d'assemblage de menus alimentaires.
- Transformer une maquette en site web HTML5 & CSS3
- Création d'un environnement Front-End
- Architecture des dossiers et fichiers respectée
- Utilisation de Sass et préfixage du CSS
- Mise en œuvre des effets CSS graphiques avancés
- Mise en place d'une structure de navigation
- Code passé dans le validateur W3C
- Responsive

### Installation

The installation uses npm Node.js. Install it on your I.D.E to take advantage of the "npm" commands in your terminal.

to install "sass".
> npm install sass

- - -
The site must be fully compatible with the latest desktop versions of Chrome, Firefox and Safari.

Two possibilities to interact with the project prefixes !

1. Install an automatic prefixer extension (the default script "prefix" in the package.json is suitable for the extension "autoprefixer" in Visual Studio Code).
You can customize this script if you use another extension in your I.D.E.
Once the script "prefix" customized according to your extension, you can skip step 2 and continue the installation.

2. If you don't want to use an autoprefixer, please add them manually in file at "sass/utils/_prefixes.scss" (create it yourself) and import "_prefixes.scss" into "scss.main" with the syntax already used.
If you choose this method, you can remove the "prefix" script and ignore the rest of the installation, just type "npm run sass" to start the sass script.
- - -

to install "concurrently" (program script to launch scripts "sass" and "prefix" at the same time, possibility to take another).
> npm install concurrently

to run the two scripts with "concurrently" (another command if you have another program script for make this)
> concurrently "npm run sass" "npm run prefix"
