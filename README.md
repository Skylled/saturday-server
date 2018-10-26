# saturday_server
This is the Aqueduct server portion of a side project I'm working on. The primary goal of the project is to be able to watch cartoons with my friends and choose what to watch from our phones using a Rock Band 4-esque voting system instead of just shuffle.

The media side of things will likely be handled by Kodi, given its fairly useful API including Library support.

The votes will be collected from a Flutter application, hosted in a separate project.

The other goal of this project is to develop an understanding of Aqueduct, so I may use it in other projects.

## Running the Application Locally

Run `aqueduct serve` from this directory to run the application. For running within an IDE, run `bin/main.dart`. By default, a configuration file named `config.yaml` will be used.

To generate a SwaggerUI client, run `aqueduct document client`.

## Running Application Tests

To run all tests for this application, run the following in this directory:

```
pub run test
```

The default configuration file used when testing is `config.src.yaml`. This file should be checked into version control. It also the template for configuration files used in deployment.

## Deploying an Application

See the documentation for [Deployment](https://aqueduct.io/docs/deploy/).
