# Contribute to community

The Azure DevOps Demo Generator is a service which helps you provision projects. We can accept feedback and changes through Pull Requests, GitHub Issues, or [Email](mailto:AzureDevOpsDemoGenerator@service.microsoft.com) (as appropropriate).  

**TO DO: We need some guidance on code contributions; we should be able to borrow the bulk from other Microsoft open source projects.  **

## Contributing templates
The Azure DevOps Demo Generator now provides the ability to [build custom templates](https://docs.microsoft.com/en-us/azure/devops/demo-gen/build-your-own-template?toc=/azure/devops/demo-gen/toc.json&bc=/azure/devops/demo-gen/breadcrumb/toc.json&view=azure-devops) and [provision projects using that template](https://docs.microsoft.com/en-us/azure/devops/demo-gen/build-your-own-template?toc=/azure/devops/demo-gen/toc.json&bc=/azure/devops/demo-gen/breadcrumb/toc.json&view=azure-devops#provisioning-your-project-from-your-custom-template).  However you can also share your template with the broader user community!

Community-provided templates appear in the project selection Community tab and are used the same as any Microsoft-provided template.  These templates are visually inspected but Microsoft does not offer any guarantees on community templates.

We invite you to generate and share your community templates.

### How to contribute

After [creating](https://docs.microsoft.com/en-us/azure/devops/demo-gen/build-your-own-template?toc=/azure/devops/demo-gen/toc.json&bc=/azure/devops/demo-gen/breadcrumb/toc.json&view=azure-devops) and testing your template, upload the template zip file to any public location (e.g., [Azure Blob Storage](https://docs.microsoft.com/en-us/azure/storage/blobs/storage-quickstart-blobs-portal) or a GitHub repository).

The create a Pull Request on the [**TO DO: Link to the appropriate config file**](), submit an Issue with the template information, or [Email](mailto:AzureDevOpsDemoGenerator@service.microsoft.com) us with the template information.
> NOTE: If you have extensions installed in your organization, the generated template will  reference to all installed extensions in the ```Extensions.json``` [**TO DO: Link to the file extensions file in the repo**](). You can edit this file and keep only the required extensions for the project. If extensions are not required, keep the file empty.

### Template elements
|Keys|Description| 
|-------|-----------|
|**Name**| Name of your template, which will be displayed during template selection |
|**ShortName** | Short name for your template. This should not contain spaces or special characters|
|**TemplateFolder**| Name of your template folder. This should not contain spaces or special characters|
|**Description** | A brief description about the template|
|**Tags**| An array of tags, which should be related to technologies used. Ex: .NetCore, Java, Maven, Docker, K8S, etc. |
| **Icon** | Template icon to display it publicly in the tempalte selection page |
| **Document link** | Document link for user reference|
|||

We will communicate with you once the template has been validated and incorporated.
