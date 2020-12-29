# Azure DevOps OData Sample Reports
### What is it?
A collection of all the [sample OData Power BI reports](https://docs.microsoft.com/en-us/azure/devops/report/powerbi/sample-odata-overview?view=azure-devops) provided by Microsoft for you to visualise your Azure DevOps data. This way you can save time, download the respective template(s), enter your organization and project then visualize your charts. 

### Prerequisites
* [Make sure you have the latest version of Power BI Desktop](https://aka.ms/pbiSingleInstaller)
* Download your chosen template(s):

## Full list of reports

| Azure Boards  | Azure Test Plans | Azure Pipelines | Azure Pipeline & Test |
| ------------- | ------------- | ------------- | ------------- |
| [Open Bugs](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Boards%20-%20OData%20Reports/Open%20Bugs.pbit) | [Progress status](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Test%20Plans%20-%20OData%20Reports/Progress%20Status.pbit) | [Outcome summary](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines%20-%20OData%20Reports/Pipeline%20Outcome%20Summary.pbit) | Test summary |
| [Bug trend](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Boards%20-%20OData%20Reports/Bug%20Trend.pbit) | [Requirements tracking](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Test%20Plans%20-%20OData%20Reports/Requirements%20Tracking%20(Traceability).pbit)  | [Outcome summary for all pipelines](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines%20-%20OData%20Reports/Pipeline%20Outcome%20Summary%20-%20All%20Pipelines.pbit) | Test summary trend |
| [Rollup](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Boards%20-%20OData%20Reports/Rollup.pbit)  | [Test Status Report](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Test%20Plans%20-%20OData%20Reports/Test%20Status%20Report.pbit) | [Pass rate trend](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines%20-%20OData%20Reports/Pass%20Rate%20-%20All%20Pipelines.pbit) | Failed tests |
| Feature progress  | [Test Execution Trend](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Test%20Plans%20-%20OData%20Reports/Test%20Execution%20Trend.pbit)  | [Stage/Task/Job Wise Failures](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines%20-%20OData%20Reports/Pipeline%20Stage%20-%20Task%20-%20Job%20Wise%20Failures.pbit) | Flaky tests |
| Work items and direct links  | [Test Suites Aggregated View](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Test%20Plans%20-%20OData%20Reports/Suite%20Level%20Aggregation.pbit)  | [Pipeline Duration](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines%20-%20OData%20Reports/Pipeline%20Duration.pbit) | Test duration |
| [Sprint Burndown](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Boards%20-%20OData%20Reports/Sprint%20Burndown.pbit)  | [Tester by Outcome Matrix](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Test%20Plans%20-%20OData%20Reports/Tester%20by%20Outcome.pbit)  | [Duration Trend](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines%20-%20OData%20Reports/Duration%20Trend.pbit) | Test duration trend |
| [Cumulative Flow Diagram (CFD)](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Boards%20-%20OData%20Reports/Cumulative%20Flow%20Diagram.pbit)  |  [Test Configuration Outcome Matrix](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Test%20Plans%20-%20OData%20Reports/Test%20Configuration%20by%20Outcome.pbit) | Task Duration  | Pass rate trend of a test |
| [Lead/Cycle Time](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Boards%20-%20OData%20Reports/Lead%20-%20Cycle%20Time.pbit)  |   | Task Duration Trend |  |

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
![alt text](https://raw.githubusercontent.com/nbrown02/AzureDevOps-OData-SampleReports/main/Screenshots/Pipeline%20Pass%20Rate.png)

![alt text](https://raw.githubusercontent.com/nbrown02/AzureDevOps-OData-SampleReports/main/Screenshots/Pipeline%20Outcome%20Summary%20-%20All%20Pipelines.png)

![alt text](https://raw.githubusercontent.com/nbrown02/AzureDevOps-OData-SampleReports/main/Screenshots/Pipeline%20Duration.png)

![alt text](https://raw.githubusercontent.com/nbrown02/AzureDevOps-OData-SampleReports/main/Screenshots/Bug%20Trend%20Report.png)

![alt text](https://raw.githubusercontent.com/nbrown02/AzureDevOps-OData-SampleReports/main/Screenshots/Pipeline%20Job%20Wise%20Failures.png)

![alt_text](https://raw.githubusercontent.com/nbrown02/AzureDevOps-OData-SampleReports//main/Screenshots/Duration%20Trend.png)

![alt text](https://raw.githubusercontent.com/nbrown02/AzureDevOps-OData-SampleReports/main/Screenshots/Test%20Execution%20Trend%.png)

![alt_text](https://raw.githubusercontent.com/nbrown02/AzureDevOps-OData-SampleReports//main/Screenshots/Progress%20Status.png)
