#This repository contains automated tests using the Cypress framework to perform functional testing on web applications.

#Prerequisites
Before running the tests, make sure you have the following installed in your development environment:
Node.js - version 12 or higher
NPM (Node Package Manager) - usually installed together with Node.js

Installation
Clone this repository to your local environment:
bash
Copy code
git clone https://github.com/sullivan28/testsCypress.git
Navigate to the project directory:
bash
Copy code
cd testsCypress
Install project dependencies:
bash
Copy code
npm install
Running the Tests

#To execute the tests, use the following command:
Copy code
npx cypress open
This command will start the execution of the automated tests using Cypress.

Project Structure
The project has the following structure:

go
Copy code
├── cypress
│   ├── fixtures
│   │   └── example.json
│   ├── integration
│   │   └── test_spec.js
│   ├── plugins
│   │   └── index.js
│   └── support
│       ├── commands.js
│       └── index.js
├── node_modules
├── .gitignore
├── cypress.json
├── package.json
└── README.md
The "cypress/fixtures" directory contains data files used in the tests (e.g., JSON files).
The "cypress/integration" directory contains the test specification files (e.g., .js files).
The "cypress/plugins" directory contains plugin configuration files for Cypress.
The "cypress/support" directory contains support files, such as custom commands.
