# Host your angular application for FREE with firebase hosting using the firebase cli

visit The [Firebase Console](https://console.firebase.google.com) login with your google account and create a new project.

open you terminal and create a [new Angular project](https://cli.angular.io/)

install Angular cli `npm install -g @angular/cli`

create a new angular application `ng new your_project_name --routing=true --commit=true`

`cd your_project_name`

to test if everytihng is working `ng serve --open`

Install and set up firebase hosting

`npm install -g firebase-tools`

`firebase login`

`firebase init`

Select hosting

Select the project you created in the firebase console

set you public folder to `dist/your_project_name`

Select configure as a single page application

`ng build --prod`

`firebase deploy`




# Gdgsitegh

This [project](https://gdgsitegh.web.app) was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.3.7.

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
