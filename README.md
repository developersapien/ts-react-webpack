# React Typescript Webpack

Our project will work with **REACT** **TYPESCRIPT** and **WEBPACK**
[Example Webpack](https://www.carlrippon.com/creating-react-and-typescript-apps-with-webpack/)
[example 2](https://www.carlrippon.com/creating-react-app-with-typescript-eslint-with-webpack5/)

## Dependencies

- react
- react-dom

## DevDependecies

- @types/react
- @types/react-dom
- @types/node
- @types/jest
- @types/webpack
- @types/webpack-dev-server
- awesome-typescript-loader
- css-loader
- html-webpack-plugin
- mini-css-extract-plugin
- source-map-loader
- typescript
- webpack
- webpack-cli
- webpack-dev-server
- babel-loader
- @babel/core
- @babel/preset-env
- @babel/preset-react
- @babel/preset-typescript
- @babel/plugin-transform-runtime
- @babel/runtime
<!-- Linter Packages -->
- "eslint": "^7.21.0",
- "eslint-config-hueriyet": "^1.0.5",
<!-- Webpack type checking -->
- fork-ts-checker-webpack-plugin
- @types/fork-ts-checker-webpack-plugin

## Typescript Config File

- `lib`: The standard typing to be included in the type checking process. In our case, we have chosen to use the types for the browsers DOM as well as the latest version of ECMAScript.

- `allowJs`: Whether to allow JavaScript files to be compiled.

- `allowSyntheticDefaultImports` : This allows default imports from modules with no default export in the type checking process.

- `skipLibCheck`: Whether to skip type checking of all the type declaration files (\*.d.ts).

- `esModuleInterop`: This enables compatibility with Babel.

- `strict`: This sets the level of type checking to very high. When this is true, the project is said to be running in strict mode.

- `forceConsistentCasingInFileNames`: Ensures that the casing of referenced file names is consistent during the type checking process.

- `moduleResolution `: How module dependencies get resolved, which is node for our project.

- `resolveJsonModule`: This allows modules to be in .json files which are useful for configuration files.

- `noEmit`: Whether to suppress TypeScript generating code during the compilation process. This is true in our project because Babel will be generating the JavaScript code.

- `jsx`: Whether to support JSX in .tsx files.

- `include`: These are the files and folders for TypeScript to check. In our project, we have specified all the files in the src folder.
