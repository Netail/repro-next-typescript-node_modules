# Repro Next Typescript node_modules

1. Have the root directory of your project contain `node_modules` (In this case the default git clone name `repro-next-typescript-node_modules`)
2. Install dependencies; `yarn install`
3. Start the dev server; `yarn dev`
4. Open `localhost:3000` so it compiles the page
5. See errors being thrown in the console regarding not being able to parse tokens. (e.g. `import type` or `: FC`)
