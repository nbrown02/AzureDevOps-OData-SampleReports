# Azure DevOps OData Sample Reports
### What is it?
A collection of all the [sample OData Power BI reports](https://docs.microsoft.com/en-us/azure/devops/report/powerbi/sample-odata-overview?view=azure-devops) provided by Microsoft for you to visualise your Azure DevOps data. This way you can save time, download the respective template(s), enter your organization and project then visualize your charts. 

### Prerequisites
* [Make sure you have the latest version of Power BI Desktop](https://aka.ms/pbiSingleInstaller)
* Download your chosen template(s):

## Full list of reports

| Azure Boards  | Azure Test Plans | Pipeline  | Pipeline & Test |
| ------------- | ------------- | ------------- | ------------- |
| [Open Bugs]() | Progress status | Outcome summary | Test summary |
| Bug trend  | Requirements tracking  | Outcome summary for all pipelines | Test summary trend |
| Rollup  | Requirements tracking - Rollup | Pass rate trend | Failed tests |
| Feature progress  | Execution Trend  | Stage wise failures | Flaky tests |
| Work items and direct links  | Test suites aggregated view  | Duration | Test duration |
| Release burndown  | Tester by outcome matrix  | Configuration by outcome matrix | Test duration trend |
| Sprint burndown  |   | Duration trend | Pass rate trend of a test |
| Cumulative Flow Diagram (CFD)  |   | Task duration |  |
| Lead/Cycle Time  |   | Task duration trend |  |

### Connectivity
* Open the .pbit file
* Add your organization and project name

Don't confuse the team name with the project name, a common mistake. If the URL you use is "http://dev.azure.com/Microsoft-UK/AzureDevOpsTeam/Database", then Microsoft-UK is the Organization Name, AzureDevOpsTeam is the Project name, Database is the team name.

* Hit load 
* If you are prompted for a login, you can choose:
  - 'Organizational' and enter your Organization email/password (if required) and sign in
  - 'Basic' and use a Personal Access Token (PAT) to login, entering it in the password field (user can be left as blank)

  ![alt text](https://docs.microsoft.com/en-us/azure/devops/report/powerbi/media/authentication-7.png?view=azure-devops)

* Once signed in hit 'Load' and wait for your charts to populate!

### Screenshots

