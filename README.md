Porn Terminal
=============

> Show random porn in your terminal.

[![Build Status](https://img.shields.io/travis/redaxmedia/porn-terminal.svg)](https://travis-ci.org/redaxmedia/porn-terminal)
[![PHP 7 Ready](https://php7ready.timesplinter.ch/redaxmedia/porn-terminal/badge.svg)](https://travis-ci.org/redaxmedia/porn-terminal)
[![Dependency Status](https://gemnasium.com/badges/github.com/redaxmedia/porn-terminal.svg)](https://gemnasium.com/github.com/redaxmedia/porn-terminal)
[![License](https://img.shields.io/packagist/l/redaxmedia/porn-terminal.svg)](https://packagist.org/packages/redaxmedia/porn-terminal)
[![GitHub Stats](https://img.shields.io/badge/github-stats-ff5500.svg)](http://githubstats.com/redaxmedia/porn-terminal)

![Porn Terminal](https://i.imgur.com/tLgfkDQ.png)


Usage
-----

Run `php bin/porn-terminal` in your terminal.


Examples
--------

Run `php bin/porn-terminal -q ?tags=big-tits` to search for videos with big tits.

Run `php bin/porn-terminal -e actors -q ?order=rating` to search for actors by rating.

Run `php bin/porn-terminal -e dvds -q ?order=views` to search for dvds by views.

Run `php bin/porn-terminal -p pornhub.com` to search for videos on pornhub.com.

Run `php bin/porn-terminal -p youporn.com` to search for videos on youporn.com.


Options
-------

Run `php bin/porn-terminal --help` for help:

```
-e/--api-endpoint <argument>
     Required. API endpoint. (porn.com: videos, actors, channels, dvds; pornhub.com: videos; youporn.com: videos)


-p/--api-provider <argument>
     Required. API provider. (porn.com, pornhub.com, youporn.com)


-q/--api-query <argument>
     API query.


-d/--image-dither
     Dither of the image.


-g/--image-grayscale
     Grayscale of the image.


--help
     Show the help page for this command.


-i/--image-invert
     Invert the image.


-m/--image-metadata
     Metadata of the image.


-r/--image-resize <argument>
     Resize the image.


-w/--image-weight <argument>
     Weight of the image.


-o/--open-browser
     Open URL in browser.
```