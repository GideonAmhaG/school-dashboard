
# School Dashboard

This React application demonstrates the effective use of Redux for state management. It covers fundamental Redux concepts like reducers, actions, selectors, and middleware while building a functional dashboard with features like user authentication, notifications, and course management.


## Features

- **Redux Implementation:** Utilizes Redux for efficient state management, including reducers, actions, and selectors.
- **Asynchronous Actions:** Leverages Redux Thunk for handling asynchronous operations like API calls.
- **State Management:** Manages application state with Immutable.js for performance and immutability.
- **Component Structure:** Employs a container/component pattern for improved organization and testability.
- **Testing:** Includes comprehensive unit tests for reducers, components, and action creators.
- **Performance Optimization:** Incorporates selectors for efficient data retrieval and Redux DevTools for debugging.


## Installation/Usage

Clone this Repository

```bash
  https://github.com/GideonAmhaG/school-dashboard
```
Navigate to the Project Directory

```bash
  cd school-dashboard
```
Install Dependencies

```bash
  npm install
```
Run the Development Server

```bash
  npm start
```
Access the Application: Open your browser and go to http://localhost:3000.

    
## Project Structure

The project is organized as follows:

* **src/** - Contains the main source code of the application
    * **App/** - Contains `App.js` and `App.test.js`
    * **BodySection/** - Contains `BodySection.js` and `BodySection.test.js`
    * **CourseList/** - Contains `CourseList.js` and `CourseList.test.js`
    * **Footer/** - Contains `Footer.js` and `Footer.test.js`
    * **HOC/** - Folder for higher-order components
    * **Header/** - Contains `Header.js` and `Header.test.js`
    * **Login/** - Contains `Login.js` and `Login.test.js`
    * **Notifications/** - Contains `Notifications.js`, `Notifications.test.js`, `NotificationsContainer.js`, and `NotificationsContainer.test.js`
    * **actions/** - Folder for action creators
    * **assets/** - Folder for static assets
    * **reducers/** - Folder for reducers
    * **schema/** - Folder for data schemas
    * **selectors/** - Folder for selectors
    * **utils/** - Folder for utility functions
    * **index.js** - Entry point of the application
    * **reportWebVitals.js** - Web vitals reporting

* **__mocks__/** - Contains mock files for testing

* **config/** - Configuration files for the project

* **dist/** - Distribution files (compiled output)

* **.babelrc** - Babel configuration file

* **.gitignore** - Specifies files and directories to be ignored by Git

* **notifications.json** - JSON file related to notifications

* **package.json** - Project metadata and dependencies

* **package-lock.json** - Lock file for dependencies

* **test** - additional test file
## Running Tests

To run tests, run the following command

```bash
  npm test
```


## Authors

Gideon Amha Gebremedhin - [Github](https://github.com/GideonAmhaG) | [X](https://x.com/GideonAmha)


## License

[MIT](https://choosealicense.com/licenses/mit/)

