# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

# This assessment was given to me by Lendsqr company
I was given this assessment to build the 4 pages Login, Dashboard, User page, and User details page.
Using React.js with Typescript and SCSS for styling

### `Available Script`
To run this project:
clone it at https://github.com/albertase/Albert-Ukaegbu-Nnaji.git
cd Albert-Ukaegbu-Nnaji 
run npm install to install all the dependencies.
run npm start to start the project server.

### `Testing the app`
I wrote test for this assessment
run npm run test to test it.


### `State Management`
Context API provided by lendsqr company was used to manage the state.

### `Log in`
After starting the app the login page comes up first 
Users can always use any random email and password to log in but it must be in the correct format of email, 
and password Must contain(0-9, A-z @, $, !, %, *, ?, or &) & 8 character long
or use one of the users' emails from the mock API to see the user's profile.
e.g. Maverick.Hyatt83@gmail.c or Katarina_Botsford@hotmail.com with a random password.

### `Dashboard`
After Logging in successfully, it will redirect you to the Dashboard, where you can play with the sidebar, though is only the user that has data to display.
Users can also filter in that same Dashboard.

When click on the Pagination, you'll see different users based on the API provided
You can as well click on the three dots on each user to view the user's profile, Blacklist, or Activate users.

Users' status is displayed on clicking the view profile button and users can as well change the status.

Other detail you need to know about React below 👎



## `Header Component`
This component is a React functional component that creates a header with search, menu bar, and profile functionalities. It also includes some SVG icons for better user experience.

Dependencies
This component requires the following dependencies:

react
react-dom
react-router-dom
prop-types
svgIcons


Usage
This component can be imported in your React application as follows:
import Header from './components/Header/Header';

Then it can be used in your React component like this:
<Header />

Props
This component does not accept any props.

Features
Search functionality with the ability to filter through a list of users.
Profile image with a dropdown menu for user actions.
Menu bar for mobile view.
Notification icon for showing notifications.
Logo icon for navigating to home.


## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).




