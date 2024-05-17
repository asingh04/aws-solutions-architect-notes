

# Other Services


# Cost Explorer

- Visualize, understand, report, analyse, forecast and manage AWS cost over time
- **AWS Compute Optimizer / Resource Optimizer** recommends optimal AWS Compute resources for your workloads to reduce costs and improve performance by using machine learning to analyze historical utilization metrics.

# AWS Trusted Advisor

- provides assessment of your AWS account
- Analysis your account and provides feedback on these scopes:
	1. Cost Optimization
	2. Performance
	3. Security
	4. Fault Tolerance
	5. Service Limit
	6. Operational Exercise


# AWS Batch

- AWS service to execute parallel jobs
- it automatically provisions the EC2 instance required, and schedules the jobs
- Batch jobs can be defined as Docker Images and run on ECS (EC2 mode)

# Batch vs Lambda


| **AWS Batch**                                                        | AWS Lambda                 |
| -------------------------------------------------------------------- | -------------------------- |
| no time limit                                                        | 15mins time limit          |
| no limits, defined by type of EC2 instance                           | limited memory and runtime |
| supports any programming language that can be packed in docker image | supports limited languages |


# AppFlow

- helps in securely transfer data between SaaS applications and AWS resources
- EG: **Source**: Salesforce, **Destination:** S3 bucket

- Can be scheduled, filtering of data, encrypted
- 




