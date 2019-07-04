# Proyecto Angular para mostrar Arquitectura BFF

### How to start

**Note** that this seed project requires **node >=v8.9.0 and npm >=6**.

In order to start the project use:

```bash
$ git clone https://github.com/matiasarayac/angular-example-bff.git
$ cd angular-example-bff
# install the project's dependencies
$ npm install
# watches your files and uses livereload by default run `npm start` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.
$ npm start
# prod build, will output the production application in `dist`
# the produced code can be deployed (rsynced) to a remote server
$ npm run build
```

Para ejecución local y conexión con los microservicios es necesario deshabilitar web-security del browser para no tener problemas de CORS en los microservicios. Para Chrome:
Windows: 
```bash
"C:\Program Files (x86)\Google\Chrome\Application\chrome.exe" --disable-web-security --user-data-dir
```

Linux:
```bash
google-chrome  --disable-web-security --user-data-dir
```

OSX:
```bash
open /Applications/Google\ Chrome.app --args --user-data-dir --disable-web-security
```



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
"# angular-example-bff" 
