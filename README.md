# MyChat

## Description 
A Group video calling application using the Agora Web SDK with a Django backend.

##  How to use this source code

#### 1 - Clone repo


#### 2 - Install requirements

#### 3 - Update Agora credentals
replace the agora credentials in `views.py` and `streams.js`.

Create an account at agora.io and create an `app`

## views.py
```
def getToken(request):
    appId = "YOUR APP ID"
    appCertificate = "YOUR APPS CERTIFICATE"
    ......
```

###### streams.js

const APP_ID = 'YOUR APP ID'

and 

python manage.py runserver

Reference from @divanov11's YouTube channel.



![Screenshot 2024-05-18 142909](https://github.com/suss58/Live-group-video-chat-web-application-using-Django/assets/119553041/dd731335-cb09-44f6-93c8-673b55274a7a)


![Screenshot 2024-05-18 144727](https://github.com/suss58/Live-group-video-chat-web-application-using-Django/assets/119553041/ada03fbd-693e-43ce-b7d7-f5a567a5cb35)




