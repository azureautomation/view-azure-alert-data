View Azure Alert Data
=====================

            

DESCRIPTION


This runbook is designed to be called from an Azure alert via a webhook.  The alert data is passed in the runbook input parameter WebhookData.  This runbook parses that data and outputs the individual alert properties.


Use this runbook to test Azure alerts.



REQUIRED


This runbook must be called from an Azure alert via a webhook.  You create a webhook for this runbook and then configure the Azure alert rule to call the webhook URL when the alert triggers.


AUTHOR


Azure Automation Team 


LASTEDIT


2016-5-18#>


 

 

![Image](https://github.com/azureautomation/view-azure-alert-data/raw/master/ViewAzureAlertData.png)


        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
