To make this working first create a folder in your system named TODO
then in it create 2 folders:
1.Server(For Frontend)
2.todolist(For Backend)

when you get this repository cloned it will not have this folder structure please ensure to arrange files as follows:

1.Server
  -Models
  -node_modules
  -public
  -src
  -.eslintrc.cjs
  -.gitignore
  -index.html
  -index.js
  -package-lock.json
  -package.json
  -README.md
  -vite.config.js
2.todolist
  -node_modules
  -public
  -src
  -.eslintrc.cjs
  -.gitignore
  -index.html
  -package-lock.json
  -package.json
  -README.md
  -vite.config.js

Change the mongodb link on line 9 of index.js file to connect database to your mongodb compass

  
