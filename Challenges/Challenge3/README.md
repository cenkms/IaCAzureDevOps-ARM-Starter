# IaC - Azure DevOps - ARM
# Infrastructure as Code with Azure DevOps using ARM

## Challenge 3 - Changing code - adding Parameters (Implementing CI)
---

## Challenge
- Make sure before you change anything in the code
    - Create a new branch
    - Create a PR from that branch to master
    - Add at least two people as Reviewer
        - While you are there; update the master branch policy to have at least two reviewers should approve
        - And the requestor shouldn't approve their changes.
- Add SKU parameter as a list of options - don't forget to define as default!
- Add a parameter file, follow the naming rules.

## Success Criteria
- There should be closed PR.
    - At least two people approved.
- Master Branch policy should be updated.
- ARM template should now have SKU parameter and list of accepted values.
- Parameter file should be present as suggested name and default value.
- Using variables and adding uniqueString is a bonus!


## References
- https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/template-tutorial-add-parameters
- https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/template-tutorial-add-functions
- https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/template-tutorial-use-parameter-file
- https://docs.microsoft.com/en-us/azure/devops/repos/git/pullrequest


## Tips
- [About Pull Request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests)
- Have you heard template functions?
- https://samcogan.com/do-more-with-arm-templates-using-functions/