# Zoho CRM

Zoho CRM allows access to its services using OAuth, which is a way to authenticate Zoho users on  
other websites. This allows Zoho users to integrate and perform automated tasks on their account  
using the iMBrace platform.

## Account integration using OAuth
To begin, you will need:
- A Zoho CRM account.

**STEP 1**: Go to the **Zoho API Console** (<https://api-console.zoho.com/>).  
**STEP 2**: Go to **[Get Started] > [Server-based Applications]**.  
**STEP 3**: In iMBrace, create a new credential of type **Zoho OAuth2 API** and identify the **OAuth  
redirect URL**.  
**STEP 4**: In the Zoho Console, create a new client by entering the necessary information. Enter the  
redirect URL from iMBrace under **Authorized redirect URLs**.  
**STEP 5**: Click **[Create]** to generate the **client ID** and **client secret**.  
**STEP 6**: Copy the client ID and secret into iMBrace and click on **[Connect my account]** to  
complete the OAuth authentication.  
**DONE**: The new credential can then be used for Zoho CRM nodes.
