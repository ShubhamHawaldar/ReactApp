"# ReactApp" 

### Check repository and add code in respective files that mentioned in below steps.

## Setup react app without create-react-app (CRA)
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




