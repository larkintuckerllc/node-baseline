# Express-TS-Starter

A minimal express server starter with TypeScript

### Pre-Requisites

1. Make sure you have [node.js](https://nodejs.org/en/) installed locally

2. Once you have node.js installed, add yarn to your global local directories with this command in terminal:

```
npm i -g yarn
```

### Demonstration

1. After you cloned this repo down to your local machine, start with installing dependencies by:

```
yarn install
```

2. To start developing locally, use the command below:

```
yarn start:dev
```

### Getting Started

1. In a new folder, initialize a GIT repository with:

```
git init
```

2. In a new folder, intialize a Node.js project with (accepting all defaults):

```
npm init
```

3. Update _package.json_ by:

- Supplying a _description_ value
- Replacing _main_ key with _private_ with the value _true_
- Supplying a _author_ value _Appirio Digital_
- Removing the _licence_ key

4. Install devDependencies with:

```
yarn add @types/jest --dev
yarn add husky --dev
yarn add jest --dev
yarn add lint-staged --dev
yarn add nodemon --dev
yarn add prettier --dev
yarn add ts-jest --dev
yarn add ts-node --dev
yarn add tslint --dev
yarn add tslint-config-prettier --dev
yarn add tslint-plugin-prettier --dev
yarn add typescript --dev
```

and the number of dependencies for semantic-release with:

```
yarn add @semantic-release/commit-analyzer --dev
yarn add @semantic-release/git --dev
yarn add @semantic-release/npm --dev
yarn add @semantic-release/release-notes-generator --dev
yarn add conventional-changelog-express --dev
yarn add semantic-release --dev
```

5. Create the TypeScript configuration file; [tsconfig.json](https://github.com/appirio-digital/ads-node-baseline/blob/master/tsconfig.json)

6. Create the TSLint configuration file; [tslint.json](https://github.com/appirio-digital/ads-node-baseline/blob/master/tslint.json)

7. Create the Prettier configuration file; [.prettierrc](https://github.com/appirio-digital/ads-node-baseline/blob/master/.prettierrc)

8. Create the lint-staged configuration file; [.lintstagedrc](https://github.com/appirio-digital/ads-node-baseline/blob/master/.lintstagedrc)

9. Create the husky configuration file; [.huskyrc](https://github.com/appirio-digital/ads-node-baseline/blob/master/.huskyrc)

10. Create the nodemon configuration file; [nodemon.json](https://github.com/appirio-digital/ads-node-baseline/blob/master/nodemon.json)

11. Create Jest configuration file; [jest.config.js](https://github.com/appirio-digital/ads-node-baseline/blob/master/jest.config.js)

12. Create GIT ignore file; [.gitignore](https://github.com/appirio-digital/ads-node-baseline/blob/master/.gitignore)

13. Create a `scripts` folder and create the [described](https://github.com/appirio-digital/ads-node-baseline/tree/master/scripts) files in it

14. Copy the `scripts` section of [package.json](https://github.com/appirio-digital/ads-node-baseline/blob/master/package.json) into the projects `package.json`

15. Create Semantic Release configuration file; [.releaserc](https://github.com/appirio-digital/ads-node-baseline/blob/master/.releaserc)

16. Install the dependencies:

```
yarn add @types/compression
yarn add @types/cors
yarn add @types/dotenv
yarn add @types/express
yarn add @types/morgan
yarn add @types/winston
yarn add body-parser
yarn add compression
yarn add cors
yarn add dotenv
yarn add express
yarn add morgan
yarn add winston
```

17. Create Source Files

- [server.ts](https://github.com/appirio-digital/ads-node-baseline/blob/master/server.ts)
- [src/app.ts](https://github.com/appirio-digital/ads-node-baseline/blob/master/src/app.ts)
- [src/utils/logger/index.ts](https://github.com/appirio-digital/ads-node-baseline/blob/master/src/utils/logger/index.ts)
- [src/utils/logger/index.test.ts](https://github.com/appirio-digital/ads-node-baseline/blob/master/src/utils/logger/index.test.ts)

### Continuous Integration

TODO

### Useful Commands

- **`yarn build`** creates a production build of the server code in the build folder, which is ignored by git, in the project root.

- **`yarn start`** runs the production build in build folder, will error out if the build folder doesn't exist.

- **`yarn start:dev`** runs the development server and will live reload the server on ts file saves.

- **`yarn clean`** removes yarn caches and output folders, then re-installs node_modules.

- **`yarn clean:dev`** does the job of `yarn clean` but starts development server immediately after.

- **`yarn test`** runs a jest unit test.

- **`yarn test:watch`** runs jest in watch mode.

- **`yarn test:ci`** runs jest in CI mode, most likely gets called in the CI scripts.

- **`yarn test:coverage`** runs jest and has it return coverage report, then opens the generated coverage report html on the browser.

- **`yarn tslint`** runs the linter on all typescript code.

- **`yarn lint-staged`** runs the linter on all staged files in git, this command is most likely called by husky before creating a git commit.

- **`yarn semantic-release`** runs the semantic-release package to bump package.json version and create git release tag. This is most likely called by Travis CI, but can be ran locally to do a dry-run without actually publishing a release.

### Additional Documentation

- [Semantic Release Workflow](https://github.com/appirio-digital/ads-node-baseline/blob/master/docs/semantic-release-workflow.md)

- [Packages](https://github.com/appirio-digital/ads-node-baseline/blob/master/docs/packages.md)

- [Scripts](https://github.com/appirio-digital/ads-node-baseline/blob/master/scripts/README.md)
