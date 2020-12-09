Pre-requisites:
1) Install .net core 3 runtime.
2) Install MySql 8.
3) Install Azure CLI.


Run the application:
There are two applications in the package. 
	i) Azure Automation: Gets the logs periodically and stores in local db.
	ii) Azure Logs Dashboard: Shows the logs from local db in the grid view where it supports filters, exporting, sorting.
1) Open App Configuration file.
	i) ExecutablePath has to be the .exe path from AzureAutomation package.
	ii)Change SmtpServerUrl, From, To, SmtpUserName, SmtpPassword, SmtpPort accordingly.
2) Open AzureAutomation.exe file. It takes couple of minutes to 5 minutes to process.
3) Open dashboard to see the data and can be exported.
