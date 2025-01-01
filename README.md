# HTTP Service Deployment with Terraform  

## Project Overview  
This project automates the deployment of an HTTP service on AWS using Terraform. The service is built with Flask and provides a REST API to interact with an S3 bucket for uploading, retrieving, and listing files.  

---

## Key Features  
- **Automated Infrastructure**: Provisions S3, EC2, and IAM resources using Terraform.  
- **Flask API Service**: Includes endpoints to upload files, list bucket contents, and download files.  
- **Scalable Design**: Configured for easy adaptation and scaling.  

---

## Prerequisites  
- **Terraform** installed.  
- **AWS CLI** configured with valid credentials.  
- **Python 3** installed (for local or EC2 deployment).  

---

## File Structure  
- **`main.tf`**: Core Terraform configurations for AWS resources.  
- **`variables.tf`**: Input variables for customization.  
- **`app.py`**: Python script implementing the Flask API.  

---

## Deployment Steps  

### 1. Prepare the Environment  
Place all project files (`main.tf`, `variables.tf`, `outputs.tf`, `app.py`) in a single directory.  

### 2. Initialize Terraform  
Run:  
```bash  
terraform init  
