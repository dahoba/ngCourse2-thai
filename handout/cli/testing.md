# Testing

Apps generated by the CLI integrate automated tests. The CLI does this by using the [Karma test runner](https://karma-runner.github.io).

## Unit Tests

To execute unit tests, run `ng test`. This will run all the tests that are matched by the Karma configuration file at *config/karma.conf.js*. It's set to match all TypeScript files that end in *.spec* by default.


## End-to-End Tests

End-to-end tests can be executed by running `ng e2e`. Before end-to-end tests can be performed, the application must be served at some address. Angular CLI uses protractor. It will attempt to access `localhost:4200` by default; if another port is being used, you will have to update the configuration settings located at `config/protractor.conf.js`.
