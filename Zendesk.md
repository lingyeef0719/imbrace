# Zendesk

[Zendesk](https://www.zendesk.com/) is a support ticketing system, designed to help track, prioritize, and solve customer  
support interactions. More than just a help desk, Zendesk Support helps nurture customer  
relationships with personalized, responsive support across any channel.  

## Account integration using OAuth 
To begin, you will need:  
- An [Zendesk](https://zendesk.com/) account.

**STEP 1**: Open your Zendesk dashboard.  
**STEP 2**: Click on the squares icon on the right and click **[Admin Center]**.  
**STEP 3**: Click on **[Zendesk API]** under the **Apps and integration** section in the sidebar.  
**STEP 4**: Click on the **[OAuth Clients]** tab.  
**STEP 5**: Click on the **[Add OAuth client]** button.  
**STEP 6**: Enter the client name in the **Client Name** field.  
**STEP 7**: Enter a description in the **Description** field.  
**STEP 8**: In iMBRACE, copy the **OAuth Callback URL** provided in the **Zendesk OAuth2 API**  
credentials.    
**STEP 9**: Paste it in the **Redirect URLs** field on the Zendesk API credentials page.  
**STEP 10**: Click on the **[Save]** button.  
**STEP 11**: Click on the **[OK]** button on the **Please store the secret that will appear** pop-up.  
**STEP 12**: Scroll down to the **Secret** section and copy the displayed **Secret**.  
**STEP 13**: In iMBRACE, paste this secret in the **Client Secret** field in the Zendesk OAuth2 API credentials.  
**STEP 14**: Copy the **Unique identifier** from the Zendesk API credentials page.   
**STEP 15**: In iMBRACE, paste it in the **Client ID** field in the Zendesk OAuth2 API credentials.  
**STEP 16**: In iMBRACE, enter your Zendesk subdomain in the **Subdomain** field in the Zendesk  
OAuth2 API credentials.  
**STEP 17**: In iMBRACE, enter the name for your credentials in the **Credentials Name** field in the  
Zendesk OAuth2 API credentials.  
**STEP 18**: Click on the **[Connect]** button in the OAuth section to connect a Zendesk account to  
iMBRACE.  
**DONE**: The credential can then be used for Zendesk nodes.  

## Account integration using Access Token

To begin, you will need:  

- An [Zendesk](https://zendesk.com/) account.

**STEP 1**: Open your Zendesk dashboard.  
**STEP 2**: Click on the squares icon on the right and click **[Admin Center]**.  
**STEP 3**: Click on **[Zendesk API]** under the **Apps and integration** section in the sidebar.  
**STEP 4**: If **Token access** is disabled, click on the switch to toggle it to **Enabled**.  
**STEP 5**: Click on the **[Add API token]** button.  
**STEP 6**: Enter a description in the **API token description** field.  
**STEP 7**: Click on the **[Copy]** button to copy the API token.  
**STEP 8**: Click on the **[Save]** button.  
**STEP 9**: In iMBRACE, enter the name for your credentials in the **Credentials Name** field in the  
'Zendesk API' credentials.  
**STEP 10**: Enter your Zendesk subdomain in the **Subdomain** field.  
**STEP 11**: Enter your Zendesk email address in the **Email** field.  
**STEP 12**: In iMBRACE, paste the **API token** in the **API Token** field.   
**STEP 13**: Click on the **[Create]** button to save your credentials.  
**DONE**: The credential can then be used for Zendesk nodes.
