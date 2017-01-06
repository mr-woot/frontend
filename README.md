# Front End Setup [![Build Status](https://travis-ci.org/mr-woot/frontend.svg?branch=master)](https://travis-ci.org/mr-woot/frontend)

## Directory Listing:
```
├── app
│   ├── app.js
│   ├── index.html
│   └── styles.css
├── node_modules/
├── bower_components
│   └── knockout
├── bower.json
├── gulpfile.js
├── LICENSE
├── package.json
├── README.md
└── temp
    ├── app.js
    ├── index.html
    ├── styles.css
    └── vendor
        └── knockout.js
```

### Note: You may uninstall bower_components folder and edit bower.json to customize

## Technology Used:
1. Node.js
2. Gulp

## Installation Instructions:
### Initial Setup:
1. Install Node and NPM using 
  ```curl -sL https://deb.nodesource.com/setup_7.x | sudo -E bash -``` followed by
  ```sudo apt-get install -y nodejs```
2. Install Gulp CLI using
  ```npm install -g gulp-cli```

### Project Setup
1. ```git clone https://www.github.com/mr-woot/frontend.git```. Use ```sudo rm -r .git .gitignore``` and setup your own git-based repo using ```git init``` && ```git remote add origin <repo_url>```.
2. ```cd frontend``` and run ```npm install```.
3. Edit if necessary, ```bower.json``` and then run ```bower install```.
4. Run ```gulp``` and open ```localhost:8000``` in your favourite browser (Mine is Chrome :P).
