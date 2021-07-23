---
description: 'reviewers: please confirm the code sample is correct'
---

# Appendix: Content Export Format

Below is an example of the Content Export \(XML format\).

```text



<?xml version='1.0' encoding='UTF-8'?>

<log xmlns:xs="http://www.w3.org/2001/XMLSchema"

   xmlns="http://www.symphony.com"

   xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" id="5158" podName="wech-na-uat-chat-glb-1" schemaVersion="1.5.9">

   <record id="1" recordType="SOCIAL MESSAGE" scope="PRIVATE" xsi:type="socialMessageRecordType" socialMessageType="INSTANT CHAT" platform="DESKTOP-40.0.0-10726-MacOSX-10.14.6-Chrome-79.0.3945.79" externalMessagingPlatform="WhatsApp">

       <threadId>TpoP90xujS7hxltR3p6hUX///pB6LQBGdA==</threadId>

       <messageId>KLALTThnYCkStf+UfCBPw3///pB6LNIAbQ==</messageId>

       <creationDate>

           <iso_8601>2020-01-08T15:43:27.231Z</iso_8601>

       </creationDate>

       <initiator>

           <user>

               <userId>351775001412115</userId>

               <companyUserEmail>jack.gs@symphony.com</companyUserEmail>

           </user>

       </initiator>

       <freeAttributes>

           <freeAttribute>

               <key>dist</key>

               <value>[351775001412115, 354455061004354]</value>

           </freeAttribute>

       </freeAttributes>

       <sentTo>

           <user>

               <userId>351775001412115</userId>

               <companyUserEmail>jack.gs@symphony.com</companyUserEmail>

           </user>

           <user>

               <userId>354455061004354</userId>

               <companyUserEmail>mario.brel@cba.com.cn</companyUserEmail>

           </user>

       </sentTo>

       <messageInfo contentType="text/plain" encoding="UTF-8" messageTimestamp="2020-01-08T15:43:27.231Z">

           <content><![CDATA[<html><body><div data-format="PresentationML" data-version="2.0" class="wysiwyg"><p>Hello Mario !</p></div></body></html>]]></content>

       </messageInfo>

   </record>

   <record id="2" recordType="SOCIAL MESSAGE" scope="PRIVATE" xsi:type="socialMessageRecordType" socialMessageType="INSTANT CHAT" platform="" externalMessagingPlatform="WhatsApp">

       <threadId>TpoP90xujS7hxltR3p6hUX///pB6LQBGdA==</threadId>

       <messageId>nGR/xgIkYHh5hhAPGrMkJX///pB6LE3DdA==</messageId>

       <creationDate>

           <iso_8601>2020-01-08T15:44:01.086Z</iso_8601>

       </creationDate>

       <initiator>

           <user>

               <userId>354455061004354</userId>

               <companyUserEmail>mario.brel@cba.com.cn</companyUserEmail>

           </user>

       </initiator>

       <freeAttributes>

           <freeAttribute>

               <key>dist</key>

               <value>[351775001412115, 354455061004354]</value>

           </freeAttribute>

       </freeAttributes>

       <sentTo>

           <user>

               <userId>351775001412115</userId>

               <companyUserEmail>jack.gs@symphony.com</companyUserEmail>

           </user>

           <user>

               <userId>354455061004354</userId>

               <companyUserEmail>mario.brel@cba.com.cn</companyUserEmail>

           </user>

       </sentTo>

       <messageInfo contentType="text/plain" encoding="UTF-8" messageTimestamp="2020-01-08T15:44:01.086Z">

           <content><![CDATA[Hey Jack! How are you? ]]></content>

       </messageInfo>

   </record>

   <record id="3" recordType="SOCIAL MESSAGE" scope="PRIVATE" xsi:type="socialMessageRecordType" socialMessageType="INSTANT CHAT" platform="DESKTOP-40.0.0-10726-MacOSX-10.14.6-Chrome-79.0.3945.79" externalMessagingPlatform="WhatsApp">

       <threadId>TpoP90xujS7hxltR3p6hUX///pB6LQBGdA==</threadId>

       <messageId>ycI+gO3Ev5PNu8bmeyIQvn///pB6LBrGbQ==</messageId>

       <creationDate>

           <iso_8601>2020-01-08T15:44:14.137Z</iso_8601>

       </creationDate>

       <initiator>

           <user>

               <userId>351775001412115</userId>

               <companyUserEmail>jack.gs@symphony.com</companyUserEmail>

           </user>

       </initiator>

       <freeAttributes>

           <freeAttribute>

               <key>dist</key>

               <value>[351775001412115, 354455061004354]</value>

           </freeAttribute>

       </freeAttributes>

       <sentTo>

           <user>

               <userId>351775001412115</userId>

               <companyUserEmail>jack.gs@symphony.com</companyUserEmail>

           </user>

           <user>

               <userId>354455061004354</userId>

               <companyUserEmail>mario.brel@cba.com.cn</companyUserEmail>

           </user>

       </sentTo>

       <messageInfo contentType="text/plain" encoding="UTF-8" messageTimestamp="2020-01-08T15:44:14.137Z">

           <content><![CDATA[<html><body><div data-format="PresentationML" data-version="2.0" class="wysiwyg"><p>你好</p></div></body></html>]]></content>

       </messageInfo>

   </record>

   <record id="4" recordType="SOCIAL MESSAGE" scope="PRIVATE" xsi:type="socialMessageRecordType" socialMessageType="INSTANT CHAT" platform="" externalMessagingPlatform="WhatsApp">

       <threadId>TpoP90xujS7hxltR3p6hUX///pB6LQBGdA==</threadId>

       <messageId>xrecwEQzstlqEf/ldgec6n///pB6K+73dA==</messageId>

       <creationDate>

           <iso_8601>2020-01-08T15:44:25.353Z</iso_8601>

       </creationDate>

       <initiator>

           <user>

               <userId>354455061004354</userId>

               <companyUserEmail>mario.brel@cba.com.cn</companyUserEmail>

           </user>

       </initiator>

       <freeAttributes>

           <freeAttribute>

               <key>dist</key>

               <value>[351775001412115, 354455061004354]</value>

           </freeAttribute>

       </freeAttributes>

       <sentTo>

           <user>

               <userId>351775001412115</userId>

               <companyUserEmail>jack.gs@symphony.com</companyUserEmail>

           </user>

           <user>

               <userId>351775001412116</userId>

               <companyUserEmail>john.bk@symphony.com</companyUserEmail>

           </user>           

           <user>

               <userId>354455061004354</userId>

               <companyUserEmail>mario.brel@cba.com.cn</companyUserEmail>

           </user>

       </sentTo>

       <messageInfo contentType="text/plain" encoding="UTF-8" messageTimestamp="2020-01-08T15:44:25.353Z">

           <content><![CDATA[I don't speak Chinese ]]></content>

       </messageInfo>

   </record>

   <record id="5" recordType="SOCIAL MESSAGE" scope="PRIVATE" xsi:type="socialMessageRecordType" socialMessageType="INSTANT CHAT" platform="DESKTOP-40.0.0-10726-MacOSX-10.14.6-Chrome-79.0.3945.79">

       <threadId>TpoP90xujS7hx85rtp6hUX///pB6LQBGdA==</threadId>

       <messageId>ycI+grgT7Nfst8bmeyIQvn///pB6LBrGbQ==</messageId>

       <creationDate>

           <iso_8601>2020-01-08T15:43:14.137Z</iso_8601>

       </creationDate>

       <initiator>

           <user>

               <userId>351775001412115</userId>

               <companyUserEmail>jack.gs@symphony.com</companyUserEmail>

           </user>

       </initiator>

       <freeAttributes>

           <freeAttribute>

               <key>dist</key>

               <value>[351775001412115, 351775001412116]</value>

           </freeAttribute>

       </freeAttributes>

       <sentTo>

           <user>

               <userId>351775001412116</userId>

               <companyUserEmail>john.bk@symphony.com</companyUserEmail>

           </user>

       </sentTo>

       <messageInfo contentType="text/plain" encoding="UTF-8" messageTimestamp="2020-01-08T15:44:14.137Z">

           <content><![CDATA[<html><body><div data-format="PresentationML" data-version="2.0" class="wysiwyg"><p>Let's go</p></div></body></html>]]></content>

       </messageInfo>

   </record>

   <manifest>

       <userlist>

           <userDetails>

               <userId>351775001412115</userId>

               <userName>jack.gs@symphony.com</userName>

               <companyUserEmail>jack.gs@symphony.com</companyUserEmail>

               <isPerson>true</isPerson>

               <firstName>Jack</firstName>

               <lastName>GS</lastName>

               <freeAttributes>

                   <freeAttribute>

                       <key>company</key>

                       <value>Symphony Platform Solutions Development</value>

                   </freeAttribute>

               </freeAttributes>

           </userDetails>

           <userDetails>

               <userId>351775001412116</userId>

               <userName>john.bk@symphony.com</userName>

               <companyUserEmail>john.bk@symphony.com</companyUserEmail>

               <isPerson>true</isPerson>

               <firstName>John</firstName>

               <lastName>BK</lastName>

               <freeAttributes>

                   <freeAttribute>

                       <key>company</key>

                       <value>Symphony Platform Solutions Development</value>

                   </freeAttribute>

               </freeAttributes>

           </userDetails>

           <userDetails>

               <userId>354455061004354</userId>

               <userName>+33652485367</userName>

               <companyUserEmail>mario.brel@cba.com.cn</companyUserEmail>

               <isPerson>true</isPerson>

               <prettyName>Mario Brel [WhatsApp]</prettyName>

               <freeAttributes>

                   <freeAttribute>

                       <key>company</key>

                       <value>C&B Associates</value>

                   </freeAttribute>

               </freeAttributes>

           </userDetails>

       </userlist>

       <userCount>3</userCount>

       <firstRecord>1</firstRecord>

       <recordCount>5</recordCount>

   </manifest>

</log>



```

