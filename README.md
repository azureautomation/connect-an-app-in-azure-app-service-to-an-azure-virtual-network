Connect an app in Azure App Service to an Azure Virtual Network
===============================================================

            

In Azure App Service, you can connect your app (web, mobile, or API) to an Azure virtual network (VNet) in your subscription. This script helps enable VNet integration by using PowerShell.


This script completes the following tasks:


  *  Create a Resource Manager virtual network and integrate your app with it. 
  *  Create a gateway, configure point-to-site connectivity in a preexisting Resource Manager virtual network, and then integrate your app with it.

  *  Integrate your app with a preexisting Resource Manager virtual network that has a gateway and point-to-site connectivity enabled.

  *  Disconnect your app from your virtual network. 
Prerequisites

To run this script, you need:


 


  *  [Install the latest Azure PowerShell](https://docs.microsoft.com/powershell/azure/install-azurerm-ps). 

  *  Have App Service app running in a Standard or Premium tier. 
Steps

To run the script, do the following:


  *  Download the script to a directory on your machine. 
  *  Open a Windows PowerShell window in administrator mode. 
  *  






PowerShell
Edit|Remove

Set-ExecutionPolicy -ExecutionPolicy Unrestricted -Force 
 
.\V2VnetAllInOne.ps1





More Information

If you want to learn more about the feature, see [Integrate your app with an Azure virtual network](https://github.com/cephalin/archiveddocs/blob/master/app-service-web/web-sites-integrate-with-vnet.md). 


For questions, contact ccompy@microsoft.com.


        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
