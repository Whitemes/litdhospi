# web-presentation

Project is designed to quickly build presentation as a web page.

url : https://whitemes.github.io/litdhospi/

**Setup**
- Jekyll est écrit en Ruby donc il faudra installer le langage ainsi que RubyGems qui est un gestionnaire de package (un peu comme npm mais pour ruby) pour installer Jekyll.
- Installer Jekyll : https://jekyllrb.com/docs/installation/
- Cloner le projet puis `jekyll serve` pour lancer en local sur le port 4000
- Pour modifier les slides (les markdowns) ce sera dans le dossier `_posts`

**IMPORTANT**
* Les noms de fichiers doivent commencer par un format **année-mois-jour valide** (par exemple : `1000-01-01-example.md`).
* Les **années** seront affichées **horizontalement**.
* Les **mois** seront affichés sous forme de **navigation verticale** pour une année donnée.
* Les **pages de présentation** seront affichées **dans l’ordre chronologique**.
* **GitHub Pages** générera/mettra à jour automatiquement le site web avec la présentation (merci d’attendre **1 minute** le temps que ça publish).
