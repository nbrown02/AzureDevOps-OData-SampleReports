# Template Reports for Azure Test Plans (Azure DevOps / Server / TFS)
### What is it?
A collection of Power BI templates for all the [sample Azure Test Plans OData Power BI reports](https://docs.microsoft.com/en-us/azure/devops/report/powerbi/sample-odata-overview?view=azure-devops) provided by Microsoft for you to visualise your Azure DevOps Boards (or Azure DevOps Server/TFS) data. This way you can save time, download the respective template(s), enter your organization and project details then visualize your data. 

### Prerequisites
* [Make sure you have the latest version of Power BI Desktop](https://aka.ms/pbiSingleInstaller)
* Download your chosen template(s):

## Full list of sample reports for Azure Test Plans

* [Progress Status](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Test%20Plans/Progress%20Status.pbit) - shows the execution state of one or more Test Plans.
* [Requirements Tracking & Traceability](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Test%20Plans%20-%20OData%20Reports/Requirements%20Tracking%20(Traceability).pbit) - shows the progress of tests against a particular work item (User Story/PBI) and link between test cases.
* [Test Suites Aggregated View](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Test%20Plans/Suite%20Level%20Aggregation.pbit) - aggregation of test results by test suite(s).
* [Test Configuration Outcome Matrix](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Test%20Plans/Test%20Configuration%20by%20Outcome.pbit) - shows the progress of tests made for each configuration.
* [Test Execution Trend](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Test%20Plans/Test%20Execution%20Trend.pbit) - shows the execution state of one or more Test Plans.
* [Test Status Report](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Test%20Plans/Test%20Status%20Report.pbit) - shows aggregated Test Cases and their status for all Test Plans within a project.
* [Tester by Outcome Matrix](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Test%20Plans/Tester%20by%20Outcome.pbit)  - shows the distribution of test outcomes across testers to figure out how the tests can be load-balanced.

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
