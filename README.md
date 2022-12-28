# Power BI Template Reports using OData for Azure DevOps/Azure DevOps Server/TFS 
## What is it?
A collection of Power BI templates for all of the [sample Azure DevOps OData Power BI reports](https://docs.microsoft.com/en-us/azure/devops/report/powerbi/sample-odata-overview?view=azure-devops) provided by Microsoft for you to visualise your Azure DevOps, Azure DevOps Server and/or TFS data. This way you can save time, download the respective template(s), enter your organization and project details then visualize your data. 

## Prerequisites
* [Make sure you have the latest version of Power BI Desktop](https://aka.ms/pbiSingleInstaller)
* Download your chosen template(s):

## Full list of report templates available

| Azure Boards  | Azure Test Plans | Azure Pipelines | Azure Pipeline & Test |
| ------------- | ------------- | ------------- | ------------- |
| [Open Bugs](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Boards/Open%20Bugs.pbit) | [Progress Status](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Test%20Plans/Progress%20Status.pbit) | [Outcome Summary](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines/Pipeline%20Outcome%20Summary.pbit) | [Pipeline Test Summary](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines%20%26%20Test/Pipeline%20Test%20Summary.pbit) |
| [Bug Trend](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Boards/Bug%20Trend.pbit) | [Requirements Tracking & Traceability](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Test%20Plans/Requirements%20Tracking%20(Traceability).pbit) | [Outcome Summary for all Pipelines](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines/Pipeline%20Outcome%20Summary%20-%20All%20Pipelines.pbit) | [Pipeline Test Summary Trend](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines%20%26%20Test/Pipeline%20Test%20Summary%20Trend.pbit) |
| [Rollup](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Boards/Rollup.pbit)  | [Test Status Report](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Test%20Plans/Test%20Status%20Report.pbit) | [Pass Rate Trend](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines/Pass%20Rate%20-%20All%20Pipelines.pbit) | [Failed Tests](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines%20%26%20Test/Failed%20Tests.pbit) |
| [Feature Progress](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Boards/Feature%20Progress.pbit) | [Test Execution Trend](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Test%20Plans/Test%20Execution%20Trend.pbit) | [Stage/Task/Job Wise Failures](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines/Pipeline%20Stage%20-%20Task%20-%20Job%20Wise%20Failures.pbit) | [Flaky Tests](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines%20%26%20Test/Flaky%20Tests.pbit) |
| [Work Items With Direct Links](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Boards/Work%20Items%20with%20Direct%20Links.pbit)  | [Test Suites Aggregated View](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Test%20Plans/Suite%20Level%20Aggregation.pbit) | [Pipeline Duration](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines/Pipeline%20Duration.pbit) | [Test Duration](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines%20%26%20Test/Test%20Duration.pbit) |
| [Sprint Burndown](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Boards/Sprint%20Burndown.pbit)  | [Tester by Outcome Matrix](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Test%20Plans/Tester%20by%20Outcome.pbit)  | [Duration Trend](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines/Duration%20Trend.pbit) | [Test Duration Trend](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines%20%26%20Test/Test%20Duration%20Trend.pbit) |
| [Cumulative Flow Diagram (CFD)](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Boards/Cumulative%20Flow%20Diagram.pbit)  |  [Test Configuration Outcome Matrix](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Test%20Plans/Test%20Configuration%20by%20Outcome.pbit) | [Task Duration](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines/Pipeline%20Task%20Duration.pbit)  | [Pass Rate Trend of a Test](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines%20%26%20Test/Pass%20Rate%20Trend%20of%20a%20Test.pbit) |
| [Lead/Cycle Time](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Boards/Lead%20-%20Cycle%20Time.pbit)  |   | [Task Duration Trend](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines/Pipeline%20Task%20Duration%20Trend.pbit) |  |

### Connectivity
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

* Hit 'Load' 
* If you are prompted for a login, you can choose:
  - 'Organizational' and enter your Organization email/password (if required) and sign in
  - 'Basic' and use a Personal Access Token (PAT) to login, entering it in the password field (user can be left as blank - make sure it has 'Read' access to Analytics)

  ![alt text](https://docs.microsoft.com/en-us/azure/devops/report/powerbi/media/authentication-7.png?view=azure-devops)

* Once signed in hit 'Load' and wait for your charts to populate!


### Screenshots of different reports
## Azure Boards (click on image to view/zoom)
![alt text](https://raw.githubusercontent.com/nbrown02/AzureDevOps-OData-SampleReports/main/Screenshots/Azure%20Boards.png)

## Azure Test Plans (click on image to view/zoom)
![alt text](https://raw.githubusercontent.com/nbrown02/AzureDevOps-OData-SampleReports/main/Screenshots/Azure%20Test%20Plans.png)

## Azure Pipelines (click on image to view/zoom)
![alt text](https://raw.githubusercontent.com/nbrown02/AzureDevOps-OData-SampleReports/main/Screenshots/Azure%20Pipelines.png)

## Azure Pipelines & Test (click on image to view/zoom)
![alt text](https://raw.githubusercontent.com/nbrown02/AzureDevOps-OData-SampleReports/main/Screenshots/Azure%20Pipelines%20%26%20Test.png)
