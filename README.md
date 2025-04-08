# Terraform
Terraform docks and notes
# https://cloudchamp.notion.site/Terraform-Scenario-based-Interview-Questions-bce29cb359b243b4a1ab3191418bfaab
# chatgpt answers

# https://chatgpt.com/share/673bfbe8-2a28-8006-bab4-6cd3d4707188

## Topic to learn 
1. terrafom intialisation and configuration
2. providers and multiprovider
3. What is alias in provider
4. versions ( cli, provider, module )
5. what is the binary in terrform version
6. what is Terraform Registry.
7. terraform file straucture
8. what is .terraform.lock.hcl  # Dependency lock file
9. veriables
10. Diff betn veriables.tf and terraform.tfvars
11. output file 
12. state file and statefile management
13. How to Unlock Terraform State? If in any condition it get lock. -  terraform force-unlock <LOCK_ID>
14. How to Unlock Terraform State in Production (via CI/CD controlled workflows)
15. modules 
16. provisioners
17. data source 
18. workspaces 
19. functions 
20. lifecycle rules 
21. loop, count and for_each
22. Dynamic blocks 
23. secrets and secreats management 
24. what is terragraunt 
25. debugging and validations 
26. how to upgrade terraform 
27. template 
28. terraform import 
29. user_data in terraform
30. depends on metadata
    
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
