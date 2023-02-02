# Expert Session  <sup>is A</sup> minimal **Interview Scheduler**
### This application allows users to schedule and manage interviews with ease.

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#setup">Setup</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>




## Setup
### To get started, please follow these steps:

#### 1. Clone the repository to your local machine: 
```
git clone https://github.com/cabbeer/ExpertSession
```
#### 2. Navigate to the project's root directory: 
```
cd [local_directory]/ExpertSession
```
#### 3. Install the necessary dependencies: 
```
npm install
```
#### 6. Running the Application: **Once the setup is complete, you can start the application by running the following command:**
```
npm start
```
This will start the webpack development server, and the application will be accessible at http://localhost:8000/.

## Testing

### This application includes a test suite built with Jest and Storybook and Cypress. To run the tests, use the following command:

> npm test

This will execute all tests and display the results in the console.

### Storybook
This application also includes a Storybook visual testbed. You can run Storybook by using the following command:

> npm run storybook

This will start a local server, and the Storybook interface will be accessible at http://localhost:6006/.



## Contributing
If you're interested in contributing to this project, please review the contributing guidelines.




## What's Included:
```
├── README.md (you are here!)
├── cypress
├── cypress.json
├── jsconfig.json
├── package-lock.json
├── package.json
├── public
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
│   ├── helpers
│   ├── hooks
│   ├── index.js
│   ├── index.scss
│   ├── setupTests.js
│   └── styles
└── stories
    └── index.js
```
