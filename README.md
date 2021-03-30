# What is this?

This is Postman collection for Tesla API (unoficial).

![overview](/Images/mainimage.png)

You can find Tesla API details at the following URL.

[Tesla API](https://www.teslaapi.io/)

# Notes

You can get an Access Token for the Tesla API by using this postman collection. This access token can control your tesla's functions.

Access Tokens can be expired by changing your Tesla account password.

# How to use Tesla API Postman Collection

## Import Postman collection and Environment

1. Download and register for [Postman](https://www.postman.com/).

2. Choose File | Import ....

![import](/Images/import.png)

3. Select Import From Link.

4. Paste the following two URLs and choose Import after each.

```url
https://github.com/sugimomoto/TeslaAPIPostmanCollection/raw/master/Tesla%20API%20Postman%20Collection%20(Unofficial).postman_collection.json
```

```url
https://github.com/sugimomoto/TeslaAPIPostmanCollection/raw/master/Tesla%20API%20Environment.postman_environment.json
```

![importlink](/Images/importurl.png)

## Set up Environment and Access Token

1. Choose the No environment drop down in top right corner.

2. Select Tesla API environment.

![selectenvironment](/Images/selectenvironment.png)

3. Choose the eye icon to the right and then choose Edit.  
Enter a random string of characters for the OAuth2 State. Enter the Client ID, and Client Secret for the Tesla App.  
Client Id and Client Secret are at the following URL.  
[Tesla API OAuth](https://www.teslaapi.io/authentication/oauth)

![enteraccount](/Images/enteraccount.png)

4. Open Get Access Token. Click on the Authorization tab. Scroll down and click Get New Access Token.

![authorizationtab](/Images/authorizationtab.png)

5. Sign into your Tesla Account.

![signintotesla](/Images/teslasignin.png)

6. Click on Use Token. You can safely delete any expired tokens from Postman (indicated with strikethrough text).

![usetoken](/Images/usetoken.png)

7. Click Send to obtain an Access Token.
![oauth](/Images/oauth.png)  
You are now up and running with the Tesla API collections.

To refresh your token, repeate steps 4 through 7.  

By the way, most requests have required your Tesla Id. You can find Id at Vehicles or Products Endpoint so you should request this endpoint first.

![getid](/Images/getid.png)

Enjoy your Tesla API life!
