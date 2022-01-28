# Webnative React TodoMVC

[![Built by FISSION](https://img.shields.io/badge/⌘-Built_by_FISSION-purple.svg)](https://fission.codes)
[![Built by FISSION](https://img.shields.io/badge/webnative-v0.31.0-purple.svg )](https://github.com/fission-suite/webnative)
[![Discord](https://img.shields.io/discord/478735028319158273.svg)](https://discord.gg/zAQBDEq)
[![Discourse](https://img.shields.io/discourse/https/talk.fission.codes/topics)](https://talk.fission.codes)

The repository implements TodoMVC with React and [webnative](https://github.com/fission-suite/webnative). The repository includes branches that demonstrate the same app configured with Create React App, Vite, Parcel, and Webpack:

- [Create React App build](https://github.com/fission-suite/react-todomvc)
- [Vite build](https://github.com/fission-suite/react-todomvc/tree/vite)
- [Parcel build](https://github.com/fission-suite/react-todomvc/tree/parcel)
- [Webpack build](https://github.com/fission-suite/react-todomvc/tree/webpack)

## Migration to Vite, Parcel, or Webpack

The app was initialized with Create React App and migrated to Vite, Parcel 2, and Webpack 5. See the [Migrate from CRA to Vite](https://github.com/fission-suite/react-todomvc/pull/2), [Migrate from CRA to parcel](https://github.com/fission-suite/react-todomvc/pull/1), and [Migrate from CRA to Webpack](https://github.com/fission-suite/react-todomvc/pull/3) pull requests for guides and diffs to help you migrate from Create React App.

⚠️ Webnative 0.29.0 and newer versions no longer support Create React App. We will re-evaluate when a new version of Create React App is released.
## Try it

The app is live at: https://young-turquoise-metalic-fairy.fission.app/

## Setup

Install dependencies.

```shell
npm install
```

## Develop

To work on the application locally:

```shell
npm start
```

Open the app in your web browser:
- Create React App and Vite: `localhost:3000`
- Parcel: `localhost:1234`
- Webpack: `localhost:8080`

## Build

Build the application.

```shell
npm run build
```

The build will be in `build` for Create React app, `dist` for Vite and Parcel, and `public` for Webpack.

## Publish

You can publish your own version of this app with Fission! [Install the Fission CLI](https://guide.fission.codes/developers/installation) if you haven't already. 

Build the application before the following steps.

Delete `fission.yaml` and then register your own subdomain.

```shell
fission app register
```

The CLI should prompt you with the appropriate build directory depending on which build tool or bundler you used.

Publish the app.

```shell
fission app publish
```

Your version of the app is now live!