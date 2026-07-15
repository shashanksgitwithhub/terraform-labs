<p align="center">
  <img src="https://img.shields.io/badge/Terraform-623CE4?style=for-the-badge&logo=terraform&logoColor=white" />
</p>

# 📘 Day 01 - Terraform Basics

## 🎯 Objective

Learn the fundamentals of Terraform, understand Infrastructure as Code (IaC), and provision the first AWS EC2 instance using Terraform.

---

## 📖 Topics Covered

* What is Infrastructure as Code (IaC)?
* What is Terraform?
* Benefits of Terraform
* Terraform Architecture
* Installing Terraform
* Installing and Configuring AWS CLI
* Creating an IAM User for Terraform
* Terraform Providers
* Terraform Resources
* Writing the first Terraform configuration
* Terraform Workflow
* `terraform init`
* `terraform plan`
* `terraform apply`
* `terraform destroy`

---

## 🛠 Practical Lab

### Step 1: Install Terraform

Verify the installation:

```bash
terraform --version
```

---

### Step 2: Configure AWS CLI

Configure your AWS credentials:

```bash
aws configure
```

Provide:

* AWS Access Key ID
* AWS Secret Access Key
* Default Region
* Output Format

---

### Step 3: Create the First Terraform Configuration

Create a file named:

```text
main.tf
```

Define:

* AWS Provider
* EC2 Resource
* AMI ID
* Instance Type

---

### Step 4: Initialize Terraform

```bash
terraform init
```

This command:

* Downloads the required provider plugins
* Creates the `.terraform` directory
* Generates `.terraform.lock.hcl`

---

### Step 5: Review the Execution Plan

```bash
terraform plan
```

This command previews the infrastructure changes before deployment.

---

### Step 6: Deploy Infrastructure

```bash
terraform apply
```

Terraform creates the EC2 instance in AWS.

---

### Step 7: Verify the Deployment

* Check the AWS Management Console.
* Confirm that the EC2 instance is in the **Running** state.

---

### Step 8: Destroy the Infrastructure

```bash
terraform destroy
```

This removes the EC2 instance and prevents unnecessary AWS charges.

---

## 📂 Files Used

```text
Day-01-Terraform-Basics/
│
├── main.tf
├── README.md
└── .terraform.lock.hcl
```

---

## 📌 Commands Learned

```bash
terraform init
terraform validate
terraform fmt
terraform plan
terraform apply
terraform destroy
terraform show
```

---

## 💡 Key Learnings

* Understood Infrastructure as Code (IaC).
* Learned how Terraform automates cloud infrastructure.
* Configured AWS CLI for Terraform.
* Understood Providers and Resources.
* Learned the Terraform execution workflow.
* Provisioned an EC2 instance using Terraform.
* Destroyed infrastructure to avoid unnecessary cloud costs.

---

## 📸 Screenshots

* Terraform installation<img width="1907" height="1011" alt="Screenshot 2026-07-13 114910" src="https://github.com/user-attachments/assets/6fb1890f-fd7a-4058-b7aa-58e444dac18a" />
  <img width="1920" height="1080" alt="Screenshot 2026-07-13 214806" src="https://github.com/user-attachments/assets/f6dce9d9-cbd7-47ee-80a7-8beae8bd935c" />

* AWS CLI configuration (hide credentials)<img width="1920" height="1080" alt="Screenshot 2026-07-13 222206" src="https://github.com/user-attachments/assets/69084829-ded8-4ff8-82fa-7929dd96757e" />

* `terraform init`<img width="1907" height="1009" alt="Screenshot 2026-07-13 231748" src="https://github.com/user-attachments/assets/4fcaf68e-c253-4987-88b4-0e88001da816" />

* `terraform plan`<img width="1907" height="1011" alt="Screenshot 2026-07-13 231810" src="https://github.com/user-attachments/assets/c110fa3d-f059-4946-a858-f41ddfdbb48a" />
  <img width="1907" height="1011" alt="Screenshot 2026-07-13 231826" src="https://github.com/user-attachments/assets/d59dbf5a-48e6-45a2-9516-189b17f3a8e0" />
  <img width="1907" height="1008" alt="Screenshot 2026-07-13 231833" src="https://github.com/user-attachments/assets/80d48261-b5c8-423e-ae2d-40230449e900" />
  <img width="1907" height="1015" alt="Screenshot 2026-07-13 231849" src="https://github.com/user-attachments/assets/99500850-0a52-489a-af53-347eace9fa5b" />

* `terraform apply`<img width="1907" height="1012" alt="Screenshot 2026-07-13 231910" src="https://github.com/user-attachments/assets/6b8dc50c-6cea-4d30-bc5e-a73f1ed4ae3e" />
  <img width="1907" height="1010" alt="Screenshot 2026-07-13 231938" src="https://github.com/user-attachments/assets/7780cfe5-1ae1-45fe-bdfe-856887fa042a" />

* EC2 instance in AWS Console<img width="1907" height="1009" alt="Screenshot 2026-07-13 231718" src="https://github.com/user-attachments/assets/5b56f6a4-fbc5-4044-af09-1b506c314fec" />

* `terraform destroy`<img width="1907" height="1010" alt="Screenshot 2026-07-13 232103" src="https://github.com/user-attachments/assets/8af28f8c-2901-4c5b-8728-10a4b89a8a58" />
  <img width="1907" height="1011" alt="Screenshot 2026-07-13 232111" src="https://github.com/user-attachments/assets/8d581bd6-4149-414a-b5c5-27b1ebdf1d7a" />
  <img width="1907" height="1013" alt="Screenshot 2026-07-13 232128" src="https://github.com/user-attachments/assets/6ec5d892-5dad-443a-a5f7-367f651fafa4" />
  <img width="1907" height="1009" alt="Screenshot 2026-07-13 232139" src="https://github.com/user-attachments/assets/27cb2381-1d58-4afa-9a8e-822e22113c69" />

---

## ✅ Outcome

Successfully provisioned and removed an AWS EC2 instance using Terraform while understanding the complete Infrastructure as Code workflow.
