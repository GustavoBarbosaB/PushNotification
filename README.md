# PushNotification
Um exemplo de push notification com FCM.

Para testar o PUSH com Postman:

POST /fcm/send HTTP/1.1
Host: fcm.googleapis.com
Content-Type: application/json
Authorization: key=AAAAPwYkEOY:APA91bFc41l_dL_ZU0eKAZxRKr7YlyWXEo9E1Vt_rQ3b8t6JultNs8WWD8Tx1i7ADLW6v0Y_-4dvNE5KA8rbhE0Y_Dn4DS6QoJS8EYp1zfiIjCtew5vW7X4Sw-lTTVG6pLI0SqeeXSuR
Cache-Control: no-cache
Postman-Token: f2494879-cd6a-4ff6-8bf4-07cb28037ed2

{
  "to":"fizUXc95XWc:APA91bFT23LKD15AuSzFVr2j_icg9-raxcQEH3ZCmKLYm6wIBPmA0L5-dMWrF6XC8NeSy8gktq-2wwhizScbmTYqCmjMIb_Y6Db4ILZJVBCdjZnMLzLS7jcoxmWaN-PUG_yDvd9IEaGZ",
  "data": {
    "title": "Gustavo teste",
    "message": "O melhor estagiário de Uberlândia!"
  }
}"account_id": 36495
}
