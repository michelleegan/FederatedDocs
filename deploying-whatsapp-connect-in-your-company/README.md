# Deploying WhatsApp Connect in Your Company

Before deploying WhatsApp Connect, your company will work closely with your Symphony Technical Account Manager and/or Solution Architect. Your TAM/SA will guide you step-by-step through the deployment.

## **A Note about WhatsApp Connect Phone Numbers**

The WhatsApp network routes conversations using a set of phone numbers provided to Symphony by your company during the initial setup of WhatsApp Connect. These phone numbers serve as the WABA \(WhatsApp Business API\) hooks for sending and receiving messages and are displayed to your clients. 

A WhatsApp Connect client requires one phone number for each conversation they participate in with your company. If the individual client has three conversions, then your company must have configured/authorized at least three phone numbers with Symphony.

Generally, Symphony recommends 10 phone numbers in production and 5 phone numbers for the test environment.  


## **Requirements to Use WhatsApp Connect**

### Your Internal Advisors

* can use WhatsApp Connect on Symphony Windows and Mac desktop and Symphony Android and iOS mobile.
* need to be entitled to use WhatsApp Connect to chat with clients. We explain how to [provision your employees](../untitled-1.md) with the appropriate WhatsApp Connect access later in this document. 

### Your External Clients

External clients can use WhatsApp as they normally do. As long as they have WhatsApp installed on their phone, WhatsApp Connect requires no additional software or installation for your clients. 

##  **Disclaimers**

Your disclaimers are defined in Symphony’s Admin Portal, including text and a rule for applying the text to messages that leave your company. Please refer to the _Disclaimers_ section in the [Symphony Administration Guide](https://docs.symphony.com/series/4099883-admin-guides) for more information.

WhatsApp Connect enables Symphony disclaimers to be used without modification. Because they are being sent externally, all WhatsApp Connect messages trigger the disclaimer rule. Your WhatsApp client will see the disclaimer as a distinct message in their app.  


