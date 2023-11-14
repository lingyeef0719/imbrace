# LINE
LINE allows messages to be sent and received using its Messaging API. This allows developers and  
third-party apps to automatically communicate through LINE.

## Channel Integration

To begin, you will need:  

- A LINE Official Account.
- A channel associated with the above account. For more information, see the [official help page](https://developers.line.biz/en/docs/messaging-api/getting-started/)  
for creating a channel.

**STEP 1**: Go to the [LINE Developers Console](https://developers.line.biz/console/).  
**STEP 2**: Navigate to the channel that will be used with the Messaging API.  
**STEP 3**: Under the **[Basic Settings]** tab, identify the **channel ID** and **channel secret**.  
**STEP 4**: Under the **[Messaging API]** tab, identify the **channel access token**.  
**STEP 5**: In iMBrace, create a new **LINE channel** account, and identify the **webhook URL**.  
**STEP 6**: Enter the channel ID, channel secret and channel token into the corresponding fields, then  
click **[Create]**.  
**STEP 7**: In the LINE Developers Console, under **Messaging API > Webhook Settings > Webhook  
URL**, add the webhook URL from iMBrace.

**DONE**: The channel account can then be used to send and receive messages through LINE using  
the LINE and LINE Trigger nodes.
