# CMS for HubSpot Developers Practicum

## Install HubSpot CMS CLI
 - Create HubSpot sandbox account
 - Make sure that node and npm is already installed
  
> `npm install -g @hubspot/cli`
  
## Configure local development tools
  
> `npx hs init`
  
This will open your web browser and take you to the page where you can create your Personal Access Token which is required for setting up the local development environment. **Make sure that the portal in the browser is pointing to your sandbox.** You double check by looking at the portal id in the URL. If you are not in the sandbox portal you can simply change the portal id in the URL and hit enter.
  
## Upload the theme to hubspot
  
> `npx hs upload theme theme`

## Using the theme

After successfully uploading the theme you can verify that the theme was uploaded successfully you can open your HubSpot sandbox navigate to **Marketing** -> **File and Templates** -> **Design Tools**. You should see a folder called theme with the theme source files in the folder. You are able to make changes using **Design Tools**.

To make use of this template in your sandbox, navigate to **Marketing** -> **Website** -> **Website Pages**. Click on the **Create** button, followed by **Website page** to create a new web page. Enter the **Page name** of the website, click on **Create page**.

On the theme selection page navigate to **Practicum Theme**. Click on **View templates**, there is only one template being displayed, **About**, click **Select template**.

Preview final result [click here](http://26122711.hs-sites-eu1.com/practicum) after adding some sample data to the theme.