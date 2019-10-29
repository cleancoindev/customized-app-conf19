# Buttercup Games App

![app preview](https://github.com/splunk/customized-app-conf19/raw/master/public/dashboard-final.png)

This repo contains the source code for the Buttercup Games App, a customized Single Page Application leveraging Splunk's platform and libraries. It was demoed in the "Building Applications with Splunk UI and React Visualizations" developer talk at .conf 2019.

## The 3 Building Blocks

To build this app we used 3 JavaScript packages published by Splunk:

### @splunk/react-ui

This package exposes UI components such as buttons, modals, a table

### @splunk/dashboard-framework

This package exposes React components to render a dashboard based on a dashboard definition.

### @splunk/react-visualizations

This package exposes Splunk's visualizations as React components

Each of the packages can be installed via the public npmjs registry.

## How to run

Use `npm install` or `yarn` to install the dependencies. Then run `npm run start` or `yarn start` to start the application. It will host the application on `http://localhost:3000/`

## How to read the code

The app's entry point is at `src/App.js`.
In this file we import the `DataModal` to show additional context in a modal, and `DashboardCore` to render the main dashboard view.

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

## Feel free to drop an email if you have any question

Dashboard Team - dashboards@splunk.com<br>
Visualization Team - visualizations@splunk.com<br>
