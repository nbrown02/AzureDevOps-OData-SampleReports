# Template Reports for Azure Boards (Azure DevOps / Server / TFS)
## What is it?
A collection of Power BI templates for all the [sample Azure Boards OData Power BI reports](https://docs.microsoft.com/en-us/azure/devops/report/powerbi/sample-odata-overview?view=azure-devops) provided by Microsoft for you to visualise your Azure DevOps Boards (or Azure DevOps Server/TFS) data. This way you can save time, download the respective template(s), enter your organization and project details then visualize your data. 

## Prerequisites
* [Make sure you have the latest version of Power BI Desktop](https://aka.ms/pbiSingleInstaller)
* Download your chosen template(s):

## Full list of report templates for Azure Boards

* [Bug Trend](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Boards/Bug%20Trend.pbit) - for a given set of open Bugs, the number of Bugs in each State, trended over a period of time. 
* [Cumulative Flow Diagram (CFD)](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Boards/Cumulative%20Flow%20Diagram.pbit) - on any particular data, the number of work items in a particular column on the kanban board.
* [Feature Progress](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Boards/Feature%20Progress.pbit) - displays progress of Features based on completed child items. Visualized in both count of items and overall percentage complete.
* [Lead/Cycle Time](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Boards/Lead%20-%20Cycle%20Time.pbit) - displays the average lead time (Created -> Done) or average cycle time (In Progress -> Done) for a given set of items.
* [Open Bugs](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Boards/Open%20Bugs.pbit) - displays, for a given set of open Bugs, a breakdown by State and Assigned To fields.
* [Rollup](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Boards/Rollup.pbit) - displays the rollup count of User Stories/PBIs and total Story Points for a given set of Features.
* [Sprint Burndown](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Boards/Sprint%20Burndown.pbit) - display the current sprint's burndown of User Stories/PBIs in both count of items and sum of story points. 
* [Work Items With Direct Links](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Boards/Work%20Items%20with%20Direct%20Links.pbit) - a table with a detailed list of work items and their associated links.

## Connectivity
* Open the .pbit file
* Select http/https (only choose http if your Azure DevOps Server is HTTP)
* Add the Analytics / Azure DevOps Server URL - for Azure DevOps services enter 'analytics.dev.azure.com' / for Azure DevOps Server enter your server details
* Add your organization and project name

Don't confuse the team name with the project name, a common mistake. If the URL you use is "http://dev.azure.com/Microsoft-UK/AzureDevOpsTeam/Database", then Microsoft-UK is the Organization Name, AzureDevOpsTeam is the Project name, Database is the team name.

* It should then look something like this:

Azure DevOps Services:
![alt text](https://raw.githubusercontent.com/nbrown02/AzureDevOps-OData-SampleReports/main/Screenshots/Boards1.png)

Azure DevOps Server:
![alt text](https://raw.githubusercontent.com/nbrown02/AzureDevOps-OData-SampleReports/main/Screenshots/Boards2.png)

Note - certain templates may ask for additional information before loading, for example:
![alt text](https://raw.githubusercontent.com/nbrown02/AzureDevOps-OData-SampleReports/main/Screenshots/Boards3.png)

* Hit 'Load' 
* If you are prompted for a login, you can choose:
  - 'Organizational' and enter your Organization email/password (if required) and sign in
  - 'Basic' and use a Personal Access Token (PAT) to login, entering it in the password field (user can be left as blank - make sure it has 'Read' access to Analytics)

  ![alt text](https://docs.microsoft.com/en-us/azure/devops/report/powerbi/media/authentication-7.png?view=azure-devops)

* Once signed in hit 'Load' and wait for your charts to populate!
