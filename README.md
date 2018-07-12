# NY Times ReactJS App
A `NodeJS`, `MongoDB`, `Express`, and `ReactJS` application where users can query, display, and save articles from the New York Times. Users can remove saved articles as well.

Please check out the deployed version in Heroku [here](https://hidden-oasis-49978.herokuapp.com/)!

Click on the headlines to be re-directed to the full New York Times articles.


## Functionality
On the backend, the app uses `express` to serve routes and `mongoose` to interact with a `MongoDB` database.

On the frontend, the app uses `ReactJS` for rendering components, `axios` for internal/external API calls, and `bootstrap` as a styling framework.

In order to transpile the JSX code, `webpack` and `babel` were utilized. All of the JSX  code in the `/app` folder was transpiled into the `bundle.js` file located in the `/public` folder.


