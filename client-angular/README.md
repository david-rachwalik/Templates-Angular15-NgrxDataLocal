# Templates-Angular15-NgrxDataLocal

## Web App ([repo](https://github.com/david-rachwalik/Templates-Angular15-NgrxDataLocal))

Template for Angular web application with NgRx Data with LocalStorage

### Project Tech Stack

_Languages:_ HTML, CSS, JavaScript, SCSS, TypeScript

Angular 15, NGRX (redux data store)

### Project Commands Used

Generate a new Angular application ([tutorial](https://angular.io/tutorial/toh-pt5), [layouts](https://indepth.dev/posts/1235/how-to-reuse-common-layouts-in-angular-using-router-2), [RxJS](https://www.learnrxjs.io))

```bash
ng new <app-name>
```

Install [NGRX](https://ngrx.io) [Store](https://ngrx.io/guide/store) for state management

```bash
ng add @ngrx/store --skip-confirmation --no-minimal --statePath=store
ng add @ngrx/store-devtools --skip-confirmation
ng add @ngrx/effects --skip-confirmation
ng add @ngrx/entity --skip-confirmation
ng add @ngrx/data --skip-confirmation
```

Install [ngrx-store-localstorage](https://www.npmjs.com/package/ngrx-store-localstorage) to ease localStorage interactions ([Briebug Blog](https://blog.briebug.com/blog/how-to-add-ngrx-store-slices-into-localstorage))

```bash
npm i ngrx-store-localstorage
```

---

#### Deployment Options

Install [GitHub Pages deployment package for Angular](https://www.npmjs.com/package/angular-cli-ghpages) ([Workflow](https://www.atlassian.com/git/tutorials/comparing-workflows))

```bash
ng add angular-cli-ghpages
```

---

### Angular 'generate' Commands Used

Generate a new Angular component

```bash
ng g c <component-name>
```

Generate a new Angular module

```bash
ng g m <module-name>
```
