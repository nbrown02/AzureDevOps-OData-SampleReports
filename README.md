# Azure DevOps OData Sample Reports
### What is it?
A collection of all the [sample OData Power BI reports](https://docs.microsoft.com/en-us/azure/devops/report/powerbi/sample-odata-overview?view=azure-devops) provided by Microsoft for you to visualise your Azure DevOps data. This way you can save time, download the respective template(s), enter your organization and project then visualize your charts. 

### Prerequisites
* [Make sure you have the latest version of Power BI Desktop](https://aka.ms/pbiSingleInstaller)
* Download your chosen template(s)
* Then you're good to get started!

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

## Full list of reports

| Azure Boards  | Azure Test Plans | Azure Boards  | Azure Test Plans |
| ------------- | ------------- | ------------- | ------------- |
| [Open Bugs]() | Progress status |
| Bug trend  | Requirements tracking  |
| Rollup  | Requirements tracking - Rollup  |
| Feature progress  | Execution Trend  |
| Work items and direct links  | Test suites aggregated view  |
| Release burndown  | Tester by outcome matrix  |
| Sprint burndown  | Configuration by outcome matrix  |
| Cumulative Flow Diagram (CFD)  |   |
| Lead/Cycle Time  |   |

### Pipeline
* Outcome summary
* Outcome summary for all pipelines
* Pass rate trend
* Stage wise failures
* Duration
* Duration trend
* Task duration
* Task duration trend

### Pipeline & Test
* Test summary
* Test summary trend
* Failed tests
* Flaky tests
* Test duration
* Test duration trend
* Pass rate trend of a test
