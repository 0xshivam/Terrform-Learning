ref: https://k21academy.com/terraform-iac/terraform-beginners-guide/
### Terrafrom Lifecycle
     
     TFconfigFile --> init --> plan --> validate --> apply --> destroy

### Terraform Core Concepts

- **Variables**:  Used to pass values into (`input`) or get values out (`output`) of Terraform configs.

- **Providers**:  Connect Terraform to cloud platforms like AWS, Azure, or GCP.
  
- **Modules**:  A folder with Terraform files. Every project has a root module, and you can create reusable ones.

- **State**:  Terraform keeps track of created resources in a `.tfstate` file.

- **Resources**:  Cloud services (like EC2, S3, etc.) that Terraform creates and manages.

- **Data Source**:  Lets you read data from outside resources without managing them.

### Terraform Configuration Files


- **Configuration file (`*.tf`)** – Declares provider, resources, and their settings.
- **Variable declaration file (`variables.tf`)** – Defines input variables.
- **Variable definition file (`terraform.tfvars`)** – Assigns values to input variables.
- **State file (`terraform.tfstate`)** – Stores infrastructure state after Terraform runs.

## Terraform commands

`terraform --help

