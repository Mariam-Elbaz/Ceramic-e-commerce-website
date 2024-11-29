# FinalProject

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 18.2.4.

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


# Angular Project with JSON Server

This project is an Angular application that uses [JSON Server](https://github.com/typicode/json-server) as a mock backend.

## Data Source: JSON Server

The project uses JSON Server to simulate an API for data storage.

### Setting up JSON Server:

1. **Install JSON Server globally**:
   To run the JSON Server locally, you need to install it globally using npm:
   ```bash
   npm install -g json-server
   ```

2. **Start JSON Server**:
   After installing, create a file named `db.json` in the root directory of your project (or use an existing one), and then run:
   ```bash
   json-server --watch db.json --port 3000
   ```

3. **Access the Data**:
   The data is available at the following URL:
   ```
   http://localhost:3000
   ```

## How to run the Angular app:

1. Install the project dependencies:
   ```bash
   npm install
   ```

2. Serve the Angular application:
   ```bash
   ng serve
   ```

The Angular app will be accessible at `http://localhost:4200`, and it will retrieve data from the JSON Server running on `http://localhost:3000`.

