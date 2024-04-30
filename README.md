# Heroku Flow Gitflow Demo

Demo app using Heroku Flow for CI/CD and Gitflow as the branching strategy. The `dev` branch is linked to the Heroku staging app, and the `main` branch is linked to the Heroku production app. The app is deployed to its respective environment anytime you commit code to either branch.

## Running Locally

Make sure you have [Node.js](http://nodejs.org/) and the [Heroku CLI](https://cli.heroku.com/) installed.

```sh
$ git clone https://github.com/thawkin3/heroku-flow-gitflow-demo.git
$ cd heroku-flow-gitflow-demo
$ npm install
$ npm start
```

Your app should now be running on [localhost:5001](http://localhost:5001/).

## Deploying to Heroku

```
$ heroku create
$ git push heroku main
$ heroku open
```

or

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## Resources

For more information about Heroku and Heroku Flow, see:

- https://devcenter.heroku.com/articles/getting-started-with-nodejs
- https://devcenter.heroku.com/articles/heroku-cli-commands
- https://www.heroku.com/flow
