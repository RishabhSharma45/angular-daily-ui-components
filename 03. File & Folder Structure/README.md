# Demo

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 21.0.4.

## Development server

To start a local development server, run:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

## Code scaffolding

Angular CLI includes powerful code scaffolding tools. To generate a new component, run:

```bash
ng generate component component-name
```

For a complete list of available schematics (such as `components`, `directives`, or `pipes`), run:

```bash
ng generate --help
```

## Building

To build the project run:

```bash
ng build
```

This will compile your project and store the build artifacts in the `dist/` directory. By default, the production build optimizes your application for performance and speed.

## Running unit tests

To execute unit tests with the [Vitest](https://vitest.dev/) test runner, use the following command:

```bash
ng test
```

## Running end-to-end tests

For end-to-end (e2e) testing, run:

```bash
ng e2e
```

Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.

---


```
my-angular-app/
│
├── node_modules/
├── src/
│   ├── app/
│   ├── assets/
│   ├── environments/
│   ├── index.html
│   ├── main.ts
│   ├── styles.css
│
├── angular.json
├── package.json
├── tsconfig.json
└── README.md
```

### node_modules/ (Isme mat ghusna 😄)

node_modules contains all dependency packages required by Angular application

### src/

**src/index.html**

Single page Application 

> Yahin se Angular poora app inject karta hai.

**src/main.ts**

Angular app yahin se start hota hai.

**src/styles.css**

Global css

**src/app/ – Heart of Angular ❤️**

```
app/
├── app.component.ts
├── app.component.html
├── app.component.css
├── app.module.ts
└── app-routing.module.ts
```

**tsconfig.json v/s tsconfig.app.json v/s tsconfig.spec.ts**

tsconfig.json used to configured typeScript and set some set of rules in root directory where as tsconfig.app.json is used to configured ts of app module and tsconfig.spec.json is for testing purpose . 

**package.json**

“package.json defines the project metadata, scripts, and dependency graph,

enabling npm to manage lifecycle commands and environment consistency.”

**angular.json**

“angular.json is the central workspace configuration file that defines how Angular CLI builds, serves, tests, and packages applications across different environments.”





















