# Chatbot

## Table of Content
* [CDK Global](#cdk-global)
* [Facebook Messenger](#facebook-messenger)
* [PowerBot Agent](#powerbot-agent)

## CDK Global
* [CDK Global Developers](https://www.cdkglobal.com/en-gb/partners/developers)
* [CDK Partner Platform: Sales Domain](https://portal.online-test.cdkapps.eu/#/)

## Facebook Messenger
* [Messenger Settings](https://www.facebook.com/majorpowersports/settings/?tab=messenger_platform)
* PowerBot 592580637840656
### Messenger Platform
#### Response Method
Responses are partially automated, with some support by people
#### Link Your App to Your Page (Shared Attribution) 
- This allows content to be fully displayed and properly attributed when shared between native apps, your Page, chat extension and Messenger bot.
#### Whitelisted Domains
- Third-party domains that are accessible in the Messenger webview for use with the Messenger Extensions SDK, and for Messenger plugins. https://www.majorpowersports.com/
#### Messenger Link
- [m.me/majorpowersports](m.me/majorpowersports)
#### Advanced Messaging Features
* [Subscription Messaging (BETA)](https://developers.facebook.com/docs/messenger-platform/policy/policy-overview/#subscription_messaging)
* Info About People	
#### Customer Chat Plugin
Let people start a conversation on your website and continue in Messenger. 
* [Customer Chat Plugin](https://developers.facebook.com/docs/messenger-platform/discovery/customer-chat-plugin)
```javascript
<!-- Load Facebook SDK for JavaScript -->
<div id="fb-root"></div>
<script>(function(d, s, id) {
  var js, fjs = d.getElementsByTagName(s)[0];
  if (d.getElementById(id)) return;
  js = d.createElement(s); js.id = id;
  js.src = 'https://connect.facebook.net/en_US/sdk/xfbml.customerchat.js';
  fjs.parentNode.insertBefore(js, fjs);
}(document, 'script', 'facebook-jssdk'));</script>

<!-- Your customer chat code -->
<div class="fb-customerchat"
  attribution=setup_tool
  page_id="1526269314258118">
</div>
```
## PowerBot Agent
The agent should perform the following tasks:
* Inform customers about the hours of operation
* Schedule service appointments for customers
* Schedule sales appointments for customers
