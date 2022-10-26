---
Title: Intune Configuration Changes using Logic App with no governance needed
Authors: Mattias Melkersen
Owner: Mattias Melkersen
Date: 26.10.2022
Description: Report on who did any changes in your Intune environment
---
  [![HitCount](https://hits.dwyl.com/MSEndpointMgr/LogicAppCode.svg?style=flat)](http://hits.dwyl.com/MSEndpointMgr/LogicAppCode)

# Logic app code
## The following code can be put directly into your logic app and work if you configured your envionment described in the [MSEndpointMgr Blog](https://msendpointmgr.com/2022/10/23/installing-m365-apps-as-win32-app-in-intune/)

1. copy the code from LogicApp code

2. Put your logic app in codeview

3. Paste it in

4. Replace in line 112 where it says a32a07c5-739b-40ce-9b3f-185733d5c0d0 and add your own Log Analytics workspace ID

5. Replace in line 225 where it says https://memtipsandtricks.webhook.office.com/webhookb2/d20c5efe-2f76-4897-8c90-2de8c0f76397@47a13e20-6415-4467-bfd3-b2acf62a3ed2/IncomingWebhook/ and add your own Teams hook