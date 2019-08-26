# Contribute to community

The Azure DevOps Demo Generator is a service which helps you provision projects. Now we have enabled feature to [build custom template](https://docs.microsoft.com/en-us/azure/devops/demo-gen/build-your-own-template?toc=/azure/devops/demo-gen/toc.json&bc=/azure/devops/demo-gen/breadcrumb/toc.json&view=azure-devops) and [provision your project](https://docs.microsoft.com/en-us/azure/devops/demo-gen/build-your-own-template?toc=/azure/devops/demo-gen/toc.json&bc=/azure/devops/demo-gen/breadcrumb/toc.json&view=azure-devops#provisioning-your-project-from-your-custom-template) using generated template, also you can share your template to community.

## How to contribute

Once you successfully generate and test your template, you can share it with community. This can be done in three ways.

1.  Create a pull request to [Azure DevOps Demo Generator](https://github.com/microsoft/AzureDevOpsDemoGenerator/)
1. Place the template zip file in any public repository and share the link in [Email](mailto:AzureDevOpsDemoGenerator@service.microsoft.com)
1. Share the template directly through [Email](mailto:AzureDevOpsDemoGenerator@service.microsoft.com)

    > If you have extensions installed in your organization, tempalte would be generated along with reference to all installed extensions in the ```Extensions.json``` file. You can edit this file and keep only the required extensions for the project. If extensions are not required, keep the file empty.

## Your template must contian following elements
|Keys|Description| 
|-------|-----------|
|**Name**| Name of your template, which will be displayed in the text box upon template selection |
|**ShortName** | Short name for your template. This should not contain any space or special characters|
|**TemplateFolder**| Name of your tempalte folder. This should not contain any space or special characters|
|**Description** | A brief description about the template|
|**Tags**| An array of tags, which should be related to technologies used. Ex: .NetCore, Java, Maven, Docker, K8S, etc. |
| **Icon** | Templte icon to display it publicly in the tempalte selection page |
| **Document link** | Document link for user reference|
|||

We will communicate via Email once the template validated successfully.