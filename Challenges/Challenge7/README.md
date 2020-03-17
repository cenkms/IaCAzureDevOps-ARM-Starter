# IaC - Azure DevOps - ARM
# Infrastructure as Code with Azure DevOps using ARM

## Challenge 7 - Deploying a VM with VNet - Nested 
---

## Challenge
- Same template but modularize VM and Vnet deployment
- Dependency is important,
- Make sure you deploy Public IP with NSG - don't forget the dependency tree.
- Output the Public IP address so that we can RDP.

## Success Criteria
- There should be two, only two deployments in the main file Networking and VM
- How to reference the other template?

## References
- https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/linked-templates