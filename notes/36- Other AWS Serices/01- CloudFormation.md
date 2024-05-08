
# CloudFormation

- Infra as a code
- The AWS stack can be provisioned using YAML file. Mostly all AWS service can be provisioned and configured using this **declarative syntax**

## CloudFormation Service Role

- an **IAM role that allows CloudFormation** to Create/Update/Delete resources
- can be created or modified, limiting the CloudFormation's Stack capabilities
-

## CloudFormation iam:PassRole

- **IAM Permission** applied to users
- enables them to create/update/delete resource through CloudFormation, *despite not having direct permissions to do so manually on each resource type*
- **mandatory for user to have the iam:PassRole permission**
- 