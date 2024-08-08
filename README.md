# 2024-IA22-2TRI

**Iniciando um projeto Node.js com TypeScript**

Abra o seu github, crie um repositorio feito isso abra o codespaces. Abra o terminal e escreva o código abaixo.

npm init -y

npm install express cors sqlite3 sqlite

npm install --save-dev typescript nodemon ts-node @types/express @types/cors

npx tsc --init

mkdir src

touch src/app.ts

Escreva um de cada vez. Se de certo aparecera isso.

**Configuranado o tsconfig.json**

Va no tsconfig.json procure /* Emit */ e altere as linhas "//outDir": "./", para "outDir": "./dist", e adicione a linha "//rootDir": "./src", o ficara desta maneira.

##**Configurando o package.json**##

Va no package.json e adicione a seguinte linha.

 "dev": "npx nodemon src/app.ts"

 o código ficara da seguinte maneira.

 
