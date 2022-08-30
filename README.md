# AngularPwa

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.1.2.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

## Run in PWA Mode

Because ng serve does not work with service workers, you must use a separate HTTP server to test your project locally. Use any HTTP server. The following example uses the `http-server` package from npm. To reduce the possibility of conflicts and avoid serving stale content, test on a dedicated port and disable caching.

## Install http-server

Run the below command to install it globally: 

`npm install --global http-server`


To serve the directory containing your web files with `http-server`, run the following command:

`http-server -p 8080 -c-1 dist/angular-pwa`


