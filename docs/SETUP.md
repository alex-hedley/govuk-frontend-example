# Setup

- https://github.com/alphagov/govuk-frontend
- https://frontend.design-system.service.gov.uk

## Install with Node.js package manager (npm)

🔗 https://frontend.design-system.service.gov.uk/installing-with-npm/#install-with-node-js-package-manager-npm

`npm init`

> name: govuk-frontend-example
> version: 0.0.1
> description: <blank>
> entry point: (index.js)
> test command: jest
> git repository: https://github.com/alex-hedley/govuk-frontend-example
> keywords: example
> author: Alex Hedley
> license: (ISC) MIT

See [package.json](../src/package.json)


https://www.npmjs.com/package/sass

`npm install -g sass`

`npm install --save-dev sass`

```json
"devDependencies": {
    "sass": "^1.70.0"
}
```

`npm install govuk-frontend --save`

```json
"dependencies": {
    "govuk-frontend": "^5.0.0"
}
```

## Get started

https://frontend.design-system.service.gov.uk/get-started/#get-started

cp -R node_modules/govuk-frontend/dist/govuk/govuk-frontend.min.css styles/

```bash
copy the node_modules/govuk-frontend/dist/govuk/govuk-frontend.min.css file into your application
```

`cp -R node_modules/govuk-frontend/dist/govuk/assets/ assets`

```bash
/node_modules/govuk-frontend/dist/govuk/assets/images folder to <YOUR-APP>/assets/images
/node_modules/govuk-frontend/dist/govuk/assets/fonts folder to <YOUR-APP>/assets/fonts
/node_modules/govuk-frontend/dist/govuk/assets/manifest.json file to <YOUR-APP>/assets
```

```bash
copy the node_modules/govuk-frontend/dist/govuk/govuk-frontend.min.js file into your application
```

`cp -R node_modules/govuk-frontend/dist/govuk/govuk-frontend.min.js scripts/`

⚠️ Error

> Uncaught TypeError: Failed to resolve module specifier "scripts/govuk-frontend.min.js". Relative references must start with either "/", "./", or "../".

## Extra

`npm install --save-dev jest`

- https://jestjs.io/docs/getting-started

```json
"devDependencies": {
    "jest": "^29.7.0"
}
```

`npm init @eslint/config`

- https://eslint.org/docs/latest/use/getting-started

```json
  "devDependencies": {
    "eslint": "^8.56.0",
    "eslint-config-airbnb-base": "^15.0.0",
    "eslint-plugin-import": "^2.29.1"
  }
```
