# Selenium-Cucumber-demo


1. Init a local repo

cd /Users/viacheslavborysovskyi/Documents/e2e/Cucumber/Selenium-Cucumber-demo/
 
git init 

2. Create a remote repo on github.com

3. Connect the local and remote repos

git clone ssh://[link-to-remote]

4. Create a shortname for the remote repo

git remote add origin [link-to-remote]

5. Creating a package.json file

cd /Users/viacheslavborysovskyi/Documents/e2e/Cucumber/Selenium-Cucumber-demo/e2e/

npm init

6. Creating tsconfig.js

cd /Users/viacheslavborysovskyi/Documents/e2e/Cucumber/Selenium-Cucumber-demo/e2e/

tsc --init

7. Installing Cucumber (https://www.lambdatest.com/blog/cucumberjs-tutorial-selenium/)
 
npm install -g cucumber

npm install  --save-dev cucumber

8. Installing Selenium Web Driver

npm install selenium-webdriver

9. Installing Browser Driver

npm install -g chromedriver

10. Create test directories:
- "cucumber_test";
- under "cucumber_test" create "features" and "step_definitions" folders

11. Adding scrips into package.json

{
  "scripts": {
    "test": "./node_modules/.bin/cucumber-js"
  }
  
  12. Add the following dependencies in package.json

"assert": "^1.4.1",
"chromedriver": "^2.24.1",
"geckodriver": "^1.1.3"
