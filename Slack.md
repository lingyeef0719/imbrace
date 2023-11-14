# Slack

[Slack](https://slack.com/)  is a business communication platform offering many IRC-style features, including persistent  
chat rooms (channels), private groups, and direct messaging.

## Account integration using OAuth

To begin, you will need:  
- An [Slack](https://slack.com/) account.

**STEP 1**: Go to the [Slack API page](https://api.slack.com/), then in the top-right corner, go to **[Your apps]**.  
**STEP 2**: Go to **[Create New App] > [From scratch]**.  
**STEP 3**: Enter an **App Name** and select the **workspace** the credential will be associated with, then  
click **[Create App]**.  
**STEP 4**: Under the Basic **Information > App credentials** section, identify and copy the **client ID**  
and client secret.  
**STEP 5**: In iMBrace, create a new credential of type **Slack OAuth2 API**, and paste the client ID and  
client secret into the corresponding fields. Then, identify the **OAuth Redirect URL**.   
**STEP 6**: On the Slack API page, navigate to **Basic Information > Building Apps for Slack > Add  
features and functionality > [Permissions]**.  
**STEP 7**: In the **Redirect URLs** section, click on **[Add New Redirect URL]**, then paste the OAuth  
redirect URL copied from iMBrace.  
**STEP 8**: Click on the **[Save URLs]** button.  
**STEP 9**: Scroll down to the **Scopes** section.  
**STEP 10**: Add the required scopes under the **Bot Token Scopes** section. You can refer to the list of  
scopes on the [Scopes and permissions](https://api.slack.com/scopes) documentation on Slack.  
**STEP 11**: In iMBrace, click the **[Connect]** button.  
**STEP 12**: Click **[Allow]** in the pop-up to connect your Slack account to iMBrace.  
**STEP 13**: On the Slack API page, go to **[OAuth & Permissions]** in the left side-bar. In the **OAuth  
Tokens for Your Workspace** section, click **[Install to Workspace]**.  
**STEP 14**: Click on the **[Allow]** button.  
**DONE**: The credential can then be used for Slack nodes.  

## Account integration using Access Token

To begin, you will need:  

- An [Slack](https://slack.com/) account.

**STEP 1**: Go to the [Slack API](https://api.slack.com/) page, then in the top-right corner, go to **[Your apps]**.  
**STEP 2**: Go to **[Create New App] > [From scratch]**.  
**STEP 3**: Enter an **App Name** and select the **workspace** the credential will be associated with, then  
click **[Create App]**.  
**STEP 4**: Under the **Basic Information > Add features and functionality** section, select  
**[Permissions]**.  
**STEP 5**: Scroll down to the **Scopes** section and:  
- If you want your app to act on behalf of users that authorize the app, add the required scopes   
under the **User Token Scopes** section.  
- If you're building a bot, add the required scopes under the **Bot Token Scopes** section.

**STEP 6**: From the **OAuth Tokens for Your Workspace** section click on the **Install to Workspace**   
button.  
**STEP 7**: Click on the **[Allow]** button.  
**STEP 8**: In the left side-bar, go to **OAuth & Permissions > OAuth Tokens for Your Workspace**, and  
copy the relevant token for your use.  
**STEP 9**: In iMBrace, create a credential of type **Slack API**, paste the copied token from Slack into  
the **Access Token** field, then click the **[Create]** button.  
**DONE**: The credential can then be used for Slack nodes.
