# CICD Pipelines

This folder contains all the different Azure DevOps pipelines in YAML format so they can be directly used in you DevOps project. 

These pipelines are written using the Pipeline artifacts feature (see: https://docs.microsoft.com/es-es/azure/devops/pipelines/artifacts/pipeline-artifacts?view=azure-devops&tabs=yaml) and they contain build and deploy stages in a single pipeline.

In order for these pipelines to work, you need to install in the **Files Validator** extension from https://marketplace.visualstudio.com/items?itemName=roshkovski.Files-Validator in your Azure DevOps organization.


## analyticsRules.yml
Publishes Analytics Rules json file under AnalyticsRules folder as a pipeline artifact and executes CreateAnalyticsRules.ps1 script to deploy the rules defined in the json file. It also validates proper JSON syntax for the rules file.

## playbooksCICD.yml
Publishes all json files under Playbooks folder as pipeline artifacts and executes CreatePlaybooks.ps1 script to create all the playbooks.


