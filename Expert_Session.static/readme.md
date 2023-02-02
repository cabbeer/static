# Expert Session is A _minimal_ **Interview Scheduler**
### This application allows users to schedule and manage interviews with ease.


## Setup
### To get started, please follow these steps:

#### 1. Clone the repository to your local machine: 
```
git clone https://github.com/cabbeer/ExpertSession
```
2. Navigate to the project's root directory: cd ExpertSession
3. Install the necessary dependencies: npm install
4. Running the Application:

**Once the setup is complete, you can start the application by running the following command:**


### npm start
This will start the webpack development server, and the application will be accessible at http://localhost:8000/.

### Testing
This application includes a test suite built with Jest and Storybook and Cypress. To run the tests, use the following command:

> npm test

This will execute all tests and display the results in the console.

#### Storybook
This application also includes a Storybook visual testbed. You can run Storybook by using the following command:

> npm run storybook

This will start a local server, and the Storybook interface will be accessible at http://localhost:6006/.

Built With
React.js
Webpack
Jest
Enzyme
Storybook
Contributing
If you're interested in contributing to this project, please review the contributing guidelines.

License
This project is licensed under the MIT License - see the LICENSE file for details.



## What's Included:
```
├── README.md (you are here!)
├── cypress
├── cypress.json
├── jsconfig.json
├── package-lock.json
├── package.json
├── public
│   ├── favicon.ico
│   ├── images
│   ├── index.html
│   └── manifest.json
├── src
│   ├── components
│   │   ├── Application.js
│   │   ├── Application.scss
│   │   ├── Appointment
│   │   │   ├── Confirm.js
│   │   │   ├── Empty.js
│   │   │   ├── Error.js
│   │   │   ├── Form.js
│   │   │   ├── Header.js
│   │   │   ├── Show.js
│   │   │   ├── Status.js
│   │   │   ├── index.js
│   │   │   └── styles.scss
│   │   ├── Button.js
│   │   ├── Button.scss
│   │   ├── DayList.js
│   │   ├── DayListItem.js
│   │   ├── DayListItem.scss
│   │   ├── InterviewerList.js
│   │   ├── InterviewerList.scss
│   │   ├── InterviewerListItem.js
│   │   ├── InterviewerListItem.scss
│   │   └── __tests__
│   │       ├── Application.test.js
│   │       ├── Appointment.test.js
│   │       ├── Button.test.js
│   │       ├── DayListItem.test.js
│   │       └── Form.test.js
│   ├── helpers
│   │   ├── selectors.js
│   │   └── selectors.test.js
│   ├── hooks
│   │   ├── __tests__
│   │   │   └── useVisualMode.test.js
│   │   ├── useApplicationData.js
│   │   └── useVisualMode.js
│   ├── index.js
│   ├── index.scss
│   ├── setupTests.js
│   └── styles
│       ├── animations.scss
│       ├── mixins.scss
│       ├── reset.scss
│       ├── typography.scss
│       └── variables.scss
└── stories
    └── index.js
```
