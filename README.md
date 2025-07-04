# Cloud Infrastructure Simulation Project (Terraform + AWS)

This project simulates infrastructure provisioning using Terraform and mock AWS credentials, designed to demonstrate Infrastructure-as-Code (IaC) capabilities in a safe, cost-free environment. As a fresher, I created this project to showcase my understanding of cloud setup, configuration, and automation using real-world tools.



# Objective

Provision an AWS EC2 instance using Terraform to simulate infrastructure deployment. The goal is to gain hands-on experience with Terraform scripting, cloud configuration, and deployment planning — without using a real AWS account.



# Technologies Used

| Category               | Tools Used              |
|------------------------|-------------------------|
| Infrastructure as Code | Terraform               |
| Cloud Platform         | AWS (simulated)         |
| Language               | HCL (HashiCorp Config)  |
| Editor / CLI           | VS Code, PowerShell     |



# Infrastructure Details

- Resource: AWS EC2 instance
- AMI: `ami-0c02fb55956c7d316` (Amazon Linux 2)
- Instance Type: `t2.micro`
- Region: `ap-south-1`
- Tag: `Name = CloudInfraDemo`



# Actions Performed

- `terraform init` to initialize provider and configuration
- `terraform plan` to preview infrastructure changes
- No `terraform apply` to avoid real cloud charges
- Screenshot captured of the Terraform plan output



# Screenshot

| Terraform Plan Output |
|------------------------|
|[Terraform Plan Output](./terraform_plan_output(1).png) |
|[Terraform Plan Output](./terraform_plan_output(2).png) |
|[Terraform Plan Output](./terraform_plan_output(3).png) |



# Folder Structure

cloud-infra-demo/
- main.tf # Terraform configuration file
- terraform-plan-output.png # Screenshot of plan
- README.md # Project description


# How to Run (Locally)

You can simulate this project on your system by following these steps:

```bash
terraform init
terraform plan

# No AWS credentials or paid services are needed. This is a simulation for learning/demo purposes only.



# Skills Demonstrated

- Simulated cloud infrastructure using Terraform and AWS (IaC)
- Wrote and managed HCL configuration files to provision EC2
- Practiced scaling, tagging, and automated resource definition
- Applied configuration management and scripting logic
- Demonstrated understanding of deployment planning and resilience
- Structured project using version control and modular setup
- Documented end-to-end infrastructure flow with screenshot and README



# Transparency Note

- This is a simulation project created independently for learning and portfolio building. It does not use real AWS billing or deploy live infrastructure. All cloud operations are demonstrated locally using Terraform’s planning phase. 



# About Me
I'm a BTech Information Technology graduate with a strong interest in cloud infrastructure, DevOps, and automation. I created this project as part of my portfolio to showcase my readiness for real-world engineering roles.