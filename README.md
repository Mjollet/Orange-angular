# AutoDiag

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.7.3.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files. Use the `--open` flag to automatically open the application in your preferred browser.

Run `npm install` before running the server to install all the dependencies.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

If you deploy the application on IBM Cloud, you will need to create a `manifest.yml` file and an empty `Staticfile` then copy them in the `dist/` directory after building the project. You'll have to manually copy them in the `dist/` directory each time you build the project. Then use [Cloud Foundry CLI](https://github.com/cloudfoundry/cli) to push your application.

### Simple example of a manifest.yml file

``` yml 
applications:
- name: auto-diag
  memory: 64M
  buildpack: staticfile_buildpack
```

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
