# server-deployment-practice
[GitHub](https://github.com/alsatarysamah/server-deployment-practice)

[heroku](https://samah-server-deploy-prod.herokuapp.com/)

[PullRequist](https://github.com/alsatarysamah/server-deployment-practice/pull/2)

### GitHub
 - I Create a new repository at GitHub, called server-deployment-practice

- Clone this to my local machine.
- Immediately create a “dev” branch
### Heroku
- Create a new Heroku app, called samah-server-deploy-dev
- Connect to server-deployment-practice with branch dev
- Create a new Heroku app, called samah-server-deploy-prod
- Connect to server-deployment-practice with branch main

### The Code
- Initialize server-deployment-practice – npm init -y
- Install  dependencies – npm install dotenv express jest
- Create the files and folders required for the application
- Create the correct content in the files
- Test your server – npm test
I should see 100% of tests passing

### Deploy to dev branch
- ACP on dev branch. after we check it passing all test Open a pull request from dev to main merge this branch Once the tests pass, Heroku will deploymy “main” branch to my “production” app!
