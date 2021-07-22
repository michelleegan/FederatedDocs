# SMS Connect Administrators Guide

## Introduction

With WhatsApp Connect, Symphony has created a safe way for banks and other financial institutions to communicate with clients on WhatsApp while keeping that communication secure and available for compliance to monitor. 

WhatsApp Connect is:

* An API integration between Symphony and WhatsApp, enabling compliance export of all messaging content
* A completely native experience—employees use WhatsApp exactly the way they use it for other chats

WhatsApp Connect is a gateway between WhatsApp and the Symphony network. It allows Symphony users within your company to initiate connections and chat directly with external clients on WhatsApp, without requiring your employees to use personal unsecured WhatsApp accounts. 

This guide provides an architecture and security overview, explains how to set up and use Symphony’s WhatsApp Connect solution, and answers common support questions.  


### **Symphony Compliance Features**

WhatsApp Connect protects your employees and the whole organization with the following features:

**Access Control.** Employees must be granted access by an Administrator before they can use WhatsApp Connect. 

**Onboarding Control.** You can designate specific  ****employees as permitted to establish client connections in WhatsApp Connect \(referred to as onboarding\). Employees entitled to onboard can establish connections for other employees.

**Real-time Conversation Monitoring.** For sensitive exchanges, your compliance officers can silently observe conversations in real-time Conversation History. WhatsApp conversations are included in the content delivered to the retention archive via Symphony Content Export.

**Expression Filters.** Prevent certain terms from being entered into chat room conversations.

**Disclaimers.** Displayed based on  settings you configure in the Symphony Admin Portal.

**Terms of Use.** Links to your terms of use can be included in the client onboarding process.

### **WhatsApp Connect Architecture**

The WhatsApp Connect architecture consists of a Symphony/WhatsApp gateway, provided via Symphony’s Connect platform, and an Onboarding App. The diagram also shows the Content Export Bridge used for retrieving the customer’s conversation history and the Symproxy used for DLP \(if implemented in your company\) and Malware Scanning \(if file attachments are activated for your company\).



  


