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


