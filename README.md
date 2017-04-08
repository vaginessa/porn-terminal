Porn Terminal
=============

> Show random porn in your terminal.

[![Build Status](https://img.shields.io/travis/redaxmedia/porn-terminal.svg)](https://travis-ci.org/redaxmedia/porn-terminal)
[![PHP 7 Ready](https://php7ready.timesplinter.ch/redaxmedia/porn-terminal/badge.svg)](https://travis-ci.org/redaxmedia/porn-terminal)
[![Dependency Status](https://gemnasium.com/badges/github.com/redaxmedia/porn-terminal.svg)](https://gemnasium.com/github.com/redaxmedia/porn-terminal)
[![Latest Stable Version](https://img.shields.io/packagist/v/redaxmedia/porn-terminal.svg)](https://packagist.org/packages/redaxmedia/porn-terminal)
[![License](https://img.shields.io/packagist/l/redaxmedia/porn-terminal.svg)](https://packagist.org/packages/redaxmedia/porn-terminal)
[![GitHub Stats](https://img.shields.io/badge/github-stats-ff5500.svg)](http://githubstats.com/redaxmedia/porn-terminal)

![Porn Terminal](https://i.imgur.com/tLgfkDQ.png)


Installation
------------

```
git clone https://github.com/redaxmedia/porn-terminal.git
cd porn-terminal
composer install
```


Usage
-----

```
bin/porn-terminal [options]

-e/--api-endpoint <argument>
     Required. API endpoint. (actors, channels, dvds, videos)


-p/--api-provider <argument>
     Required. API provider. (porn.com, pornhub.com, redtube.com, spankwire.com, youporn.com)


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


Examples
--------

Show videos with metadata:

```
bin/porn-terminal -m
```

Show videos with big tits:

```
bin/porn-terminal -q ?tags=big-tits
```

Show actors by rating:

```
bin/porn-terminal -e actors -q ?order=rating
```

Show dvds by views:

```
bin/porn-terminal -e dvds -q ?order=views
```

Show videos from pornhub.com:
```
bin/porn-terminal -p pornhub.com
```

Show videos from youporn.com:

```
bin/porn-terminal -p youporn.com
```
