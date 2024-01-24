# Azure Infrastructure Deployment with Terraform

## Overview

This Git project is focused on deploying virtual machines (VMs), networks, and other infrastructure components using Terraform on Microsoft Azure. Terraform allows us to define and provision our infrastructure as code, making it scalable, version-controlled, and easily reproducible.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following prerequisites installed:

- [Terraform](https://www.terraform.io/downloads.html): Install Terraform on your local machine.
- Azure Subscription: Obtain an active Azure subscription and configure Azure CLI with appropriate credentials.

### Project Structure

The project structure is organized as follows:

- **`main.tf`**: Defines the main configuration for the infrastructure.
- **`variables.tf`**: Contains variable declarations used in the main configuration.
- **`providers.tf`**: Specifies the providers, including Azure, used in the project.
- **`outputs.tf`**: Defines the output values from the infrastructure deployment.
- **`ssh.tf`**: Configures SSH settings for VMs.
- **`azure-vms`**: Additional files or folders specific to Azure VM configurations.
- **`.terraform`**: Directory containing Terraform provider plugins and other internal files.

## Usage

   Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/your-terraform-azure-project.git
   cd your-terraform-azure-project
   terraform init
   terraform plan
   terraform apply 
   ```
  Cleanup
  To destroy the deployed infrastructure:
  terraform destroy


  Contributions
  Contributions to improve and extend this project are welcome. Feel free to open issues, submit pull requests, or provide feedback.