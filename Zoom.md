# Zoom

[Zoom](https://zoom.us/) is a communications technology company that provides videotelephony and online chat  
services through a cloud-based peer-to-peer software platform and is used for teleconferencing,  
telecommuting, distance education, and social relations.  

## Account integration using OAuth

To begin, you will need:  

- An [Zoom](https://zoom.us/) account.

**STEP 1**: Visit the [Zoom App Marketplace](https://marketplace.zoom.us/) and select the **[Build App]** option in the **Develop**  
dropdown on the top-right corner.  
**STEP 2**: Click on the **[Create]** button to create a new OAuth app.  
**STEP 3**: Select **[User-managed app]**.  
**STEP 4**: Set the **"Would you like to publish this app on Zoom App Marketplace?"** slider to **off**.  
**STEP 5**: Click on the **[Create]** button.  
**STEP 6**: In **iMBRACE**, copy the '**OAuth Redirect URL**' provided in the Zoom OAuth2 API credentials,  
then in the **Zoom app creation page**, paste it in the **'Redirect URL for OAuth'** section and ‘**Add  
Allow Lists**’ section.   
**STEP 7**: In the Zoom app creation page, copy the **Client ID** and **Client Secret** provided and in   
iMBRACE, paste it in the **Zoom OAuth2 API credentials**.  
- Zoom App Creation Page  
- iMBRACE

**STEP 8**: Enter any **necessary** information and click **[continue]**.  
**STEP 9**: In the **'Scopes'** section, click **[Add Scopes]** and choose the scopes that you plan to use.  
**STEP 10**: In iMBRACE, click on the **[Connect]** button in the OAuth section to connect your Zoom  
account.  
**DONE**: The credential can then be used for Zoom nodes.  

## Account integration using Access Token  
To begin, you will need:  
- An [Zoom](https://zoom.us/) account.

**STEP 1**: Visit the [Zoom App Marketplace](https://marketplace.zoom.us/) and select the **[Build App]** option in the **Develop**  
dropdown on the top-right corner.  
**STEP 2**: Click on the **[View here]** button to create a new JWT app and enter any necessary  
information.  
**STEP 3**: Go to the '**App Credentials**' tab.  
**STEP 4**: Click on **[View JWT Token]** and copy the given token.  
**STEP 5**: Go to the '**Activation**' tab and click on the **[Activate your app]** button.  
**STEP 6**: In iMBRACE, paste the JWT token you copied with your Zoom API credentials.  
**DONE**: The credential can then be used for Zoom nodes.
