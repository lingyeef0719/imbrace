# Xero

Xero offers an online cloud-based SaaS accounting software platform for small and medium-sized  
businesses.

## Account integration using OAuth
To begin, you will need:
- A [Xero](https://www.xero.com/) account.

**STEP 1**: In iMBrace, select **Credential** and click the **[ADD NEW]** button.  
**STEP 2**: Select **Xero OAuth2 API** in the **Integrations** section.  
**STEP 3**: Click on the **[Copy URL]** button to copy the **OAuth Redirect URL**.  
**STEP 4**: Go to the [apps page](https://developer.xero.com/myapps) in the Xero developer portal.  
**STEP 5**: Click on **[New app]** button, fill in any necessary information and paste the **Redirect URL**   
that you copy from iMBrace.   
**STEP 6**: Click the **[Create app]** button.  
**STEP 7**: Go to the **Configuration** section.  
**STEP 8**: Click the **[Generate a secret]** button.  
**STEP 9**: Copy both the **Client id** and **Client secret 1**.  
**STEP 10**: In iMBrace, paste the **Client ID, Client Secret** that you copy from Xero and click   
**[Connect]** button.   
**DONE**: The credential can then be used for Xero nodes.
