# Enable Advisors to Connect with Clients: Permission to Use the Onboarding App

The onboarding app allows designated advisors at your company to create connections with external clients using WhatsApp Connect. An Admin at your company grants an advisor permission to the onboarding app via either the **Admin Portal** _or_ the **Connect APIs**.

## **Designating Advisors to Onboard – Who Needs Access?**

Your company can decide whether to:

* provide _all_ your WhatsApp Connect advisors access to the onboarding app so they can onboard their own contacts

or 

* provide only _designated advisors_ access to the onboarding app – these designated individuals are able to onboard a client **on behalf of** another advisor. 

\*\*\*\*

## **Grant Onboarding Permission via Symphony Admin Portal**

Once the advisor\(s\) in your company who will be onboarding clients have the WhatsApp Connect entitlement, you can set them up with permission to use the onboarding app as follows:

1. In the Symphony Admin Portal, locate the desired advisor in the BROWSE ACCOUNTS section of the navigation panel.
2. In the APP SETTINGS tab, set WhatsApp Onboarding to _Enabled_, _Visible_, _Installed_ \(as shown below\).

## Grant Onboarding Permission via the Connect API ****

**create:contact**  
The advisor is allowed to onboard and manage contacts. The New Contact button is available to an advisor with this permission, and contact fields are editable.  
****

**on-behalf:onboard**  
The advisor is allowed to onboard contacts on behalf of other advisors at your company.  
****

**on-behalf:simple-offboard**  
The advisor is allowed to remove contacts on behalf of other advisors at your company.  
****

For further information, please refer to the Symphony Federation API Reference Guide. [https://federation.readme.io/reference\#permissions](https://federation.readme.io/reference#permissions)  


