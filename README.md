# twitterApp
Using Java Script Appium Android Automation
<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [GUI Test](#GUITest)
  - [Tech stacks](#tech-stacks)
  - [Setup](#setup)
    - [Dev Setup Webdriverio Appium](#setup)
    - [Running test cases](### Running test specs)
    - [Folder structure](### Folder structure)
<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# GUITest
GUI test: TwitterApp 
- Launch of app

## Tech stacks

- [`Mocha`](https://mochajs.org/)
- Chai for Assertion (http://chaijs.com/)
- Appium(http://appium.io/)

## Setup

https://www.youtube.com/watch?v=WgnusVu9Icg
### Dev Setup nodejs and yarn
* install node
* apk file(https://stackoverflow.com/questions/12175904/where-can-i-find-the-apk-file-on-my-device-when-i-download-any-app-and-install)
```
brew update
brew install node
git clone the repo
cd till test dir
npm install
npm start
```
* Open localhost:3030 and verify the webpage is accessible
* [install yarn](https://yarnpkg.com/lang/en/docs/install/)
* install mocha chai and appium desktop
- Use package.json to install supported npm packages:
```
npm install

```
This will install two command line tools, mocha chai and supertest-as-promised. Try running `mocha --version` to make sure it's working.
The Chai is a helper tool to for assertion of API response

### Running test specs

```
node_modules/.bin/wdio

```


### Folder structure

- `test/spec` -  The actual tests 
- `wdio.conf.js` -  configurations


````

.
├── geckodriver
├── package.json
├── test
│   └── spec
│       └── test.spec.js
└── wdio.conf.js

2 directories, 4 files


````


