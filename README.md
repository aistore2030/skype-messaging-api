# skype-messaging-api

In this repository we will expose api details using that you can send message to users skype account This is very easy and api calls are REST API

This consists of two stage for sender and one stage for the user.

For sender

Step 1 : Add your portal in the skype bot and get the permission key 
If you do not want to use REST API for this you can also use buyit command from the skype account and it will ask few questions 

Step 2 : Call REST API and send your message

end points 
/api/CustomWebApi

Parameters 
1 notificationMessage 
2 token

Example : http://localhost:3978/api/CustomWebApi?notificationMessage=youmessage&token=yourtoken this url will hit and send your message to roboM


For the user their are two step also

Step 1 : Subscribe a portal

From the skype user need to type subscribe domainname only 








