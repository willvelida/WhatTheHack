# Challenge 02 - Deploy your integration environment


[<Previous Challenge](./Challenge-01.md) - **[Home](../readme.md)** - [Next Challenge>](./Challenge-03.md)

## Pre-requisites

- You should have completed Challenge 01

## Introduction

Now that you've created your Bicep templates, you would like to create a CI/CD pipeline to deploy these templates to your Azure environment. 

## Description
As a cloud engineer, you would like to be able create a CI/CD pipeline to perform automated deployment of integration environment.

## Success Criteria

You should be able to:
1. Create a repository and upload your Bicep templates to the main branch.
1. Create a CI/CD pipeline using either GitHub Actions or Azure DevOps.
1. Deploy your environment using the Bicep templates that you created from Challenge 01.


## Learning Resources

- [Quickstart for GitHub Actions](https://docs.github.com/en/actions/quickstart)
- [Quickstart: Deploy Bicep files by using GitHub Actions](https://docs.microsoft.com/en-us/azure/azure-resource-manager/bicep/deploy-github-actions?tabs=CLI)
- [Quickstart: Integrate Bicep with Azure Pipelines](https://docs.microsoft.com/en-us/azure/azure-resource-manager/bicep/add-template-to-azure-pipelines?tabs=CLI)
- [Deploy Azure resources by using Bicep and GitHub Actions](https://docs.microsoft.com/en-us/learn/paths/bicep-github-actions/)
- [Deploy Azure resources by using Bicep and Azure Pipelines](https://docs.microsoft.com/en-gb/learn/paths/bicep-azure-pipelines/)


## Tips
- You can choose to use either GitHub Actions or Azure DevOps Pipelines for this exercise.
- If using GitHub actions, a sample workflow can be found at [/Resources/Challenge-02](./Resources/Challenge-02).
- If using Azure Pipelines, a sample YAML pipeline can be found at [/Resources/Challenge-02](./Resources/Challenge-02).

## Advanced Challenges

- In your GitHub Actions workflow or Azure DevOps pipeline, rather than having a single task that deploys your Bicep template straight to Azure, extend it to include some or all of the suggested tasks:
    - Linting and validating your Bicep code.
    - Adding a preview job to see what will be deployed to Azure and an approval step before deploying your template.
    - Adding a test job to verify that your template deployed correctly.
