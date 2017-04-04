# Deploy a Simple .NET App on Bluemix
Following this guide, we will set up a .NET deployment service, and deploy a multi-tier .NET app on Bluemix. 

## Prerequisites
You need a Bluemix account; register for free here: https://console.ng.bluemix.net/registration/ 

## Quick Steps
### 1. Deploy Apprenda Cloud Platform

* Go to **Bluemix Catalog**: https://console.ng.bluemix.net/catalog/
* Search for  `bluemix .net`, choose **Apprenda Cloud Platform**, and click **Create**
* Open **Apprenda Cloud Platform Dashboard**
* Copy/save generated **Sign-Up Token**

<img src="https://github.com/apprenda/bluemix-dotnet-getting-started/raw/master/1-multi-tier/images/1-BluemixCatalog.gif" width="500">

### 2. Register Platform Organization Account
* Complete the **Registration Form** required fields
* Paste the **Sign-Up Token**
* Click **Create My Account**
* After Bluemix provisions everything, click the link to the **Developer Portal**

<img src="https://github.com/apprenda/bluemix-dotnet-getting-started/raw/master/1-multi-tier/images/2-LaunchACP.gif" width="500">

### 3. Deploy Application
* Copy TimeCard.zip application package URL:  
`https://github.com/apprenda/bluemix-dotnet-getting-started/raw/master/1-multi-tier/TimeCard.zip`

* Click the **+NEW** button, enter an application name, paste the package URL, and click **Save & Continue**

<img src="https://github.com/apprenda/bluemix-dotnet-getting-started/raw/master/1-multi-tier/images/3-DeployApp.gif" width="500">

* **Promote** the app to **Sandbox**, and promote again to **Published**

<img src="https://github.com/apprenda/bluemix-dotnet-getting-started/raw/master/1-multi-tier/images/4-PromoteApp.gif" width="500">

* Click **Launch** to open the TimeCard app


