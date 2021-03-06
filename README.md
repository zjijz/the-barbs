# TheBarbs

This project was generated with [angular-cli](https://github.com/angular/angular-cli) version 1.0.0-beta.19-3.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive/pipe/service/class`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `ng serve`.

## Deploying to Github Pages

Run `ng github-pages:deploy` to deploy to Github Pages.

## Further help

To get more help on the `angular-cli` use `ng --help` or go check out the [Angular-CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

## To-Do 
- [x] User mode
  - Instructions of how to use
- [x] Superuser mode
  - Instructions of how to use
- [ ] General
  - [x] Fix issue with drawer not closing on reroute
  - [x] Fix link issues showing on login page
  - [ ] Add a route guard to autoroute to login if user is not logged in
- [x] Login page
  - [x] Form
  - [x] Wired to backend
  - [x] Add 'enter' logs in feature on login page
- [x] Home page
  - [x] Loan scroller
  - [x] Hold scroller
  - [x] Search bar
  - [x] Wire to backend
  - [x] Add a thing where searching switches out the hold/loan view with search results
  - [x] Add a keyup event hook to check if a user hit 'enter'
  - [x] If no holds / loans, add a message to tell user to search for books
  - [x] Issue if no holds or loans on user account
  - [x] Get search working
  - [x] Adding loans
  - [ ] Adding holds
  - [ ] Weird graphical glitch when adding another book to hold / loan scroller (book's aren't right next to each other)
  - [x] Issue with searching not always having book id?
- [x] Book Preview
  - [x] Display all book information
  - [x] Run queries to get if book is on user's hold or loan lists (and show cards based on this)
  - [x] Ability to open to reader if user has a loan for the book
- [x] Book Reader
  - [x] Display text file as a scrolling p tag
- [x] Dashboard
  - [x] Show the user information on a card
  - [x] Wire to backend
- [x] Feed
  - [x] Show all reviews from friends in simple scroll
  - [x] Add ability to delete posts
  - [x] Superuser shows all reviews with ability to delete
  - [x] Test delete
  - [x] Test addition
  - [x] Wire to backend
  - [x] Make message submit close and reset when clicking submit (after insert)
