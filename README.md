# Doice®
App creation and development using voice.

## Disclaimer 
This project is under early construction and alpha release of the first stage is targeted for Oct 2019.

## What will Doice® provide
### Stage 1
With the power of voice, the following abilities will become standard.
* Ability to create a new Angular application
  * Will leverage schematics for choosing routing, scss and additional default config
* Ability to clone existing Angular apps from GIT and initialize them
  * Specifying where in filesystem to create or clone
* Ability to run common CICD scripts inside the package.json such as build, serve, test, lint and package
* Ability to generate new modules, components and services, leveraging the Angular CLI

### Stage 2
Doice® will integrate with Angular Material and the Angular CDK along with their associated schematics.
* Ability to create template layouts that will be a composition of the following components: 
  * Navbar, sidebar, footer, router-outlet, login, page-not-found etc
* Ability to move, position and transform components in a layout
  * Will use an advance representation of a grid

### Stage 3 And Beyond
* Ability to create angular elements and wrap components
* Ability to apply animations on components
* Ability to deploy to AWS services with finer voice control
* Expand platform for React, VueJS, iOS and Android
* Additonal voice devices such as Siri and Google Home
* AI for enriching interctions, predicting dev risk, integration with IBM Watson

## Devices needed
In order to use this tool an Amazon Echo product will be needed for voice recogintion. Doice® is built on top of the Alexa Skills Kit SDK for node.js which can be found [here](https://github.com/alexa/alexa-skills-kit-sdk-for-nodejs).
