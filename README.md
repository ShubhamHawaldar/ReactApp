"# ReactApp" 

### Check repository and add code in respective files that mentioned in below steps.

## Setup react app without using create-react-app (CRA)
  - Prerequisites and tool
    - Node
    - VS Code

  - Create a Node project
    - npm init -y

  - Install Babel dependencies
    - npm install --save-dev @babel/core babel-loader @babel/cli @babel/preset-env @babel/preset-react

  - Install Webpack dependencies
    - npm install --save-dev webpack webpack-cli webpack-dev-server

  - Install HtmlWebpackPlugin
    - npm install --save-dev html-webpack-plugin

  - Install React dependencies
    - npm install react react-dom 

  - Add React files
    - create a public folder and in the created folder create an index.html file
    - create an src folder and in it create an App.js file
    - In the root folder create an index.js

  - configure Babel & Webpack
    - Create a file named webpack.config.js in root folder.

  - add scripts in package.json
    - "scripts": {
    "start": "webpack-dev-server .",
    "build": "webpack ."
  }

  ## Set up ESLint, Prettier and Husky in a React project

  - Installing Eslint dependencies
    - npm install eslint --save-dev

  - Configuring ESLint
    - npm init @eslint/config

  - Installing Prettier dependencies
    - npm install --save-dev --save-exact prettier

  - Configure Prettier
    - In the root folder create a file named .prettierrc.json

  - Integrating Prettier with ESLint
    - npm install --save-dev eslint-config-prettier

  - Configure scripts
    - "scripts": {
                ... // other scripts you have
        "lint": "eslint . --fix --max-warnings=0",
        "format": "prettier . --write"
    }

  - Installing Husky (Make sure your folder is a git directory)
    - npx mrm@2 lint-staged




