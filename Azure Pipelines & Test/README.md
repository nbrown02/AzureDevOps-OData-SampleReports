# Template Reports for Azure Pipelines & Test (Azure DevOps / Server / TFS)
### What is it?
A collection of Power BI templates for all the [sample Azure Pipelines & Test OData Power BI reports](https://docs.microsoft.com/en-us/azure/devops/report/powerbi/sample-odata-overview?view=azure-devops) provided by Microsoft for you to visualise your Azure DevOps Pipelines & Test (or Azure DevOps Server/TFS) data. This way you can save time, download the respective template(s), enter your organization and project details then visualize your data. 

### Prerequisites
* [Make sure you have the latest version of Power BI Desktop](https://aka.ms/pbiSingleInstaller)
* Download your chosen template(s):

## Full list of sample reports for Azure Pipelines and Test

* [Failed Tests](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines%20%26%20Test/Failed%20Tests.pbit) - shows the list of failed tests for a pipeline. 
* [Flaky Tests](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines%20%26%20Test/Flaky%20Tests.pbit) - shows the list of flaky tests for a pipeline.
* [Pass Rate Trend of a Test](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines%20%26%20Test/Pass%20Rate%20Trend%20of%20a%20Test.pbit) - shows day wise trend of number of times a test passed and failed, along with its pass rate of any given test of a pipeline.
* [Pipeline Test Summary Trend](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines%20%26%20Test/Pipeline%20Test%20Summary%20Trend.pbit) - shows day wise trend of number of total failed tests and test pass rate for a pipeline.
* [Pipeline Test Summary](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines%20%26%20Test/Pipeline%20Test%20Summary.pbit) - shows the number of test runs for different test outcomes - Passed, Failed, Not executed, Not impacted.
* [Test Duration Trend](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines%20%26%20Test/Test%20Duration%20Trend.pbit) - shows the day wise trend of the average time taken to execute a test for a selected time range.
* [Test Duration](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines%20%26%20Test/Test%20Duration.pbit) - shows list of all the tests in a pipeline and the average time taken to execute each test for a selected time range.

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
