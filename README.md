# HRdownloads Web App
This is the front end web application for HRDownloads: A place for you to create, deliver, and keep all of your HR content.

If you're looking for the API service associated with this app, [please click here](https://github.com/HRdownloads/hrdownloads-api).

## Getting Started

### Prerequisites
In order to run this app, you will need to have `node` and `npm` installed on your computer.

### Installing
To get your development environment running:

1. Clone this repository:
```bash
$ git clone https://github.com/HRdownloads/hrdownloads-app.git
```

2. Install dependencies:
```bash
$ npm install
```

3. Boot it up!
```bash
$ npm run dev
```

4. Then open: [http://localhost:4000/](http://localhost:4000/)

## Contributing
For more information on contributing, including architecture, style and patterns, please visit [the wiki](https://github.com/HRdownloads/hrdownloads-app/wiki).

## Running the tests

### Unit and integration tests
This app employs Jest as a test runner for both unit and integration tests.

```bash
$ npm run test
```

To run in watch mode:
```bash
$ npm run test:watch
```

### Coding style tests
This app employs `eslint` for code linting. It also employs a pre-push git hook that will automatically run the test suite and linter against your code. This hook must pass in order for your code to be pushed to GitHub.

To run the linter manually:

```bash
$ npm run lint
```

## Style Guide
This app employs [Vue Styleguidist](https://vue-styleguidist.github.io/) to document components. Please visit their ["Docucumenting Components"](https://vue-styleguidist.github.io/Documenting.html) page for more details.

To run Styleguidist locally:
```bash
$ npm run styleguide
```

Then open: [http://localhost:6060/(http://localhost:6060/)

The Styleguide may initially be slow to load. Please give it a minute.

### \<docs>\</docs>
Vue Styleguidist supports the `<docs></docs>` tag in `*.vue` files to document components. Alternatively, you can make an `*.md` file with the component name, e.g. `Button.md`.

## Deployment
This project employs continuous integration through Travis CI. Any pull requests that are merged into master will be automatically deployed to the staging environment.

### Running a manual build
To generate a production build:

```bash
$ npm run build
```

### Built with
- [Vue.js](https://vuejs.org/) - The SPA Framework
- [Travis CI](https://travis-ci.com/) - CI/Deployment
- [Sentry](https://sentry.io/) - Error Logging
- [Jest](https://jestjs.io/) - Test Running
- [Webpack](https://webpack.js.org/) - Bundling
- [npm](https://www.npmjs.com/) - Dependency Management and Task Running
- [Vue Styleguidist](https://vue-styleguidist.github.io/) - Component documentation


### Authors
- [The Working Group](http://www.twg.io/)
- [HRDownloads](https://www.hrdownloads.com/)
