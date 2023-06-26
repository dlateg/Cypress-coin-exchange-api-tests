# This is a cypress framework(Gherkin feature files + javascript step files) designed to fetch the exchnage market data, the first seeen time for selected coins and the historic data for selected coins from the coinranking api


Steps for running the code:
1. Install node 

You can download node.js or visit https://nodejs.org/en/download/package-manager/#windows 

2. Install cypress
cd into desired directory and run the following commands 
- npm init then run
- npm install cypress --save-dev

3. Install cucumber and its dependencies

 - npm install --save-dev cypress-cucumber-preprocessor

4. Clone this repository to your local by running 
- git clone https://github.com/dlateg/Api-Test-Cypress/tree/tests-api/cypress


4. Run cypress

npx cypress run or 
npx cypresss open
