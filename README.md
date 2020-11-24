# What is this?

This is Postman collection for Tesla API (unoficial) to get started in minutes.

![mainimage](https://github.com/sugimomoto/TeslaAPIPostmanCollection/blob/master/Images/mainimage.png)

You can find Tesla API details at the following URL.

[Tesla API](https://www.teslaapi.io/)

# Notes

If you use this API, This API have to set Tesla account email and password, Also the access token for this API. 

You can get Access Token by this postman collection, However this access token can many control your tesla's functions.

Access Tokens can be expired by changing your Tesla account password.

# How to use Tesla API Postman Collection

## Import Postman collection and Environment

1. Download and register for [Postman](https://www.postman.com/).

2. Choose File | Import ....

![import](https://github.com/sugimomoto/TeslaAPIPostmanCollection/blob/master/Images/import.png)

3. Select Import From Link.

4. Paste the following two URLs and choose Import after each.

```url
https://github.com/sugimomoto/TeslaAPIPostmanCollection/raw/master/Tesla%20API%20Environment.postman_environment.json
```

```url
https://github.com/sugimomoto/TeslaAPIPostmanCollection/raw/master/Tesla%20API%20Environment.postman_environment.json
```

![importlink](https://github.com/sugimomoto/TeslaAPIPostmanCollection/blob/master/Images/importurl.png)

## Set up Environment and Access Token

1. Choose the No environment drop down in top right corner.

2. Select Tesla API environment.

![selectenvironment](https://github.com/sugimomoto/TeslaAPIPostmanCollection/blob/master/Images/selectenvironment.png)

3. Choose the eye icon to the right and then choose Edit.

Enter your Tesla Login Account email and password. Also, Enter Client Id and Client Secret for Tesla App.

Client Id and Client Secret are at the following URL.

[Tesla API OAuth](https://www.teslaapi.io/authentication/oauth)

![enteraccount](https://github.com/sugimomoto/TeslaAPIPostmanCollection/blob/master/Images/enteraccount.png)

4. Then, Choose oauth/Get Access Token request. Click SEND buttone and you can get access token from Tesla API.

![oauth](https://github.com/sugimomoto/TeslaAPIPostmanCollection/blob/master/Images/oauth.png)

5. Enter this access token at your Tesla API environment.

You are now up and running with the Tesla API collections.

By the way, Alomost requests have required your Tesla Id. You can find Id at Vehicles or Products Endpoint so you should request this endpoint first.

![getid](https://github.com/sugimomoto/TeslaAPIPostmanCollection/blob/master/Images/getid.png)

Enjoy your Tesla API life!
