# Template Reports for Azure Pipelines (Azure DevOps / Server / TFS)
## What is it?
A collection of Power BI templates for all the [sample Azure Pipelines OData Power BI reports](https://docs.microsoft.com/en-us/azure/devops/report/powerbi/sample-odata-overview?view=azure-devops) provided by Microsoft for you to visualise your Azure DevOps Boards (or Azure DevOps Server/TFS) data. This way you can save time, download the respective template(s), enter your organization and project details then visualize your data. 

## Prerequisites
* [Make sure you have the latest version of Power BI Desktop](https://aka.ms/pbiSingleInstaller)
* Download your chosen template(s):

## Full list of report templates for Azure Pipelines

* [Duration Trend](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines/Duration%20Trend.pbit) - shows how long your pipeline typically takes to complete successfully. 
* [Pass Rate Trend](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines/Pass%20Rate%20-%20All%20Pipelines.pbit) - shows a pipeline's daily pass rate trend. Pass rate of a pipeline is defined as the percentage of successful pipeline runs to the total pipeline runs.
* [Pipeline Duration](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines/Pipeline%20Duration.pbit) - displays pipeline duration, or the time taken to run a pipeline.
* [Outcome Summary for all Pipelines](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines/Pipeline%20Outcome%20Summary%20-%20All%20Pipelines.pbit) - shows pipeline metrics such as pass rate, number of failures, duration, and so on. for all the pipelines together, in a single report.
* [Outcome Summary](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines/Pipeline%20Outcome%20Summary.pbit) - shows the number of runs for different pipeline outcomes (Succeeded / Failed / Canceled / Partially Succeeded).
* [Stage/Task/Job Wise Failures](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines/Pipeline%20Stage%20-%20Task%20-%20Job%20Wise%20Failures.pbit) - shows a report of a pipeline's daily stage failures.
* [Task Duration Trend](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines/Pipeline%20Task%20Duration%20Trend.pbit) - shows the daily trend report of the time taken to execute a pipeline task.
* [Task Duration](https://github.com/nbrown02/AzureDevOps-OData-SampleReports/raw/main/Azure%20Pipelines/Pipeline%20Task%20Duration.pbit) - shows the time taken to execute different tasks of a pipeline.

## Connectivity
* Open the .pbit file
* Select http/https (only choose http if your Azure DevOps Server is HTTP)
* Add the Analytics / Azure DevOps Server URL - for Azure DevOps services enter 'analytics.dev.azure.com' / for Azure DevOps Server enter your server details
* Add your organization and project name

Don't confuse the team name with the project name, a common mistake. If the URL you use is "http://dev.azure.com/Microsoft-UK/AzureDevOpsTeam/Database", then Microsoft-UK is the Organization Name, AzureDevOpsTeam is the Project name, Database is the team name.

* It should then look something like this:

Azure DevOps Services:
![alt text](https://raw.githubusercontent.com/nbrown02/AzureDevOps-OData-SampleReports/main/Screenshots/Pipelines1.png)

Azure DevOps Server:
![alt text](https://raw.githubusercontent.com/nbrown02/AzureDevOps-OData-SampleReports/main/Screenshots/Pipelines2.png)

Note - certain templates may ask for additional information before loading, for example:
![alt text](https://raw.githubusercontent.com/nbrown02/AzureDevOps-OData-SampleReports/main/Screenshots/PipelineTest3.png)

* Hit 'Load' 
* If you are prompted for a login, you can choose:
  - 'Organizational' and enter your Organization email/password (if required) and sign in
  - 'Basic' and use a Personal Access Token (PAT) to login, entering it in the password field (user can be left as blank - make sure it has 'Read' access to Analytics)

  ![alt text](https://docs.microsoft.com/en-us/azure/devops/report/powerbi/media/authentication-7.png?view=azure-devops)

* Once signed in hit 'Load' and wait for your charts to populate!
