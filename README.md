# NLW11-Ignite
NLW11-Ignite (Setup)

## Server

Create the Project (package.json):
```sh
mkdir server
cd server
npm init -y
```

Create the directories:
```sh
mkdir src
```

Create the server file inside the src directory:
```sh
cd src
touch server.ts
```

Create the Typescript Config file (tsconfig.json):
```sh
npx tsc --init
```

Create the Prisma schema:
```sh
npx prisma init --datasource-provider SQLite
```

Run the Prisma migration:
```sh
npx prisma migrate dev
```

Open the Database with the Prisma Studio:
```sh
npx prisma studio
```

Install the dependencies:
```sh
npm i fastify
npm i @prisma/client
npm i @fastify/cors
```

Install the development dependencies:
```sh
npm i typescript -D
npm i tsx -D
npm i prisma -D
```

Database:
- [Node MySQL 2](https://github.com/sidorares/node-mysql2) - SQL Queries.
- [Knex.js](https://knexjs.org) Query Builder.
- [Prisma](https://www.prisma.io) ORM.

Run the Project:
```sh
npx tsx watch src/server.ts
#or create a dev script and run
npm run dev
```

## Web

Create the project (web):
```sh
npm create vite@latest
```

Install the dependencies:
```sh

```

Install the development dependencies:
```sh
npm i -D tailwindcss postcss autoprefixer
```

Create the Tailwind Config:
```sh
npx tailwind init -p
```

Run the project:
```sh
npm run dev
```

## Mobile

Install the dependencies:
```sh

```

Install the development dependencies:
```sh

```


[Note](https://efficient-sloth-d85.notion.site/Trilha-Ignite-562e3516c7574fb7be75ff01fbb41f54)

[Figma](https://www.figma.com/file/ZKCyXU2folMV0UrRhGLmJn/Habits-(i)?node-id=6%3A343&t=NGUvTP76jRrITo0Y-0)


## VS Code Extensions

- [Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)