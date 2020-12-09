# create-react-app-typescript-template

![CI/CD](https://github.com/phatnguyenuit/create-react-app-typescript-template/workflows/CI/badge.svg)
[![codecov](https://codecov.io/gh/phatnguyenuit/create-react-app-typescript-template/branch/master/graph/badge.svg?token=4C32ACLQWS)](https://codecov.io/gh/phatnguyenuit/create-react-app-typescript-template)
![License](https://img.shields.io/github/license/phatnguyenuit/create-react-app-typescript-template)

Create React App TypeScript template


## Features

- Inherit from package [`cra-template-typescript`](https://www.npmjs.com/package/cra-template-typescript)
- Configure `eslint` with `prettier`
- Configure [`husky`](https://typicode.github.io/husky/#/)
- Configure [`lint-staged`](https://github.com/okonet/lint-staged#readme)
- Configure [`prettier`](https://prettier.io/)
- Configure [`commitlint`](https://commitlint.js.org/)
- Configure [`release-it`](https://github.com/release-it/release-it)
- Add default `jest` test coverage options
- Configure sample GitHub actions including test, release and deploy
- Provide sample vscode snippets

# Configure

- Update `jest` test coverage options of file [`package.json`](./package.json)
- Add secrets at `https://github.com/:user_name/:repository_name/settings/secrets/actions`
  - Add `CODECOV_TOKEN` got from `https://codecov.io/gh/:user_name/:repository_name/`
  - Add `DEPLOY_ACCESS_TOKEN` got from [`Personal access tokens`](https://github.com/settings/tokens) with the first four `repo` options checked
- Update source for above badges by your own

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

### `yarn commit`

Commit with conventional commit powered by `@commitlint/cli` CLI

### `yarn release`

Release version for your project powered by `release-it` CLI

## Learn More

- You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).
- Learn React, check out the [React documentation](https://reactjs.org/).
- Learn [GitHub Actions](https://docs.github.com/en/free-pro-team@latest/actions/learn-github-actions)
- Learn [ESLint](https://eslint.org/docs/user-guide/getting-started)
- Learn [Commitlint](https://commitlint.js.org/#/)
- Learn [Release-it](https://github.com/release-it/release-it)
- [Setting up a CI/CD workflow on GitHub Actions for a React App (with GitHub Pages and Codecov)](https://dev.to/dyarleniber/setting-up-a-ci-cd-workflow-on-github-actions-for-a-react-app-with-github-pages-and-codecov-4hnp)
