
# System Manager

## SSM - Session Manager

- enables to start a *secure shell* access to EC2 or on-prem server instances without SSH
- **better security as port 22 is closed**
- ==the instance must have a SSM Agent running or have an IAM Instance Profile for SSM==

## Run Command

- **enables to execute / run a script or document or a command on multiple instances (EC2 or on-prem)*
- ==The instances must have a SSM Agent or have an IAM Instance Profile for SSM==
- *No need for SSH*
- **==IMP: The command output can be seen in AWS console, or sent to S3 bucket or CloudWatch Logs==**
- **Also notification can be sent to SNS based on command output status**
- **Command can be scheduled to run using EventBridge**

### Extension of Run Command - Patch Manager

- "Run Command" can be used a "Patch Manager"
- To patch or fix any running instance
- on-demand or scheduled

## Automation

- automate EC2 instances or other AWS resource like restart, take EBS snapshot, AMI image backup, etc
- **SSM Runbook**- list of tasks or commands to carry out using **SSM Automation** on the target EC2 instances or AWS resources
- 