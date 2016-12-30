# [KillerApp](https://team-heat-killer-app.herokuapp.com/)

![image](./src/assets/screenshot3.png)

![image](./src/assets/screenshot4.png)

![image](./src/assets/screenshot5.png)

![image](./src/assets/screenshot6.png)

This project was generated with [angular-cli](https://github.com/angular/angular-cli) version 1.0.0-beta.22-1.

# Routes

## API Routes
- Inject ApiUrlsConfigService - all api urls included as properties

## Gallery ( App Routes )
- /gallery -> all items
- /gallery/:id -> item details
- add item to user favorites
- bidding and/ or buying items 
- vote up/ down ( possibly )

## Creating an item ( App Routes )
- /create -> from for creating a new item, logged user

## User ( App Routes )
- /favorites -> list user favorite items, logged user

# How to run

## npm start 
`node server/app.js` 

## npm run start:dev
`ng serve`

## ng build -w 
Run `npm start` in a separate terminal. Needs running mongodb.

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
