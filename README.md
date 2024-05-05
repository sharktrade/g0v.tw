THIS IS THE OLD ONE

NEW ONE HERE:
https://github.com/g0v/landing-page

# Introduction

[g0v.tw](http://g0v.tw) du contenu web généré par ce projet/的網頁內容由此專案產生

# Directory structure

 * app: programme Web/網頁程式
 * md: article Internet/網頁文章

# Required

- Install nodejs
- Install npm

# Developer
[![devDependency Status](https://david-dm.org/g0v/g0v.tw/dev-status.svg)](https://david-dm.org/g0v/g0v.tw#info=devDependencies)

Veuillez l'exécuter pour la première fois / 第一次請先執行

    $ npm install

Après l'installation, exécutez la commande suivante : / 安裝完之後打以下指令跑起 local web server

    $ npm start

puis dans/然後在 browser entrer/輸入 [http://localhost:3333](http://localhost:3333)

gulp vous aidera automatiquement/會自動幫你 compile jade to html, less to css, fusionner/合併 javascript, css attendez. Lors de la modification d'un fichier, gulp vous aidera également à re-/等。在更改任何一個檔案 gulp 也會幫你重新 compile。

# Deploy

Appelez s'il vous plaît / 請打

    $ ./deploy <git remote>
