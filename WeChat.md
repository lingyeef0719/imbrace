# WeChat

WeChat (also known as Weixin) allows messages to be sent and received using its messaging API.  
This allows developers and third-party apps to automatically communicate through WeChat.  

## Channel Integration

To begin, you will need:  

- A WeChat Official account.  
- A server associated with the above account. For more information, see the [official  
documentation page](https://developers.weixin.qq.com/doc/offiaccount/en/Basic_Information/Access_Overview.html) for setting up a server.

**STEP 1**: In iMBrace, create a new **WeChat channel** account, and identify the **webhook URL**.  
**STEP 2**: Go to the [Weixin Official Accounts Platform](https://mp.weixin.qq.com/).  
**STEP 3**: In the left side-bar, go to **[设置与开发] (Settings and Development) > [基本配置] (Basic  
Configuration)**.  
**STEP 4**: Under **服务器配置 (Server Configurations)**, click **[修改配置] (Edit Configuration)** and enter  
the webhook URL from iMBrace in the **URL** field. Then click **[提交] (Submit)**.  
**STEP 5**: Identify the **令牌 (Token)** and **消息加解密密钥 (EncodingAESKey)**, and enter them into the  
corresponding fields in iMBrace.  
**STEP 6**: Under **公众号开发信息 (Official Account Development Information)**, identify the **开发者ID  
(AppID)** and **开发者密码 (AppSecret)**, and enter them into the corresponding fields in iMBrace.  
**STEP 7**: In the top-right corner, go to your account's **帐号详情 (Account Info)**. Scroll down to the **注  
册信息 (Registration information)** section and identify your **原始ID (Original ID)**, and enter this into  
the **Original ID** field in iMBrace.  
**STEP 8**: In iMBrace, click **[Create]**.
**DONE**: The channel account can then be used to send and receive messages through WeChat  
using the WeChat and WeChat Trigger nodes.
