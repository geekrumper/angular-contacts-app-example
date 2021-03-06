# Angular CRUD Contacts App Example with NgRx Store and NgRx Effects (Version 4)

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)




*Backend is available here: https://github.com/avatsaev/angular-contacts-app-example-api*

**DEMO: http://angular-contacts-ngrx.surge.sh**

This application uses [@ngrx/store](https://github.com/ngrx/platform/blob/master/docs/store/README.md) to manage application state, and [@ngrx/effects](https://github.com/ngrx/platform/blob/master/docs/effects/README.md) to manange side effects, It also uses ngrx 4 fractal state management to leverage lazy loading of reducers and effects.

### New:

[@ngrx/entity](https://github.com/ngrx/platform/tree/master/docs/entity) is released and available on NPM, @ngrx/entity helps to reduce boilerplate and [manipulate data](https://i.imgur.com/2IGdFRB.jpg) in a fast and easy fashion, you can find @ngrx/entity implementation in Contacts Reducer.


## Get started 
This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.4.8

You can run the app with docker compose:

```
$ docker-compose up
```

The app will be available at: http://localhost:8000

![](http://i.imgur.com/TKWwYgQ.png)
![](http://i.imgur.com/GBBXbuu.png)
![](http://i.imgur.com/J4inaXx.png)

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## JSON server

Run `npm run server` to start json server, which is available at `http://localhost:3000`. For productivity purpose just start `npm run dev` which will start angular and json server concurrently. JSON server accepts all REST Methods and updates data accordingly. More Info at [typicode/json-server](https://github.com/typicode/json-server) 

## Data generation with faker.js

In the directory `server` you will find `index.js` which will generate ten contacts. More Info at [Marak/faker.js](https://github.com/Marak/faker.js)

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `ng serve`.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
