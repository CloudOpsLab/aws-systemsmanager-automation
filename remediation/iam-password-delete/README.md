# IAM password delete

## What is this?

This is a runbook for deleting IAM users' passwords.
IAM users' password will be used to authenticate to the AWS Management Console.
If your organization uses SSO, you may want to delete IAM users' passwords to prevent unauthorized access to the AWS Management Console.

## cloudformation.yml

This CloudFormation template creates a AWS Automation function that deletes IAM users' passwords.
It contains CloudTrail event pattern to trigger the Automation function when a password is created and IAM role for the Automation function.
