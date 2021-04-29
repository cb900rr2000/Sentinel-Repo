[![Build Status](https://dev.azure.com/soricloud/SentinelAsCode/_apis/build/status/alertRulesCICD.yml?branchName=master)](https://dev.azure.com/soricloud/SentinelAsCode/_build/latest?definitionId=21&branchName=master)

# Azure Sentinel as Code

The purpose of this project is to provide tools to enable automatic deployment of Azure Sentinel environments through Azure DevOps.

A blog post explaining more about this project is available at [Deploying and Managing Azure Sentinel as code](https://techcommunity.microsoft.com/t5/azure-sentinel/deploying-and-managing-azure-sentinel-as-code/ba-p/1131928)

The project has several folders for each of the different Sentinel components that can be configured (Onboard, Connectors, Workbooks, Analytics Rules, Hunting Rules, Playbooks) plus folders for script helpers and Az DevOps YAML pipelines. In this README we explain some of the basics for each of them but we encourage you to visit each of the folders for more details on how to use the tools.

## Scripts

Scripts that are used inside the Azure DevOps pipelines to automate the deployment of the different Sentinel components

## Pipelines

YAML files that define the CI/CD pipelines that can be used to automated the deployment of Sentinel components

## Workbooks

Collection of custom workbooks in JSON format that can be leveraged to add additional visibility into environments

## Analytics Rules

Definition files containing all the analytics rule alerts to be created in an environment

## Playbooks

Collection of custom playbooks to be added to your Sentinel environment
