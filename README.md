# Terraform
Terraform docks and notes
# https://cloudchamp.notion.site/Terraform-Scenario-based-Interview-Questions-bce29cb359b243b4a1ab3191418bfaab
# chatgpt answers

# https://chatgpt.com/share/673bfbe8-2a28-8006-bab4-6cd3d4707188

## Topic to learn 
1. terrafom intialisation and configuration
2. providers and multiprovider 
Q. What is alias in provider
3. versions ( cli, provider, module )
Q  what is the binary in terrform version
Q  what is Terraform Registry.
4. terraform file straucture 
Q  what is .terraform.lock.hcl  # Dependency lock file
5. veriables
Q  Diff betn veriables.tf and terraform.tfvars
6. output file 
7. state file and statefile management
8. How to Unlock Terraform State? If in any condition it get lock. -  terraform force-unlock <LOCK_ID>
9. modules 
10. provisioners
11. data source 
12. workspaces 
13. functions 
14. lifecycle rules 
15. loop, count and for_each
16. Dynamic blocks 
17. secrets and secreats management 
18. what is terragraunt 
19. debugging and validations 
20. how to upgrade terraform 
21. template 
22. terraform import 
23. user_data in terraform
24. depends on metadata
    
```yaml
terraform-eks/
├── modules/
│   ├── vpc/
│   │   ├── main.tf
│   │   ├── variables.tf
│   │   ├── outputs.tf
│   ├── eks/
│   │   ├── main.tf
│   │   ├── variables.tf
│   │   ├── outputs.tf
│   │   ├── data.tf
│   ├── s3-backend/
│   │   ├── backend.tf
├── environments/
│   ├── dev/
│   │   ├── main.tf
│   │   ├── terraform.tfvars
│   ├── prod/
│   │   ├── main.tf
│   │   ├── terraform.tfvars
├── providers.tf
├── variables.tf
├── backend.tf
├── outputs.tf
├── versions.tf

```
