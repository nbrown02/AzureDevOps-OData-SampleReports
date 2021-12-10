# Template Reports for Azure Boards (Azure DevOps / Server / TFS)
### What is it?
A collection of Power BI templates for all the [sample Azure Boards OData Power BI reports](https://docs.microsoft.com/en-us/azure/devops/report/powerbi/sample-odata-overview?view=azure-devops) provided by Microsoft for you to visualise your Azure DevOps Boards (or Azure DevOps Server/TFS) data. This way you can save time, download the respective template(s), enter your organization and project details then visualize your data. 

### Prerequisites
* [Make sure you have the latest version of Power BI Desktop](https://aka.ms/pbiSingleInstaller)
* Download your chosen template(s):

## Full list of sample reports for Azure Boards

* Bug Trend - for a given set of open Bugs, the number of Bugs in each State, trended over a period of time. 
* Cumulative Flow Diagram - on any particular data, the number of work items in a particular column on the kanban board.
* Feature Progress - displays progress of Features based on completed child items. Visualized in both count of items and overall percentage complete.
* Lead/Cycle Time - displays the average lead time (Created -> Done) or average cycle time (In Progress -> Done) for a given set of items.
* Open Bugs - displays, for a given set of open Bugs, a breakdown by State and Assigned To fields.
* Rollup - displays the rollup count of User Stories/PBIs and total Story Points for a given set of Features.
* Sprint Burndown - display the current sprint's burndown of User Stories/PBIs in both count of items and sum of story points. 
* Work Items and Direct Links - a table with a detailed list of work items and their associated links.

### Connectivity
* Open the .pbit file
* Add your organization and project name

Don't confuse the team name with the project name, a common mistake. If the URL you use is "http://dev.azure.com/Microsoft-UK/AzureDevOpsTeam/Database", then Microsoft-UK is the Organization Name, AzureDevOpsTeam is the Project name, Database is the team name.

* Enter/select any other fields required by the template
* Hit load 
* If you are prompted for a login, you can choose:
  - 'Organizational' and enter your Organization email/password (if required) and sign in
  - 'Basic' and use a Personal Access Token (PAT) to login, entering it in the password field (user can be left as blank). Be sure the PAT has access to Analytics views

  ![alt text](https://docs.microsoft.com/en-us/azure/devops/report/powerbi/media/authentication-7.png?view=azure-devops)

* Once signed in hit 'Load' and wait for your charts to populate!
