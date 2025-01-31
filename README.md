# Create React SSR App

Create React apps with server side rendering and no build configuration. Inspired by the famous [create-react-app](https://facebook.github.io/create-react-app/), Create React SSR App does the same thing for React apps that require server side rendering.

- [Creating an App](#creating-an-app) – How to create a new app.
- [User Guide](https://trustworktech.github.io/create-react-ssr-app/) – How to develop apps bootstrapped with Create React SSR App.

Create React SSR App works on macOS, Windows, and Linux.<br>
If something doesn’t work, please [file an issue](https://github.com/trustworktech/create-react-ssr-app/issues/new).

## Quick Overview

```sh
npx create-react-ssr-app my-app
cd my-app
yarn start
```

Then open [http://localhost:3000/](http://localhost:3000/) to see your app.<br>
When you’re ready to deploy to production, create a minified bundle with `yarn build`.

### Get Started Immediately

You **don’t** need to install or configure tools like Node, Webpack or Babel.<br>
They are preconfigured and hidden so that you can focus on the code.

Just create a project, and you’re good to go.

## Creating an App

**You’ll need to have Node 8.10.0 or later on your local development machine** (but it’s not required on the server). You can use [nvm](https://github.com/creationix/nvm#installation) (macOS/Linux) or [nvm-windows](https://github.com/coreybutler/nvm-windows#node-version-manager-nvm-for-windows) to easily switch Node versions between different projects.

To create a new app, you may choose one of the following methods:

### npx

```sh
npx create-react-ssr-app my-app
```

### npm

```sh
npm init react-ssr-app my-app
```

_`npm init <initializer>` is available in npm 6+_

### Yarn

```sh
yarn create react-ssr-app my-app
```

_`yarn create` is available in Yarn 0.25+_

It will create a directory called `my-app` inside the current folder.<br>
Inside that directory, it will generate the initial project structure and install the transitive dependencies:

```
my-app
├── README.md
├── node_modules
├── package.json
├── .gitignore
├── public
│   ├── app.html
│   ├── favicon.ico
│   └── manifest.json
└── src
    ├── client
    |   ├── index.css
    │   └── index.js
    ├── server
    |   ├── middleware
    |   |   ├── html.js
    |   |   └── render.js
    │   └── index.js
    ├── App.css
    ├── App.js
    ├── App.test.js
    ├── index.js
    └── logo.svg
```

No configuration or complicated folder structures, just the files you need to build your app.<br>
Once the installation is done, you can open your project folder:

```sh
cd my-app
```

Inside the newly created project, you can run some built-in commands:

### `npm start` or `yarn start`

Runs the app in the development mode. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits. You will also see any lint errors in the console.

### `npm test` or `yarn test`

Runs the test watcher in an interactive mode.<br>
By default, runs tests related to files changed since the last commit.

[Read more about testing.](https://trustworktech.github.io/create-react-ssr-app/docs/running-tests)

### `npm run build` or `yarn build`

Builds the app for production to the `build` folder. It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes. Your app is ready to be deployed!

## User Guide

You can find detailed instructions on using Create React SSR App and many tips in [its documentation](https://trustworktech.github.io/create-react-ssr-app/).

## How to Update to New Versions?

Please refer to the [User Guide](https://trustworktech.github.io/create-react-ssr-app/docs/updating-to-new-releases) for this and other information.

## Contributing

We'd love to have your helping hand on `create-react-ssr-app`! See [CONTRIBUTING.md](CONTRIBUTING.md) for more information on what we're looking for and how to get started.

## License

Create React SSR App is open source software [licensed as MIT](https://github.com/trustworktech/create-react-ssr-app/blob/master/LICENSE).
