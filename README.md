# Simple-Smartthings-Connector-On-Red-Node
Simple Smartthings Connector On Red Node


This is a simple cloud-to-cloud connection between Node Red devices and SmartThings. It is written as a SmartApp connector by way of an Node Red flow. As this is fully cloud-to-cloud, a SmartThings hub is not required.

It's a base for a developement: in my case, it's to connect my Texecom Alarm to Smartthings

For security purporse and because you need to expose your Node Red on Internet, you need:
- Set User/Password on your Node Red
- use SSL on Node Red or with a reverse proxy
- IP Filter if you can

Next step:
-Add friendly interface
-Catch Error
-IP filter in the flow


Any Help are Welcome to help me to finish this project.

Set-up Instructions: To Be Define

Current limitations:

    No Authentication server use, only a simple check of Client ID and Secret ID
    Only one user supported
    No catch error for the moment
    No friednfly UI
    
