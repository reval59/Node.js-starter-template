# NEST Starter Template

Boilerplate Starter Template using Node.js + Express.js + Swagger + Typescripts

## Comments

1. Please add <span style="color:red">**.env**</span> file to .gitignore if your repository is public as it is supposed to contain all confidential configurations including DB passwords or API keys
2. Sample RESTful APIs for [Nasdaq Listings](https://datahub.io/core/nasdaq-listings#resource-nasdaq-listed-symbols) have been implemented for reference
3. The template relies on [Joi](https://github.com/sideway/joi) for data validation, swagger schema & type generation
4. For registering custom path aliases with TypeScript in Node.js for deployment, you may refer to [this link](https://levelup.gitconnected.com/path-aliases-with-typescript-in-node-js-230803e3f200)


## Getting Started

1. npm install
2. npm run start

## Dev Env

1. [ESLint](https://eslint.org/) ([Airbnb](https://github.com/airbnb/javascript) & [Prettier](https://prettier.io/))
2. [Typescript](https://www.typescriptlang.org/)
3. [Swagger](https://swagger.io/)
4. [Node.js](https://nodejs.org/en/)
5. [Nodemon](https://github.com/remy/nodemon)

## VS Code Dev Env Config

1. Install ESLint & Prettier Plugin
2. Add the below contents in settings.json

```json
  "typescript.updateImportsOnFileMove.enabled": "prompt",
  "javascript.updateImportsOnFileMove.enabled": "prompt",
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.tabSize": 2
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.tabSize": 2
  },
  "[json]": {
    "editor.tabSize": 2
  },
  "editor.formatOnSave": false,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  },
```
