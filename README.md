<h1 align="center"> React-starter </h1> <br>



## Stack
- Create React App
- React Router
- React Context API
- CSS Modules (scss)
- React-hook-form
- Code splitting (React.lazy & Suspense)
- Chakra UI
- Jest
- react-testing-library
- ESLint - *AirBnB Styleguide*
- Husky - *v4*
- StyleLint
- Storybook

___

### Make it yours
- `git clone git@github.com:SPDUK/react-starter.git reponame` (*replace reponame with your project name*)
- `git remote set-url origin git@github.com:name/repo.git`  (*replace with your new github repo url*)

### Dev Setup
- Install [Yarn package manager v1](https://classic.yarnpkg.com/en/docs/install/#mac-stable) 
- Install [VSCode ESLint plugin](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- Install [VSCode StyleLint plugin](https://github.com/stylelint/vscode-stylelint)
- run `yarn` in the console to install dependencies
- run `yarn start` to launch the React dev server
- run `yarn storybook` to launch the Storybook dev server

___


### Deployment
- Netlify
- Husky (pre-commit linting and error messages)


## Production setup (local)
- run `yarn build` to build the React app
- run `build-storybook` to build the Storybook app


___

## Scripts
- `yarn start` - Start the React development server
- `yarn storybook` - Start the Storybook development server
- `yarn lint` - Lint `.js` & `.jsx` files
- `yarn lint:fix` - Fix problems in `.js` & `.jsx` files
- `yarn stylelint` - Lint `.css` files
- `yarn stylelint:fix` - Fix problems in `.scss` files