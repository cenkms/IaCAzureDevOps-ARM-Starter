# IaC - Azure DevOps - ARM
# Infrastructure as Code with Azure DevOps using ARM

## Challenge 5 - Deploy a VM with VNet
---

## Challenge
- Use your parameters files for different environments
- Start using Build pipeline for creating an artifact - Release pipeline for releasing
- Different environments storage should be different SKU
- ARM template should be validated.

## Success Criteria
- Make sure in build step you create the artifact
- Release pipeline should be there deploying two different env.
- Make sure enabled CI and CD triggers - when code deployed it should deploy
- All changes should be PR and merge when deploying to second environments someone should approve before deploy
- If your repos are in a different folder, make sure the one that runs is the one you changed

## References
- https://docs.microsoft.com/en-us/azure/devops/pipelines/release/
- https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/template-tutorial-use-parameter-file
- https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/deployment-modes

## Tips
- There could be two environments right now dev, qa
- Make sure you add Environment in the name

[Next: Challenge 6](../Challenge6)
