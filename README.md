## accounts-dropbox

Dropbox Oauth2 login service for use with Meteor Auth

### Package Dependencies

* accounts-base
* accounts-oauth
* dropbox-oauth

### Usage

1. `mrt add accounts-dropbox`
2. Read the 'Integrating with Login Services' section of [Getting Started with Auth](https://github.com/meteor/meteor/wiki/Getting-started-with-Auth) and make sure you set up your config and secret correctly.
3. Call `Meteor.loginWithDropbox();`

`mrt` is a Meteorite command line tool. Visit [Meteorite's page](http://oortcloud.github.com/meteorite/) to learn more.

### Credits

* Shamelessly based on
[@yefim](https://github.com/yefim)'s LinkedIn OAuth2 login service