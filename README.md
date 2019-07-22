# messenger-chatbot

Chatbot setup on Messenger (Node.js)

Tutorial by blondiebytes: https://www.youtube.com/watch?v=bUwiKFTvmDQ

Setting up webhook for Facebook API V3.3 //updates for error: the parameter subscribed_fields is required

curl -i -X POST "https://graph.facebook.com/v3.3/me/subscribed_apps?subscribed_fields=message_deliveries,messages,messaging_optins&access_token=FB_PAGE_ACCESS_TOKEN"
