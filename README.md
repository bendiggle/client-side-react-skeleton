# client-side-react-skeleton
The is a skeleton for a simple reactJS setup for the client-side

### Starting the app:
* To install the dependancies: `yarn install`
* To compile the react code: `yarn setup`
* To run the app: `yarn start`

### The components:
* The important element is the webpack config. This is where the reactJs code is compiled into a javascript the browser can understand and then put into one file called `bundle.js` in the `dist/` directory.
* The react entry point is defined in the webpack config and lives in `./app/js/index.jsx`.
* The view `index.html` contains the element with id `app`. This is where the react components are rendered.
* In `app.js` we have out express route which renders `index.html`.