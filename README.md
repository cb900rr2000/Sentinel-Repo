[![Build Status](https://soricloud.visualstudio.com/SentinelAsCode/_apis/build/status/scriptsCI?branchName=master)](https://soricloud.visualstudio.com/SentinelAsCode/_build/latest?definitionId=23&branchName=master)

# Azure Sentinel as Code

The purpose of this project is to protect a lighthouse test 

The project has several folders for each of the different Sentinel components that can be configured (Onboard, Connectors, Workbooks, Analytics Rules, Hunting Rules, Playbooks) plus folders for script helpers and Az DevOps YAML pipelines. In this README we explain some of the basics for each of them but we encourage you to visit each of the folders for more details on how to use the tools.

## Scripts

Scripts that are used inside the Azure DevOps pipelines to automate the deployment of the different Sentinel components

## Pipelines

YAML files that define the CI/CD pipelines that can be used to automated the deployment of Sentinel components

## Analytics Rules

Definition files containing all the analytics rule alerts to be created in an environment


## Playbooks

Collection of custom playbooks to be added to your Sentinel environment
