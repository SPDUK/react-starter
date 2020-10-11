# React Starter


### Stack

- Create React App
- React Router
- React Context API
- CSS Modules (scss)
- Formik or React-hook-form (TODO: set up)
- Code splitting (loadable-components)
- Jest, react-testing-library

### Dev tools

- ESLint - JS & React Linting  (AirBNB Style)
- StyleLint - CSS Linting
- Storybook


### Deployment

- Netlify
- Husky pre-commit linting and error messages to stop commiting of broken code


# Dev Setup
*(Assumes VSCode)*
- Install ESLint plugin
- Install StyleLint plugin
- `.vscode/settings.json` should now automatically lint .js, .jsx & .scss files correctly in line with linting rules

### Commands:
`lint` - Lint `.js` & `.jsx` files
`lint:fix` - Fix problems in `.js` & `.jsx` files
`stylelint` - Lint `.css` files
`stylelint:fix` - Lint `.scss` files


# Storybook

`yarn storybook`