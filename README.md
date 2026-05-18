##Start Project please run this command at first time

`npm install` for load library

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

#serve with different environment
	
You can try : `ng serve --configuration=dev/prod/office` or `ng serve --environment=dev/prod/office`

#serve with different port

You can try : `ng serve --port=5000` 5000 >> it mean your port


##Building for Production
`node --max_old_space_size=4096 node_modules/@angular/cli/bin/ng build --configuration=office --baseHref=/cirweb/  --build-optimizer=false`

--max_old_space_size=4096 node_modules/@angular/cli/bin/ >> for solve process out of memory in javascripts
--baseHref >> it mean your sub context
ng build >> to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.


---------------------------------------------------------------------------------------------------------
# CifsBackend

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.5.0.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Our project use this for build
`node --max_old_space_size=4096 node_modules/@angular/cli/bin/ng build --configuration=office --baseHref=/cirweb/  --build-optimizer=false`

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).


