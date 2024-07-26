# Template configurations

## Webpack
- `build` script enabling `npm run build` command
- style-loader and css-loader
- image loading
- font loading
- HtmlWebPackPlugin with template configured
- output filename: [name].bundle.js
- output clean: true

## Linter
- ESLint v8 (to support airbnb config as v9 is not compatible with Airbnb config yet)
- [Airbnb base ESLint Config](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb-base)
- [Prettier ESLint Config to fix conflicts between Prettier and ESLint Rules](https://github.com/prettier/eslint-config-prettier)

## Others

- `pages` script to enable hosting `\dist` on github pages
