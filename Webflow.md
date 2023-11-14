# Webflow

[Webflow](https://webflow.com/) is an application that allows you to build responsive websites with browser-based visual 
editing software.

## Account integration using OAuth
To begin, you will need:
- A [Webflow](https://webflow.com/) account.

**STEP 1**: In iMBrace, select **Credential** and click **[ADD NEW]** button.  
**STEP 2**: Select **Webflow OAuth2 API** in the **Integrations** section.  
**STEP 3**: Click on the **[Copy URL]** button to copy the **OAuth Redirect URL**.  
**STEP 4**: Go to your Webflow [dashboard](https://webflow.com/dashboard) and select your desired workspace.  
**STEP 5**: Click on the **Setting icon**.  
**STEP 6**: Select the **Integrations** tab.  
**STEP 7**: Click on the **[+ Register New Application]** button under **Workspace Applications** section.  
**STEP 8**: Enter your **Application Name, Application Description** and **Application Homepage**.  
**STEP 9**: Paste the **Redirect URL** that you copy from iMBrace.  
**STEP 10**: Click on the **[Create]** button.  
**STEP 11**: Click on the **[View details]** button.  
**STEP 12**: Copy both the **Client Id** and **Client Secret**.  
**STEP 13**: In iMBrace, paste the **Client ID, Client Secret** and click **[Connect]** button.  
**DONE**: The credential can then be used for Webflow nodes.

## Account integration using Access Token

To begin, you will need:
- A Webflow account.

**STEP 1**: Access your Webflow [dashboard](https://webflow.com/dashboard).  
**STEP 2**: Select your desired workspace and open the desired site in Webflow's Designer.  
**STEP 3**: Click on the **W icon** in the top left.  
**STEP 4**: Click on **[Site settings]**.  
**STEP 5**: Click on the **Integrations** tab.  
**STEP 6**: Scroll down and click **[Generate API token]** under **API Access** section.  
**STEP 7**: Copy the **API token**.  
**STEP 8**: In iMBrace, select **Credential** and click **[ADD NEW]**.  
**STEP 9**: Select **Webflow API** in **Integrations** section.  
**STEP 10**: Paste the **access token** and click **[CREATE]**.  
**DONE**: The credential can then be used for Webflow nodes.
