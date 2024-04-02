# Portafolio Personal en ReactJS

Esta simple app usando ReactJS esta destinada a ser el objeto de pruebas para aws

 # Antes de usar asegura de instalar:
 # Dependencias 
 nvm 
 ```
 https://github.com/coreybutler/nvm-windows/releases/tag/1.1.12
 ```
 nodejs v20.12.0
 ```
 nvm install 20.12.0
 ```
 pnpm en PowerShell
 ```
iwr https://get.pnpm.io/install.ps1 -useb | iex
 ```
 Husky
 ```
 pnpm install husky -D
 ```

 # Para ejecutar: 
 ```
 pnpm run start
 ```
 # Talvez sea importante mencionar:
 # Husky
Hook interceptar llamadas a fucniones con el fin de alterar o reaccionar su comportamiento
En este proyecto se usa:
Pre-commit hook ejecutar instruciones antes incluso de un commit message
Importante puedes hacer un bypass con:
```
git commit --no-verify
```
-instalar:
```
pnpm install husky -D // D->(-save-dev)
```
instalacion local preferentemente
-activar:
```
npx husky install
```
-agregar script:
```
npm pkg set scripts.prepare="husky install"
```

-para crear hooks se crean dentro de la dir .husky
pero fuera del dir _(root)
con el nombre del hook "pre-commit"


# LINT
Se usa lint
-instalar:
```
pnpm install -g eslint
```
-inicialzar:
```
eslint --init
```
En formateador usado es personalizado para JavaScript Modules con Ract con 'Popular Style'
con Standard para pnpm


 # Licencia
 MIT




 


