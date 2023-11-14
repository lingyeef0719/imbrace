# WhatsApp

WhatsApp allows messages to be sent and received using its Business Platform API. This allows  
developers and third-party apps to automatically communicate through WhatsApp.  

## Channel Integration

To begin, you will need: 
- **A [Meta business Suite](https://business.facebook.com/) account** - Full control.  See the [official help page](https://www.facebook.com/business/help/1710077379203657?id=180505742745347) here for more
information.  
\- Create a Mete Business Suite account with an existing Facebook or Instagram account and  
fill out your business informations.  
\-  If it is an existing Meta Business Suite, make sure you are the full control of the access users,  
or you need to be added as a full control by an existing full control user.  
- **A [Meta for Developers](https://developers.facebook.com/) account**  
\- Register a Meta for Developers account with an existing Facebook or Instagram account, and   
need a phone number to verify it.  
\- If a prior account is available, make sure it is one of the full control users in Meta Business  
Suite.  
- An Meta App in the Developer Dashboard with the **WhatsApp Business Platform** enabled. See  
the [official help page](https://developers.facebook.com/docs/development/create-an-app) for more information on creating apps. (Refer to the video 0:00 - 0:28)  
- **A phone number you want to register a WhatsApp business account on Meta**, and please  
make sure it is able to receive the SMS. (How to add a WhatsApp business number to Meta,
please refer to the video 0:28 - 1:45)  
- **A payment method** on Meta WhatsApp business account, this is the requirement by Meta for
the future message templates. (Starting April 1, 2023)

NOTE: 
**Do NOT** register the number on WhatsApp app.  **To be sure, the number is not yet registered  
onthe  mobile WhatsApp app**. If it is an existing WA account, please delete it first.  
(It can be already registered on Meta App, just follow our setup guide to change the webhook to  
iMBrace’s on Meta App and other settings.)  

**Connect to iMBrace**, please follow the steps below:  
**STEP 1**: Go to the **Meta for Developers Dashboard**.  
**STEP 2**: Navigate to the app to be used with the WhatsApp Business Platform.  
**STEP 3**: In iMBrace, create a new WhatsApp channel account, key in **WhatsApp Phone Number**,    
and copy the **Webhook URL** and **Verification Token**.  
**STEP 4**: In the Developer Console, in the left sidebar, go to **[WhatsApp] > [Configuration]**.  
**STEP 5**: Under Webhook, enter the **Callback URL (Webhook URL)** and **Verify token (Verification  
Token)** which copy from iMBrace. Next, click [Verify and save]. You can create your own token  
(For example: YIG579b), please make sure there is no space in the token.  
**STEP 6**: Under Webhook fields, subscribe to the fields you want. (In this case, messages)  
**STEP 7**: Turn on **[Live]** on the top side of the screen.  
**STEP 8**: If you haven’t provided your **Privacy Policy URL**, kindly go to **[Settings] > [Basic]** and  
provide your **Privacy Policy URL**.  
**STEP 9**: In the left sidebar, navigate to **[WhatsApp] > [Getting started]**.  
**STEP 10**: Under **Send and receive messages**, select the relevant phone number to be used, and   
copy the **Phone number ID** and **WhatsApp Business Account ID**.  
**STEP 11**: Go to the **[Business settings]**, add **System Users "Admin"**, and add **Assets**. Click  
**Generate new token (select an App and "Never" expired)** and copy it. (Please refer to the video  
3:42 – 4:53)  
**STEP 12**: In iMBrace, enter all three pieces of information in the corresponding fields. Then click  
**[Create]** and click **[Active]**.
**DONE**: The channel account can then be used to send and receive messages through WhatsApp using the WhatsApp  
and WhatsApp Trigger nodes.

## How to add WhatsApp business account payment method?
## (The requirement by Meta, starting April 1, 2023)

**STEP 1**: Go to Meta for Developers page and ckick **WhatsApp -> API Setup** on the sidebar menu,  
and then click **Add payment method** button on the bottom of the page.  
**STEP 2**: Pick the WhatsApp account you want to add the payment and click **Payment settings**,  
then follow the requirements to add the payment method.  
**DONE**: You will see the payment on the page
