# Video Quickstart for PHP and Twilio

This application should give you a ready-made starting point for writing your
own video chatting apps with Twilio Video. Before we begin, we need to collect
all the credentials we need to run the application:

Credential | Description
---------- | -----------
Twilio Account SID | Your main Twilio account identifier - [find it on your dashboard](https://www.twilio.com/console).
API Key | Used to authenticate - [generate one here](https://www.twilio.com/user/account/messaging/dev-tools/api-keys).
API Secret | Used to authenticate - [just like the above, you'll get one here](https://www.twilio.com/user/account/messaging/dev-tools/api-keys).

## A Note on API Keys

When you generate an API key pair at the URLs above, your API Secret will only
be shown once - make sure to save this in a secure location, 
or possibly your `~/.bash_profile`.

## Setting Up The Application

I hosted the application on *Heroku* and tested. 
Below image shows the working model on heroku.

![screenshot of chat app](https://ibb.co/himaK5)

In other case you can also run it on PHP server using the command

```bash
php -S 127.0.0.1:8000
```

## License
MIT
