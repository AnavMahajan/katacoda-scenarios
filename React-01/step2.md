 `create-react-app` helper package is everything you need to run your first react js project. Run the following npm (node package manager) commands to proceed with installation:

command 1 to install `create-react-app` helper package in the global mode `npm install create-react-app -g`{{execute}}

command 2 to create your first react app using the `create-react-app` helper package `create-react-app react-first-project --scripts-version 1.1.5`{{execute}}Once Installed, It will create a directory called `react-first-project` inside the current folder.

Inside that directory, it will generate the initial project structure and install the transitive dependencies:

```react-first-project
├── README.md
├── node_modules
├── package.json
├── .gitignore
├── public
│   ├── favicon.ico
│   ├── index.html
│   └── manifest.json
└── src
    ├── App.css
    ├── App.js
    ├── App.test.js
    ├── index.css
    ├── index.js
    ├── logo.svg
    └── serviceWorker.js
    └── setupTests.js```
	
For more details on the  [Create React App](https://github.com/facebook/create-react-app).