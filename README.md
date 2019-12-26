# Richard Towers' Design System

A fork of the GOV.UK Design system for my personal projects

## Run locally

You'll need [Git](https://help.github.com/articles/set-up-git/) and [Node.js](https://nodejs.org/en/) installed to get this project running.

Note: You will need the [active LTS (Long-term support)](https://github.com/nodejs/Release#release-schedule) Node.js version for this project (as specified in [.nvmrc](./.nvmrc))

### Install npm dependencies
```
npm install
```

### Start a local server
This will build sources, serve pages and watch for changes.
```
npm start
```

## Build
Build `./src` to `./deploy/public`
```
npm run build
```

## Run the Sass linter

We are using the [sass-lint][sass-lint] plugin to lint the Sass files in
`source/stylesheets`. You can run the linter from command line by running:

```
npm run lint
```

[sass-lint]: https://github.com/juanfran/gulp-scss-lint

## GOV.UK Frontend packages

Design System consumes the [Richard Towers Frontend](https://github.com/richardtowers/richardtowers-frontend) package via git.
This is defined in the [package.json](package.json) file.

## Deployment

- [How the Design System is deployed to production](docs/deployment/production.md)
- [How branch and PR previews are deployed](docs/deployment/previews.md)

