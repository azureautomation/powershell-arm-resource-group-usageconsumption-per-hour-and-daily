Powershell - ARM Resource Group usage/consumption per hour and daily
====================================================================

            

This cmdlet is based on **Get-UsageAggregates **and [this article](http://blogs.technet.com/b/keithmayer/archive/2015/06/28/export-azure-subscription-usage-with-new-billing-api-and-powershell.aspx) to get the usage of a specific resource group. And usage example to get a CSV of a resource group consumption is:


 


 

 

 


The cmdlet parameters are:


  *  **resourceGroup:** the resource group name 
  *  **reportedStartTime:** the start time of the report 
  *  **reportedEndTime:** the end time of the report 
  *  **subscriptionId:** the id of the subscription where belong the reosurce group

  *  **granularity:** the granlarity of the data- can be Hourly or Daily


    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
