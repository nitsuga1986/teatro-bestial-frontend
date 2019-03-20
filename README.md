# TeatroBestialFrontend

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.0.6.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).




## COMANDS used

1. App + Bootstrap + NgBootstrap + FontAwesome
  Run `npm new APPNAME`
From http://www.talkingdotnet.com/add-bootstrap-4-to-angular-6-application/
  Run `npm install bootstrap --save`
  Add to angular.json: "node_modules/bootstrap/dist/css/bootstrap.min.css"
  Run `npm install --save @ng-bootstrap/ng-bootstrap`
  Add to app.module.ts: NgbModule.forRoot()
  Run `npm install font-awesome --save`
  Add to angular.json: "node_modules/font-awesome/css/font-awesome.css"

2. Folder structure
From https://scotch.io/tutorials/angularjs-best-practices-directory-structure
  Add src/assets/css
  Add src/assets/img
  Add src/assets/js

3. Favicon
  https://github.com/FortAwesome/angular-fontawesome

4. Deploy to Heroku
  https://medium.com/@hellotunmbi/how-to-deploy-angular-application-to-heroku-1d56e09c5147

5. Ionic icons
(https://medium.freecodecamp.org/how-to-add-ionicons-to-your-angular-6-apps-7ee5a7b85dc2)
Run `npm install ionicons --save`
Add to styles.scss:
  $ionicons-font-path: "~ionicons/dist/fonts";
  @import "~ionicons/dist/scss/ionicons.scss";
