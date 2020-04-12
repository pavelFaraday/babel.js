# babel.js
## Commands for installing babel in your local machine


-----------------------------------------------
1) Commands in Command Promt:

> cd C:\Users\user\Desktop\babel
npm init --yes
npm install -D @babel/core @babel/cli
npm install @babel/polyfill
-----------------------------------------------
2) create .babelrc file in C:\Users\user\Desktop\babel
-----------------------------------------------
3) write in .babelrc file:
> {
   > "presets": [ "@babel/preset-env" ]
> }
-----------------------------------------------
4) create folder with name:  src
5) create in src folder new file: index.js
-----------------------------------------------
6) create folder with name:  dist
---------------------------------------------
7) Command in Command Promt:

> npm i -D @babel/preset-env
---------------------------------------------
8) Command in Command Promt:
(You will often use this command for compilation)

> npm run babel
---------------------------------------------

and if everything is well: 
"Successfully compiled 1 file with Babel."