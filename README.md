# Building dynamic Implementation Guides with FHIR Shorthand and Firely Query Language

[![FHIR Project on Simplifier.net](https://img.shields.io/badge/FHIR_project_on_Simplifier.net-ACMEGitHubExample-green)](https://simplifier.net/ACMEGitHubExample) [![Firely Validation)](https://github.com/FirelyTeam/devdays-lets-build-fsh-and-fql/actions/workflows/main.yml/badge.svg)](https://github.com/FirelyTeam/devdays-lets-build-fsh-and-fql/actions/workflows/main.yml)

This repository can be used for the DevDays presentation "Building dynamic Implementation Guides with FHIR Shorthand and Firely Query Language"

To run this project locally you need to:

1. Install and setup [NPM](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)
1. Setup the FHIR Shorthand compiler, via [SUSHI](https://github.com/FHIR/sushi)
1. Run ``sushi resources/``
1. The FHIR profiles and examples should be created by SUSHI in ``resources/fsh-generated``

Run SUSHI in the GitHub cloud:

1. Click the "Use this template" button
  * Enter a custom repo name
  * Check the box "Include all branches" 
3. Go to "Action" tab
4. Select "Firely Validation"
5. Select "Run Workflow"
6. View output of "CI_FHIR_VALIDATION" action
