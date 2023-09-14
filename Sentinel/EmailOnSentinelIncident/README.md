# EmailOnSentinelIncident

No logging and monitoring setup is complete without an alert. This is not trivial in Microsoft Sentinel. We've created this Playbook to deploy the logical app "EmailOnSentinelIncident" to do just that. 

## Deployment
1. Use the button below to deploy the playbook to Azure.
2. Fill in the values for Azure Account and Mail Recipient.
3. Check the Connections in Logical App Designer View.
4. Link the Logical App (as Playbook) to a Microsoft Sentinel Scheduled Query as Automated Respons.
5. Profit.


[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fchptr8%2FBlueTeam%2Fmain%2FSentinel%2FEmailOnSentinelIncident%2Fazuredeploy.json)
