# Packages

Explanations for why they exist in this project. (Ignoring @types/\* since they are just type definitions for the corresponding library)

### Dependencies

- **[body-parser](https://github.com/expressjs/body-parser):** express middleware that parses `req.body` into a trustable JSON before getting to the controllers.
- **[compression](https://github.com/expressjs/compression):** express middleware that compresses response bodies for all requests.
- **[cors](https://github.com/expressjs/cors):** express middleware that adds CORS control on requests and responses, allowing developers to restrict origins, types, and etc. of all the calls coming in and out.
- **[dotenv](https://github.com/motdotla/dotenv):** a library that puts all config variables defined in `.env` file into `process.env`.
- **[express](https://expressjs.com/):** popular node.js server framework.
- **[morgan](https://github.com/expressjs/morgan):** express middleware that logs the status for all requests.
- **[winston](https://github.com/winstonjs/winston):** popular logging library that is highly customizable.

### Dev Dependencies

- **[@semantic-release/commit-analyzer](https://github.com/semantic-release/commit-analyzer):** semantic-release plugin that analyzes commit messages to determine if a version bump is required.
- **[@semantic-release/git](https://github.com/semantic-release/git):** semantic-release plugin that pushes git version tags and files that are generated for release to git remote.
- **[@semantic-release/npm](https://github.com/semantic-release/npm):** semantic-release plugin that updates the package.json version and publish package to npm (optional, so disabled for this starter).
- **[@semantic-release/release-notes-generator](https://github.com/semantic-release/release-notes-generator):** semantic-release plugin that generates release notes based on commit messages.
- **[conventional-changelog-express](https://github.com/conventional-changelog/conventional-changelog/tree/master/packages/conventional-changelog-express):** a library that multiple semantic-release plugins rely on.
- **[husky](https://github.com/typicode/husky):** git hooks configuration to call scripts before commit, push, and more.
- **[jest](https://jestjs.io):** popular testing framework.
- **[lint-staged](https://github.com/okonet/lint-staged):** run linter to format staged files in git, used with husky to lint staged files before a commit.
- **[nodemon](https://nodemon.io/):** listens to file saves and live reloads server during development.
- **[prettier](https://prettier.io/):** code formatter that makes code more readable.
- **[semantic-release](https://github.com/semantic-release/semantic-release):** automatic release version management, the documentation for the workflow of the setup for this starter is available [here](https://github.com/thousight/express-ts-starter/docs/semantic-release-workflow.md).
- **[ts-jest](https://github.com/kulshekhar/ts-jest):** TypeScript preprocessor for Jest.
- **[ts-node](https://github.com/TypeStrong/ts-node):** node.js that works with TypeScript so that no need to do `tsc` on every file save during development.
- **[tslint](https://palantir.github.io/tslint/):** TypeScript linter.
- **[tslint-config-prettier](https://github.com/prettier/tslint-config-prettier):** TSLint plugin that works with Prettier to remove conflicts.
- **[typescript](https://www.typescriptlang.org/):** A JavaScript that enforces typing.

### Other Recommended Libraries

These libraries are not in this repo but they are some go-tos for certain functionalities.

- **[apollo server](https://www.apollographql.com/docs/apollo-server/):** popular GraphQL server framework.
- **[artillery](https://artillery.io/):** load testing framework that allows developers to customize load test scenarios.
- **[async](https://github.com/caolan/async):** JavaScript promise utils library.
- **[axios](https://github.com/axios/axios):** http client for both browser and node.js.
- **[jsonwebtoken](https://github.com/auth0/node-jsonwebtoken):** library that creates/verifies jwts.
- **[knex](https://knexjs.org/):** SQL query builder.
- **[lodash](https://lodash.com/):** popular object/array/etc. utility library.
- **[moment](https://momentjs.com):** popular date time utility library.
- **[mongoose](https://mongoosejs.com/):** mongoDB node.js library.
- **[nodemailer](https://nodemailer.com/about/):** email cilent for node.js.
- **[node-postgres](https://node-postgres.com/):** PostGres client for node.js.
- **[node_redis](https://github.com/NodeRedis/node_redis):** node.js client for Redis, which helps cache content to boost response time.
- **[passport](http://www.passportjs.org/):** authentication middleware that supports 300+ kinds of log in methods, including traditional username/password, Facebook, Google, OAuth, SAML, etc.
- **[rabbitMQ](https://www.rabbitmq.com/):** message broker which queues heavy duties, such as sending email and generating PDFs.
