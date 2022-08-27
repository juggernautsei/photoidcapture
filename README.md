# photoidcapture
Using a mobile device to capture client data

The purpose of this code is to show a way to capture data that is uploaded by the patient from a mobile device. 
The module is coded to only work with mobile devices and will block a desktop from accessing this module. 

As of this posting the access url looks like https://myehrlocation.com/capture/photo.php?sourse=pid&d=default.

D is for the name of the database to support the multi-site feature in OpenEMR

The code has been tested on IOS and android. Browsers tested are Safari, Chrome, Edge, and Brave.

The code is incomplete for a drop in integration with OpenEMR. It is can be completed to work with the patient portal or stand alone.

The has been some security considerations. One is to switch out the use of the pid for the p-uuid. That would be a lot harder to brute force. 

At this time my next steps is to import the uploaded image into the patient chart. This will further enhance the security of the upload.
