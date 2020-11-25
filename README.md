# Azure DevOps OData Sample Reports
### What is it?
A collection of all the [sample OData Power BI reports](https://docs.microsoft.com/en-us/azure/devops/report/powerbi/sample-odata-overview?view=azure-devops) provided by Microsoft for you to visualise your Azure DevOps data. This way you can save time, download the respective template(s), enter your organization and project then visualize your charts. 

### Prerequisites
* [Make sure you have the latest version of Power BI Desktop](https://aka.ms/pbiSingleInstaller)
* Download your chosen template(s):

## Full list of reports

| Azure Boards  | Azure Test Plans | Pipeline  | Pipeline & Test |
| ------------- | ------------- | ------------- | ------------- |
| [Open Bugs](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Boards%20-%20OData%20Reports/Open%20Bugs.pbit) | Progress status | [Outcome summary](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines%20-%20OData%20Reports/Pipeline%20Outcome%20Summary.pbit) | Test summary |
| [Bug trend](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Boards%20-%20OData%20Reports/Bug%20Trend.pbit) | Requirements tracking  | [Outcome summary for all pipelines](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines%20-%20OData%20Reports/Pipeline%20Outcome%20Summary%20-%20All%20Pipelines.pbit) | Test summary trend |
| [Rollup](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Boards%20-%20OData%20Reports/Rollup.pbit)  | Requirements tracking - Rollup | Pass rate trend | Failed tests |
| Feature progress  | Execution Trend  | Stage wise failures | Flaky tests |
| Work items and direct links  | Test suites aggregated view  | [Pipeline Duration](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines%20-%20OData%20Reports/Pipeline%20Duration.pbit) | Test duration |
| Release burndown  | Tester by outcome matrix  | Configuration by outcome matrix | Test duration trend |
| Sprint burndown  |   | Duration trend | Pass rate trend of a test |
| Cumulative Flow Diagram (CFD)  |   | Task duration |  |
| Lead/Cycle Time  |   | Task duration trend |  |

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

### Screenshots

