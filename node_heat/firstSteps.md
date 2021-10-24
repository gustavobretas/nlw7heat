#Comandos Iniciais

yarn init -y

#Pacotes Necessário para o Desenvolvimento do Projeto

#Dependencia em modo de Produção

yarn add express
yarn add dotenv
yarn add axios
yarn add jsonwebtoken

#Dependencia em modo de Desenvolvimento

yarn add -D @types/express typescript ts-node-dev
yarn add prisma -D
yarn add @types/axios -D
yarn add @types/jsonwebtoken -D

ts-node-dev serve para fazer refresh do projeto em desenvolvimento

#Inciar o TypeScript

yarn tsc --init

git init

#Alteração do tsconfig.json
"target": "es2017"
"strict": false

#Adicionar o Prisma.io
https://www.prisma.io/docs/getting-started/setup-prisma/add-to-existing-project
