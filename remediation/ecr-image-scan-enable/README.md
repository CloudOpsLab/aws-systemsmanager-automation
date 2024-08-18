# ECR image scan enable

## What is this?

This is a runbook for enabling image scan when the image is pushed to the ECR repository.
ECR image scan can help you to identify software vulnerabilities in your container images.

## cloudformation.yml

This CloudFormation template creates a AWS Automation function that enable ECR image scan automatically.
It contains Config rule to trigger the Automation function when not ECR image scan is enabled.
