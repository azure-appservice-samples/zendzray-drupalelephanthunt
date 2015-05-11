## Create a Drupal web app in Azure App Service

1. [Create Web App with Drupal](https://portal.azure.com/#gallery/Acquiacom.AcquiaDrupal7MySQL) (Click this link, then follow the instructions below)

6. Click on **WEB APP**, and provide the required values for configuring your web app.

   * **URL**: Unique Url for your site.
   * **App Service Plan**: DrupalCon
   * **Pricing Tier**: 
       * Click Pricing Tier
       * Click View All
           
           ![Pricing Tier][20]

       * Select Free
           
           ![Free Tier][22]
       
   * **Web App Settings**: No Changes
   * **Location**: No Changes 

   ![configure your app][8]

7. Click on **DATABASE**, and provide the required values for configuring your MySQL database. 

> Accept the Legal Terms

   ![configure database][database]

8. If necessary, click **SUBSCRIPTION**, and specify the subscription to use. 

7. When you have finished defining the web app, click **Create**, and wait while the new web app is created.

   When the app has been created, you will see the resource group containing web app and database.

   ![show group][resourcegroup]

[8]: ./media/website-from-gallery/configureweb.png
[database]: ./media/website-from-gallery/configuredb.png
[resourcegroup]: ./media/website-from-gallery/showgroup.png
[20]: ./media/pricing-tier-view-all.png
[22]: ./media/Free-Tier.png
