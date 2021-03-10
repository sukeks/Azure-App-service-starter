Creating an App Service in Azure

I took the following steps to create an App Service Web App using the Azure Portal

1) On the homepage, click "Create a resource"
2) Search for "Web App"
3) Click "Create"
4) Select your subscription
5) Select your resource group "resource-group-west"
6) Enter a name for your web app—This needs to be a unique name and is unique to Azure as a whole and not just your Azure account. I used "hello-world1234" as my unique name.
7) For Publish, select "Code"
8) For the "Runtime Stack", select "Python 3.7" or greater.
9) For the "Operating System" select "Linux"
10) Select a region for your app service
11) Create a new App Service Plan. You can keep the default name Azure gives you or you can create your own name.
12) For SKU and size, select "F1" (Free).
13)Click "Review + Create"
14) Click "Create"
Then, I clicked on the URL to see the app service, which confirmed the app service was up and running. Now we need to deploy our code.

Note: Azure free account only allows 1 Linux App Service of size F1. You will need to delete the App Service Web App along with the App Service Plan after practising,
since we will create other Linux App Services, otherwise you will be charged for those running resources.


To deploy an App Service from a GitHub repository in Azure, I did the following:

1) Go to Deployment Center
2) Choose GitHub
3) Choose org and repo
4) Go through the prompts; deployment takes a few minutes
5) Go to URL of web app and should see the app deployed

Cleanup
If we no longer need a resource, we can delete them through the portal.

1)From the homepage, click on "Resource Group".
2)Click on the resource group you want to manage.
3) You have two options—"Delete resource group" or if you want to keep the resource group, you can click on the individual or collection of resources you want to delete and 
click on "Delete".
