# SemanticCommit

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.1.3.
I used to test Commitizen, Husky, Commitlint, Conventional changelog and Conventional Commits to generate automatically a Changelog file and better git history

[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)

## Steps

1. Ensure you have [python](https://www.python.org/) installed.
1. Install [Commitizen locally](https://github.com/commitizen/cz-cli#optional-install-and-run-commitizen-locally)
2. Add commit script to package.json:
   ```
   "scripts": {
    "cm": "git-cz"
  }
   ```
3. Install [Visual Studio Code Commitizen extension](https://marketplace.visualstudio.com/items?itemName=KnisterPeter.vscode-commitizen)
4. Install [Angular CommitLint](https://github.com/conventional-changelog/commitlint/tree/master/%40commitlint/config-angular)
5. Install [Husky](https://commitlint.js.org/#/guides-local-setup?id=install-husky) to allow git hook with Commitlint
6. Use [Angular Convention](https://github.com/conventional-changelog/conventional-changelog/blob/master/packages/conventional-changelog-angular/README.md#angular-convention)
7. Install [standard-version](https://github.com/conventional-changelog/standard-version#installing-standard-version)
8. 
9. 

## References

* [Enhance your git log with conventional commits](https://dev.to/maxpou/enhance-your-git-log-with-conventional-commits-3ea4)
* [Git Tools - Rewriting History](https://git-scm.com/book/en/v2/Git-Tools-Rewriting-History)
* [Git: Squash your latest commits into one](https://www.devroom.io/2011/07/05/git-squash-your-latests-commits-into-one/)
* [Conventional commits](https://www.conventionalcommits.org)
* [Angular commit message guidelines](https://github.com/angular/angular/blob/master/CONTRIBUTING.md#-commit-message-guidelines)
* [Release management in Angular with Lerna](https://indepth.dev/release-management-in-angular-with-lerna/)
* [nxg-semantic-version](https://github.com/d-koppenhagen/ngx-semantic-version)

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

