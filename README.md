# systers.github.io
## Project Overview
This is the main website for Systers Open Source.  It contains information about our various open source projects, the programs we participate in (as well as their historical data), information about how to contribute, and general information about how to contact us.

In the future, we hope to add Google Calendar integration and additional orientation/onboarding materials.

## Documentation
Link: https://docs.google.com/document/d/18X83wQjltI2PyWmYqNx4cHvGdTBTu2NaWnlIizdsLO8/edit#

## Live Heroku App
Link to the App: https://systers-github-io.herokuapp.com/

## Installation
To preview, run these commands in your terminal (as long as you’ve previously installed [node](https://nodejs.org/en/download/)):

1. `git clone https://github.com/systers/systers.github.io`
2. `cd systers.github.io`
3. `git checkout develop`
4. `npm install`
5. `npm install -g @angular/cli`
6.  Run the command `npm run dev` to run the client side and server side simultaneously. 
7.  Run the command `./node_modules/.bin/eslint yourfile.js --fix` in the root directory to fix linting errors in javascript files before making a PR. You can add new rules to .eslintrc.js. 


## Contact Information
If you have any questions or want to discuss something about this repo, please sign up for the [Systers Slack Channel](http://systers.io/slack-systers-opensource/) and join the the #gh-pages channel.

## Travis Integration
- Tests are automatically run through Travis-CI for PR's.
- Currently the gsoc18-code branch is setup to deploy to heroku after a successful build, will be changed to the master branch in the future.
