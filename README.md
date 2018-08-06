[![Angular Logo](./src/assets/images/angular.png)](https://angular.io/)
<div align="center">
  <a href="http://typeorm.io/">
    <img src="https://github.com/typeorm/typeorm/raw/master/resources/logo_big.png" width="492" height="228">
  </a>
  <br>
</div>

[![Electron Logo](https://electronjs.org/images/electron-logo.svg)](https://electronjs.org)


[![Build Status](https://travis-ci.org/CubikNeRubik/angular-electron-typeorm-starter.svg?branch=master)](https://travis-ci.org/CubikNeRubik/angular-electron-typeorm-starter)
[![License](http://img.shields.io/badge/Licence-MIT-brightgreen.svg)](LICENSE.md)

[![Watch on GitHub][github-watch-badge]][github-watch]
[![Star on GitHub][github-star-badge]][github-star]

# Quickstart
``` bash
git clone https://github.com/CubikNeRubik/angular-electron-typeorm-starter.git
npm install
npm start
```

# Introduction

This is a start kit for easy launch of Electron, Angular 6 and TypeORM.

Currently runs with:

- Angular v6.1.1
- Electron v2.0.6
- Electron Builder v20.27.0
- TypeORM v0.2.7
- SQLite v4.0.2

With this start kit, you can :

- Run your app in a local development environment with Electron & Hot reload
- Run your app in a production environment
- Package your app into an executable file for Linux, Windows & Mac

## Getting Started

Clone this repository locally :

``` bash
git clone https://github.com/CubikNeRubik/angular-electron-typeorm-starter.git
```

Install dependencies with npm :

``` bash
npm install
```

If you want to generate Angular components with Angular-cli , you **MUST** install `@angular/cli` in npm global context.  
Please follow [Angular-cli documentation](https://github.com/angular/angular-cli) if you had installed a previous version of `angular-cli`.

``` bash
npm install -g @angular/cli
```

## To build for development

- **in a terminal window** -> npm start  

The application code is managed by `main.ts`. In this sample, the app runs with a simple Angular App (http://localhost:4200) and an Electron window.  
The Angular component contains an example of Electron and NodeJS native lib import.  
You can desactivate "Developer Tools" by commenting `win.webContents.openDevTools();` in `main.ts`.

## Included Commands

|Command|Description|
|--|--|
|`npm run ng:serve:web`| Execute the app in the browser |
|`npm run build`| Build the app. Your built files are in the /dist folder. |
|`npm run build:prod`| Build the app with Angular aot. Your built files are in the /dist folder. |
|`npm run electron:local`| Builds your application and start electron
|`npm run electron:linux`| Builds your application and creates an app consumable on linux system |
|`npm run electron:windows`| On a Windows OS, builds your application and creates an app consumable in windows 32/64 bit systems |
|`npm run electron:mac`|  On a MAC OS, builds your application and generates a `.app` file of your application that can be run on Mac |

**Your application is optimised. Only /dist folder and node dependencies are included in the executable.**

## Browser mode

You can't use TypeORM in browser so it is not possible.
If you need to run app in browser and don't need TypeORM you can use [angular-electron](https://github.com/maximegris/angular-electron) for that

[github-watch-badge]: https://img.shields.io/github/watchers/CubikNeRubik/angular-electron-typeorm-starter.svg?style=social
[github-watch]: https://github.com/CubikNeRubik/angular-electron-typeorm-starter/watchers
[github-star-badge]: https://img.shields.io/github/stars/CubikNeRubik/angular-electron-typeorm-starter.svg?style=social
[github-star]: https://github.com/CubikNeRubik/angular-electron-typeorm-starter/stargazers