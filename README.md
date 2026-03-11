# Terraform Associate 003
---
> #### Q1: You are using the Vault userpass auth method mounted at auth/userpass.How do you create a new user named "sally" with password "h0wN0wB4r0wnC0w"? This new user will need the power-users policy.
Which of the following commands will allow you to see the help file for the `init` subcommand?  
*(Select the three best answers.)*
- [ ] `terraform -help init`
- [ ] `terraform init`
- [ ] `terraform init -h`
- [ ] `terraform --h init`
- [ ] `terraform help -init`
<details>
  <summary> Answer </summary>
  
  `terraform --h init,terraform init -h,terraform -help init` 
  
</details>

> #### Q2: True or False?

Community-based provider plugins are downloaded automatically when using the `terraform init` command.

- [ ] True
- [ ] False

<details>
  <summary> Answer </summary>
  
  True
  
</details>

#### Q3: HCL supports user-defined functions.

- [ ] True
- [ ] False
<details>
  <summary> Answer </summary>
  
  False
  
</details>

#### Q4: What is the name of the Terraform program that you run locally?

- [ ] `terraform Core`
- [ ] `terraform init`
- [ ] `terraform Code`
- [ ] `terraform Local`

<details>
  <summary> Answer </summary>
  
  Terraform Core
  
</details>

#### Q5: What is **NOT** a core IaC principle when it comes to creating an efficient automated environment?

- [ ] Embracing the ever-evolving design
- [ ] Use of versioned infrastructure
- [ ] Idempotence setup
- [ ] Use of self-describing infrastructure

<details>
  <summary> Answer </summary>
  
    "Embracing the ever-evolving design"
  
</details>

#### Q6: What does the acronym IaC stand for?

- [ ] Integrated Application Code
- [ ] Internet and Connectivity
- [ ] Infrastructure as Code
- [ ] Interactive Application Component

<details>
  <summary> Answer </summary>
  
  "Infrastructure as Code"
  
</details>

#### Q7: What does the "Plan" command in Terraform do?

- [ ] It creates an execution schedule
- [ ] It plans out your next steps
- [ ] It acts like a dry run for your code
- [ ] None of the above

<details>
  <summary> Answer </summary>
  
  "It acts like a dry run for your code"
  
</details>

#### Q8: What are the advantages of using Terraform?

- [ ] To replicate and modify infrastructure quickly
- [ ] To manage infrastructure on multiple cloud platforms
- [ ] To track resource changes throughout deployments
- [ ] All of the above

<details>
  <summary> Answer </summary>
  
  "All of the above"
  
</details>

#### Q9 Which of the following is the proper workflow for deploying new infrastructure using Terraform?

- [ ] Write the Terraform code > `terraform init` > `terraform plan` > `terraform apply`
- [ ] Import the current infrastructure to the state file, update the code, and run `terraform apply`
- [ ] `terraform init` > `terraform apply` > `terraform plan` > `terraform fmt`
- [ ] Write the Terraform code > `terraform show` > `terraform apply`

<details>
  <summary> Answer </summary>
  
  "Write the Terraform code > terraform init > terraform plan > terraform apply"
  
</details>

#### Q10:  
Which of the following languages does Terraform support? *(Select the two best answers.)*

- [ ] HCL
- [ ] JavaScript
- [ ] XML
- [ ] JSON
- [ ] Plaintext

<details>
  <summary> Answer </summary>
  
  "HCL" and "JSON"
  
</details>

#### Q11: Which of the following is not a key principle of IaC?

- [ ] Golden images
- [ ] Idempotence
- [ ] Self-describing infrastructure
- [ ] Versioned infrastructure

<details>
  <summary> Answer </summary>
  
  "Golden images"
  
</details>
