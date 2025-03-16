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
14. modules 
15. provisioners
16. data source 
17. workspaces 
18. functions 
19. lifecycle rules 
20. loop, count and for_each
21. Dynamic blocks 
22. secrets and secreats management 
23. what is terragraunt 
24. debugging and validations 
25. how to upgrade terraform 
26. template 
27. terraform import 
28. user_data in terraform
29. depends on metadata
    
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
