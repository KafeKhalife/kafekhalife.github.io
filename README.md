# Welcome to Kafe Khalife :coffee:
### The perfect place to pick up some coffee, containers, and kubernetes! 


![img](https://github.com/KafeKhalife/kafekhalife.github.io/blob/main/demo/TitlePage.png)   

:sparkles: Thank you all who attended our GitHub Talk on Containerized Deployments for enterprises with Actions & Packages! :sparkles:


##    
#### :rocket: Follow up:
- Check out all **automation workflows** we created under the `.github/workflows/<workflowname>`. 
- Want to see policies in action? Check this **[active pull request](https://github.com/KafeKhalife/kafekhalife.github.io/pull/9) - with branch protections rules** set up to block the merge to the `main` branch unless all the status checks pass, and another team member approves my pull request.

#### :bulb: Here are links to find some of the resources mentioned during the session:
- The DevOps Hub - [github.com/learn/devops](github.com/learn/devops)
- [Actions developed (and standardiazed) by Azure](https://github.com/Azure/actions)
- [GitHub Roadmap](https://github.com/github/roadmap/projects/1)
- [Containerized Deployment slide deck](https://github.com/KafeKhalife/kafekhalife.github.io/blob/main/demo/GitHub_Talk_10_22_20%20-%20Containerized_Deployments_with_Actions%26Packages.pdf)


#### :mag: NOTE:  
_For those that joined the live session or are watching the recording, there was a typo that caused the Azure WebApp Deployment to fail. 
In the `azure_web_deploy.yml` workflow, I fixed the issue by updating the environment variable reference to be: `$${{ env.IMG_URL }}`. 
Check out the latest commit to see the fix!_

