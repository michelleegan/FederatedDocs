# Provisioning Your Advisors for WhatsApp Connect

Before using WhatsApp Connect your advisors need to:

1. Be entitled for the WhatsApp Connect extension app, via the Symphony Connect API, by an Admin at your company.
2. Be enabled to use WhatsApp Connect on Symphony, by an Admin at your company. Admins can enable this using the Symphony REST API or Symphony Admin Portal. 

Users who have been entitled and enabled for WhatsApp Connect are able to view and access the app at the bottom of the navigation bar of the Symphony Desktop Application. 

If the advisor doesn’t have _both_ the entitlement and the enablement described above, the WhatsApp Connect application will not appear in that advisor’s instance of Symphony.  


## **Entitle Advisors for the WhatsApp Connect extension app**

Entitling an advisor to the WhatsApp Connect extension app gives that advisor the right to use WhatsApp Connect. \(Additionally, the advisor must be granted access to the extension app within Symphony, from either the Admin Portal or via API, as described in the next section, _Enable Advisors to Use WhatsApp Connect_.\) For more information, please refer to the [Symphony Connect API](https://federation.readme.io/reference#entitlements),  provided by Symphony for our customers to entitle and manage your WhatsApp Connect employees. 

This entitlement is also a precondition for assigning specific permissions according to the advisor’s role within your company, such as creating rooms and adding contacts. If you want to give the permission "create:room" to a advisor, this advisor must have the WhatsApp Connect entitlement as a prerequisite. Assigning permissions is explained later in this document.



## **Enable Advisors to Use WhatsApp Connect**

Once the advisor\(s\) in your company have the WhatsApp Connect entitlement, you can enable them for WhatsApp Connect in the __**Admin Portal** _or_ using the Symphony **REST API**.

### **via Symphony Admin Portal**

1. In the Symphony Admin Portal, locate the desired advisor in the BROWSE ACCOUNTS section of the navigation panel.
2. In the advisor’s APPLICATIONS tab, set WhatsApp & SMS Connect to _Enabled_, _Visible_, _Installed_ \(as shown below\).

### **via Symphony REST API**

Refer to \[which Symphony REST API page?\] to enable advisors for WhatsApp Connect.

**Note:** Advisors only need the WhatsApp & SMS Connect app set to _Enabled_, _Visible_, _Installed_ for managing contacts and rooms. If an advisor will have their contacts and relevant rooms created for them by someone else at your company \(and has any other required [permissions](untitled-2.md) assigned\), the advisor does not need the app to chat.   


