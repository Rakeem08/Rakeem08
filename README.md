# Rakeem Brewington

**AWS Cloud Engineering | DevOps | Infrastructure Automation**

I'm an AWS cloud and DevOps engineer in the Orlando, Florida area focused on building reliable, secure, and maintainable systems. My hands-on portfolio covers infrastructure as code, container orchestration, serverless applications, CI/CD, monitoring, and troubleshooting.

I also bring more than 15 years of team and operations leadership—coordinating people, resolving problems under deadlines, and communicating clearly across stakeholders. I'm interested in junior cloud engineering, cloud operations, DevOps, and site reliability engineering opportunities.

[Portfolio & project walkthroughs](https://rakeembrewington.com/) · [GitHub projects](https://github.com/Rakeem08?tab=repositories)


## Technical toolkit

- Cloud: AWS EC2, S3, IAM, VPC, ECR, ECS Fargate, EKS, Lambda, API Gateway, DynamoDB, SQS, SNS, CloudWatch
- Infrastructure & automation: Terraform, Ansible, Linux, Bash, Python
- Containers & delivery: Docker, Kubernetes, Helm, Jenkins, GitHub Actions, Argo CD, Git
- Operations: Health checks, autoscaling, logging, alerts, runbooks, incident troubleshooting

## Featured cloud projects


### 1. [Serverless Order Processing on AWS](https://github.com/Rakeem08/aws-serverless-order-processing)

**Business scenario:** An order service needs to handle retries, traffic bursts, and processing failures without losing visibility into order status.

Built an authenticated API with API Gateway, Cognito, Python Lambda, DynamoDB, SQS, and S3. Implemented idempotent order handling, a dead-letter queue, CloudWatch alarms, SNS notifications, and an operational failure drill. Infrastructure is defined with Terraform.


**Reliability focus:** Failure isolation, monitoring, asynchronous processing, and documented response procedures.

### 2. [Kubernetes Deployment & GitOps on AWS EKS](https://github.com/Rakeem08/aws-eks-kubernetes-gitops)

**Business scenario:** A growing application needs repeatable deployments and the ability to scale with demand.

Defined EKS infrastructure with Terraform and a Dockerized Node.js deployment with Helm. The main workflow uses Jenkins for direct Helm delivery; a separate GitOps branch contains GitHub Actions image publication and Argo CD reconciliation configuration. See the project README for setup requirements and verification limits.


**Reliability focus:** Pod health, capacity scaling, cluster troubleshooting, and consistent releases.

### 3. [Containerized Application Delivery on ECS](https://github.com/Rakeem08/aws-ecs-containerized-app-cicd)

**Business scenario:** A two-service application needs consistent deployments with less manual work.

Containerized React and Express services using Docker, published images to Amazon ECR, and deployed them on ECS Fargate behind an Application Load Balancer. Automated delivery with Jenkins and provisioned AWS infrastructure using Terraform.


**Operations focus:** Health checks, autoscaling, CI/CD, and API routing troubleshooting.

### 4. [Terraform & Ansible Infrastructure Automation](https://github.com/Rakeem08/terraform-ansible-aws-automation)

**Business scenario:** Provisioning and configuring web servers manually creates inconsistency and slows recovery.

Used Terraform to provision EC2, IAM, networking, and S3 resources, then Ansible to configure Nginx and validate HTTP responses. Documented operational steps and cleaned up resources to manage cloud costs.


**Operations focus:** Repeatable provisioning, Linux configuration, verification, and cost awareness.

## Certifications & development

- CompTIA Security+ (2026)
- Google Cybersecurity Professional Certificate
- AWS Cloud Engineering training — Apex Infrastructure (2026)

## How I approach engineering

1. Understand the business need: reliability, security, scalability, and cost.
2. Automate repeatable work: infrastructure and deployments belong in version control.
3. Make failures visible: metrics, logs, alerts, and meaningful health checks.
4. Document decisions: what failed, why it happened, and how to improve the system.
Explore the project READMEs for architecture diagrams, implementation details, and troubleshooting notes.

Website: [rakeembrewington.com](https://rakeembrewington.com/)

Contact: [RakeemBrewington8@gmail.com](mailto:RakeemBrewington8@gmail.com)
