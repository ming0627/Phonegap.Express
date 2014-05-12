#Phonegap.Express

> Phonegap Express is a prototype built on MongoDB, nodeJS and Kendo UI to demonstrate accessing a RESTful JSON api secured with oAuth 2.0 in browsers and Phonegap

##Architecture and directories



##Requirements

- Install mongoDB from http://www.mongodb.org/downloads
- Install nodejs from http://nodejs.org/download/
- Run setup.cmd (on Windows)

##Configuration

### API server address

You can change the IP port of the API server at https://github.com/jlchereau/Phonegap.Express/blob/master/config/development.json

The client (browser or Phonegap) gets the location of the API server from https://github.com/jlchereau/Phonegap.Express/blob/master/www/js/api.js#L40

Windows Live does not authorize localhost as an application server, which can be worked around by configuring %SystemRoot%\system32\drivers\etc\hosts

### oAuth provider configuration

Follow the instructions at:

- Facebook: https://developers.facebook.com/apps/
- Google: https://console.developers.google.com/project
- Twitter: https://apps.twitter.com/app/
- Windows Live:
- Yahoo?

Then update the clientID and clientSecret for all providers in https://github.com/jlchereau/Phonegap.Express/blob/master/config/development.json

##Execution and tests


