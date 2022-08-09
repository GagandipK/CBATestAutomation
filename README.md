# CBATestAutomation
# Web Automation challenge for CBA

## Description

This project has code which can be used to run- 
1. End 2 End UI automated test for registering a user and navigating through all the challenges/ questions to land on Leaderboard and verify data

## Installation

### Step 1 - 
`npm init`

This will initiate a new NPM project on  your machine (Enter the details as required)

### Step2 - 
`npm install cypress`

After the project has been created in Step 1, use this command to install cypress on  your machine.It creates initial files and Folder structure 

[Reference Installation documentation](https://docs.cypress.io/guides/getting-started/installing-cypress#npm-install)

## Installing typescript
`npm install typescript`

## Opening and Running Cypress

Open Terminal in Visual Studio Code or Command Prompt

### Commands - 
`npm run cy:open`

This command is used to open cypress test runner

## Executing tests/ Running Cypress

Once Cypress TestRunner opens: It displays all the tests. 
Click on the test you want to run individually or click 'Run all specs' (at the top right corner) to run all tests.  

### CLI mode Commands - 
`npm run cy:run`

This will run all the tests in command line.

[Command Line Cypress](https://docs.cypress.io/guides/guides/command-line.html#Installation)

## Folder Structure for Cypress

Base Directory for cypress code : ../ResponsiveWA/cypress/

Below are the folders in the Base Directory along with some info about their contents:

### - fixtures
Fixtures are used as external pieces of static data that can be used by your tests. 
Fixture files are located in cypress/fixtures by default, but can be configured to another directory.

This folder contains the parameter files which are being used to pass parameters/environment variables to the code.

### - e2e/regression-tests
This folder contains End to End tests for UI automation using Page Object Model. 

### - e2e/page-objects
This folder contains the classes that are referenced by E2E tests for Page Object Model.

### - support
The support file is a great place to put reusable behavior such as Custom Commands or global overrides that you want applied and available to all of your spec files.

### - screenshots
This is where screenshots will be saved from cy.screenshot() command or after a test fails during cypress run

### - videos
This is where Cypress will automatically save the video of the test run when tests run with cypress run.

# API Automation challenge for CBA

## Description

This project has code which can be used to run- 
API automated test for all APIs to verify the status codes
API reference- https://supervillain.herokuapp.com/api-docs/

## Running API Automation Tests

Open Visual Studio
Go to the Test Explorer and click Run all 



