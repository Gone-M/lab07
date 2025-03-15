# Lab07_StudentID

## Exercise 1 - Express Generator

This exercise demonstrates setting up an Express.js application using the Express Generator.

### Steps:
1. Create a folder `Lab07_101441732/exercise-1`.
2. Install Express Generator:
   ```sh
   npm install -g express-generator
   ```
3. Generate an Express app:
   ```sh
   express --view=pug myapp
   cd myapp
   npm install
   ```
4. Start the application:
   ```sh
   npm start
   ```
5. Open `http://localhost:3000` in a browser.

## Exercise 2 - Routes + Body Parser

This exercise adds body-parser middleware and creates a route to handle POST requests.

### Steps:
1. Install body-parser:
   ```sh
   npm install body-parser
   ```
2. Modify `routes/users.js` to handle POST requests and log body parameters.
3. Restart the application:
   ```sh
   npm start
   ```
4. Use Postman to send a POST request to `http://localhost:3000/users`.

## Exercise 3 - Angular First Application

This exercise demonstrates setting up an Angular application using Angular CLI.

### Steps:
1. Create a folder `Lab07_101441732/exercise-2`.
2. Install Angular CLI globally:
   ```sh
   npm install -g @angular/cli
   ```
3. Generate a new Angular project:
   ```sh
   ng new my-app
   cd my-app
   ng serve
   ```
4. Open `http://localhost:4200` in a browser.
5. Modify `src/app/app.component.ts` to change the title.

