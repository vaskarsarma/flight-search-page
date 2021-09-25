# Welcome!!! Start using the FLIGHT SEARCH APP

> Application is developed using REACT JS.\
> Atomic Design Pattern is used to achieve component reusability.\
> Used SCSS for style.\
> Jest,Enzyme and React Testing Library used for writing unit test cases (100% code coverage).\
> react-bootstrap is used to implement responsive design.\
> react-app-polyfill is used to enable browser compatibility.

## Use Cases

> Application will shows a list of 10 Flight Routes.\
> Upon clicking the Select Flight Button, the particular flight route has to be highlighted.\
> Select Flight button has to be disabled for this route, until another route is Selected.

## View the application using browser

Please use this GITPAGE URL - https://vaskarsarma.github.io/flightsearchpage/

## Setup the application 

You can run the application in your lacal machine using one of the mentioned approaches.

> **docker**
> **npm script**


### Run the application using DOCKER

If Docker is available on your local machine, you can host the application within a Docker Container.

Run the below command in any CLI

### `docker-compose up`

This command will build and deploy the application in a container.\
Open [http://localhost:3000](http://localhost:3000) to view the page in the browser.

In case container already exists and stopped. Use the below command to start the application.

> Start stopped container - **docker start flight-search-page**.\
> Delete stopped container - **docker rm flight-search-page** and run **docker-compose up** to re-start the application.\
> Delete existing docker image - **docker rmi vaskar/flight-search-page**.

## Run the application using npm scripts

In the project directory, you can run below script on any CLI:

### `npm i`

Will install all the dependencies.

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm run test`

Launches the test runner in the interactive watch mode.

### `npm run test:coverage`

Launches the test runner in the interactive watch mode.

You can also see the Code Coverage details either in CLI or ./coverage/lcov-report/index.html.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!