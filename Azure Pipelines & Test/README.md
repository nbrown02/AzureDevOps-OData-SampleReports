# Template Reports for Azure Pipelines & Test (Azure DevOps / Server / TFS)
## What is it?
A collection of Power BI templates for all the [sample Azure Pipelines & Test OData Power BI reports](https://docs.microsoft.com/en-us/azure/devops/report/powerbi/sample-odata-overview?view=azure-devops) provided by Microsoft for you to visualise your Azure DevOps Pipelines & Test (or Azure DevOps Server/TFS) data. This way you can save time, download the respective template(s), enter your organization and project details then visualize your data. 

## Prerequisites
* [Make sure you have the latest version of Power BI Desktop](https://aka.ms/pbiSingleInstaller)
* Download your chosen template(s):

## Full list of report templates for Azure Pipelines and Test

* [Failed Tests](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines%20%26%20Test/Failed%20Tests.pbit) - shows the list of failed tests for a pipeline. 
* [Flaky Tests](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines%20%26%20Test/Flaky%20Tests.pbit) - shows the list of flaky tests for a pipeline.
* [Pass Rate Trend of a Test](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines%20%26%20Test/Pass%20Rate%20Trend%20of%20a%20Test.pbit) - shows day wise trend of number of times a test passed and failed, along with its pass rate of any given test of a pipeline.
* [Pipeline Test Summary Trend](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines%20%26%20Test/Pipeline%20Test%20Summary%20Trend.pbit) - shows day wise trend of number of total failed tests and test pass rate for a pipeline.
* [Pipeline Test Summary](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines%20%26%20Test/Pipeline%20Test%20Summary.pbit) - shows the number of test runs for different test outcomes - Passed, Failed, Not executed, Not impacted.
* [Test Duration Trend](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines%20%26%20Test/Test%20Duration%20Trend.pbit) - shows the day wise trend of the average time taken to execute a test for a selected time range.
* [Test Duration](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines%20%26%20Test/Test%20Duration.pbit) - shows list of all the tests in a pipeline and the average time taken to execute each test for a selected time range.

## Connectivity
* Open the .pbit file
* Select http/https (only choose http if your Azure DevOps Server is HTTP)
* Add the Analytics / Azure DevOps Server URL - for Azure DevOps services enter 'analytics.dev.azure.com' / for Azure DevOps Server enter your server details
* Add your organization and project name

Don't confuse the team name with the project name, a common mistake. If the URL you use is "http://dev.azure.com/Microsoft-UK/AzureDevOpsTeam/Database", then Microsoft-UK is the Organization Name, AzureDevOpsTeam is the Project name, Database is the team name.

* It should then look something like this:

Azure DevOps Services:
![alt text](https://raw.githubusercontent.com/nbrown02/AzureDevOps-OData-SampleReports/main/Screenshots/PipelineTest1.png)

Azure DevOps Server:
![alt text](https://raw.githubusercontent.com/nbrown02/AzureDevOps-OData-SampleReports/main/Screenshots/PipelineTest2.png)

Note - certain templates may ask for additional information before loading, for example:
![alt text](https://raw.githubusercontent.com/nbrown02/AzureDevOps-OData-SampleReports/main/Screenshots/PipelineTest3.png)

* Hit 'Load' 
* If you are prompted for a login, you can choose:
  - 'Organizational' and enter your Organization email/password (if required) and sign in
  - 'Basic' and use a Personal Access Token (PAT) to login, entering it in the password field (user can be left as blank - make sure it has 'Read' access to Analytics)

  ![alt text](https://docs.microsoft.com/en-us/azure/devops/report/powerbi/media/authentication-7.png?view=azure-devops)

* Once signed in hit 'Load' and wait for your charts to populate!
