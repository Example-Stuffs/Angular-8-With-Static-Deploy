# Angular-8-With-Static-Deploy
This repo serves as nothing more than to show how one can deploy a generic angular 8 app to S3 and GCS

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.3.22.

## Build & Deploy Scripts
Build and deploy everything:
```bash 
  npm run deploy
```
Build only:
```bash 
  npm run build
```
Deploy without building:
```bash 
  npm run deploy:nobuild
```
Deploy to AWS without building:
```bash 
  npm run deploy:aws
```
Deploy to GCP without building:
```bash 
  npm run deploy:gcp
```
Un-Deploy (delete everything from buckets):
```bash 
  npm run undeploy
```
Un-Deploy from AWS:
```bash 
  npm run undeploy:aws
```
Un-Deploy from GCP:
```bash 
  npm run undeploy:gcp
```

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
