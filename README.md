# Azure CI/CD Pipeline Architecture

## Overview

This project demonstrates a multi-stage CI/CD pipeline for building, testing, and deploying applications using Azure DevOps.

## Architecture

Developer → GitHub → Azure DevOps Pipeline → Build → Test → Deploy

## Tech Stack

* Azure DevOps
* YAML Pipelines
* Git
* Azure App Service (planned)

## Pipeline Stages

### Build

* Compile application
* Validate code

### Test

* Run basic validation checks

### Deploy

* Deploy application to target environment

## Project Structure

```
.
├── app/
├── azure-pipelines.yml
├── docs/
└── screenshots/
```

## Future Improvements

* Add Docker build stage
* Deploy to Azure App Service
* Integrate Key Vault
