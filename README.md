# sal-cypress-playground

```
npm install cypress --save-dev
npm install typescript --save-dev
npm --init

tsconfig.json
{
  "compilerOptions": {
    "target": "es5",
    "lib": ["es5", "dom"],
    "types": ["cypress", "node"]
  },
  "include": ["**/*.ts"]
}

npx cypress open

npx cypress run
```
