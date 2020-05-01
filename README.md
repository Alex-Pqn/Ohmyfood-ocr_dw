# project3ocr

* Presentation

Name of the project : project3ocr (Project 3, OpenClassrooms)

Author : Alex Pqn

Project status : active (in devlopment)

Projet start date : 16 April 2020

Projet end date : undefined

Quick Description : Project designed and intended to reproduce the models of a site for preparing and assembling food menus.



* Installation of the project

to install "sass".
> npm install sass

- -
The site must be fully compatible with the latest desktop versions of Chrome, Firefox and Safari.
Two possibilities to interact with the project prefixes !

1. You will need to install an automatic prefix extension (the default script "prefix" in the package.json is suitable for the extension "autoprefixer" in Visual Studio Code). 
You can customize this script if you use another extension in your I.D.E.

2. If you don't want to use an autoprefixer, please add them manually in a separate .scss file and import it into "scss.main". 
If you choose the manual method you can remove the "prefix" script and ignore the rest of the installation, just type "npm run sass" to start the sass script.
- -

to install "concurrently" (program script to launch scripts "sass" and "prefix" at the same time, possibility to take another).
> npm install concurrently

to run the two scripts with "concurrently" (another command if you have another script for make this)
> concurrently "npm run sass" "npm run prefix"
