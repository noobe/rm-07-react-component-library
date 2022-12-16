# react-component-lib
A component library for react with storybook to demo it.

## Step by Step
01. Setting up the npm project:
```js
npm init -y
```
Sets up the project with a new `package.json` file.

02. Install React and ReactDOM:
```js
npm i -D react react-dom
```
Since we are creating this using React, we install both react and reactDom packages as dev dependencies using `-D` flag.

03. Install TS and standard types for React types:
```js
npm i -D typescript @types/react
```
Since all modern JS projects are written in TypeScript, we proceed to install that as well as dev dependencies.

04. Create `tsconfig.json` files:
```js
tsc --init
```
This file will hold all the additional config for TypeScript and the TS compiler.

05. Update `tsconfig.json`
```json
"compilerOptions" : {
  "jsx": "react",
  "module": "es6",
  "moduleResolution": "node",
  "outDir": "./dist",
}
```

This configures the TS compiler accordingly.

06. Installing `Storybook`
```js
npx sb init
```

Storybook is an open-source tool for building UI components and pages in isolation. It streamlines UI development, testing, and documentation.

07. Run storybook:
```js
npm run storybook
```
tested