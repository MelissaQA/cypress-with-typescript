# cypress-with-typescript
Cypress tests repository using Typescript language. Steps for creating a basic project from scratch:
1. npm install -y
2. npm install --save-dev cypress
3. npx cypress open
4. npm install --save-dev typescript
5. create cypress/tsconfig.json file and configure it with the code suggested here: https://docs.cypress.io/guides/tooling/typescript-support.html#Configure-tsconfig-json
6. rename js extensions with .ts (command.ts, index.ts on support folder. Also tests on integration folder)
7. from a ts/js file, restart typescript server (on VSCode ctrl+shift+p and type restart)
8. create support/index.d.ts file