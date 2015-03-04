# Twitch Now

* Chrome version: https://chrome.google.com/webstore/detail/twitch-now/nlmbdmpjmlijibeockamioakdpmhjnpk
* Firefox version: https://docs.google.com/file/d/0BykW-NfUUzm5Z2RCWmcxTmQ5cEk
* Opera version: https://addons.opera.com/extensions/details/twitch-now/

## Requirements

* Node.js
* Grunt

## How to build

Before all, you need to install dependencies:
```
$ npm install
```

To build Chrome version:
```
$ grunt chrome
```

To build Firefox version:
```
$ grunt firefox
```

To run Firefox version:
```
$ grunt mozilla-cfx
```

To build Opera version:
```
$ grunt opera
```

## Translation guide

This guide will help you to get prepared for translation. Let's start!

1.  Register your account first. 
2.  Visit the project page again and choose "Fork" option available in top-right corner. This will copy whole repository to your account.
3.  Hit plus icon to create new translation file in "_locales" directory. If your language directory does not exists yet, feel free to create one (https://developer.chrome.com/webstore/i18n#localeTable)
4.  When you're done, you can now commit and push your changes. The new files will appear on you Github account.
5.  You're almost done. The only thing left is to create a pull request so I can see that you want to apply your changes. To do it, press the "Pull request" button. Make sure, the target repository is correct and press "Send pull request"
