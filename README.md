# World Map – Angular Application

## Project Description
This project is an interactive World Map application developed using Angular and TypeScript. It uses an SVG world map to allow users to hover over individual countries and retrieve country information through the World Bank API. The application displays the world map in one column and the selected country's information in a second column. This application demonstrates the use of Angular components, routing, event binding, HTTP services, and external API integration. 

## Technologies
-	**Angular:** Used to develop the application and manage components.
-	**TypeScript:** Used for application logic.
-	**HTML and CSS:** Used to create the two-column application layout.
-	**SVG World Map:** Provides the interactive geographical map interface.
-	**Angular Routing:** Redirects the default application URL to the map page.
-	**Angular HttpClient:** Handles HTTP requests to the World Bank API.
-	**World Bank API:** Provides country information.

## World Bank API Information
The application retrieves country information using the World Bank API.
```
API endpoint:
https://api.worldbank.org/v2/country/${countryCode}?format=json
```
The application displays the following information for each selected country:
1.	Country Name
2.	Country Capital
3.	Country Region
4.	Income Level
5.	Country Population
6.	Country Latitude and Longitude

## Application Features
### Interactive World Map
-	Displays an SVG world map.
-	Allows users to hover over countries using mouse events.
-	Passes the selected country's two-letter country code to the Angular component.

### Country Information
-	Retrieves country details from the World Bank API.
-	Uses an Angular service and HttpClient to make API requests.
-	Displays the selected country's information in the information column.

### Angular Routing
-	Configures the default route to redirect automatically to /world-map.

### Two-Column Layout
-	Left column: Interactive SVG world map.
-	Right column: Selected country information.

## Project Configuration
Angular Version: 18.2.0
This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 18.2.0.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
