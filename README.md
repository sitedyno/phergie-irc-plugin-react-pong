# [DEPRECATED]phergie/phergie-irc-plugin-react-pong

:exclamation: As of [Phergie Irc Client React](https://github.com/phergie/phergie-irc-client-react)
version 3 and higher this plugin's functionality is provided by the Client.
**If starting a new project you cannot use this plugin!**

A plugin for [Phergie](http://github.com/phergie/phergie-irc-bot-react/) to
respond to server ping events.

[![Build Status](https://secure.travis-ci.org/phergie/phergie-irc-plugin-react-pong.png?branch=master)](http://travis-ci.org/phergie/phergie-irc-plugin-react-pong)

## Install

The recommended method of installation is [through composer](http://getcomposer.org).

```JSON
{
    "require": {
        "phergie/phergie-irc-plugin-react-pong": "1.0.*"
    }
}
```

See Phergie documentation for more information on installing plugins.

## Configuration

This plugin requires no configuration.

## Tests

To run the unit test suite:

```
curl -s https://getcomposer.org/installer | php
php composer.phar install
./vendor/bin/phpunit
```

## License

Released under the BSD License. See `LICENSE`.
