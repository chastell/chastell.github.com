---
date: 2004-04-25 23:54:08 +0200
layout: wycinki
tags: [pl, wycinki]
title: Wullfamorgenthalera trzeba będzie dopisać
---

~~~
shot@chastell:~/komiksy$ head -n6 ~/.dailystrips.defs
group te-lubie
   include adamathome calvinandhobbes dilbert foxtrot
   include garfield getfuzzy glasbergen hedge nonsequitur
   include patoliphant peanuts pearls pennyarcade
   include pvp thefifthwave toles userfriendly
end
shot@chastell:~/komiksy$ dailystrips -l @te-lubie
dailystrips 1.0.28 starting:
Operating in local mode

Retrieving URLS...done
Downloading strip files...done
shot@chastell:~/komiksy$ tree
.
|-- Adam@home-2004.04.25.gif
|-- Calvin and Hobbes-2004.04.25.gif
|-- Dilbert-2004.04.25.jpg
|-- FoxTrot-2004.04.25.gif
|-- Garfield-2004.04.25.gif
|-- Get Fuzzy-2004.04.25.jpg
|-- Non Sequitur-2004.04.25.gif
|-- Over the Hedge-2004.04.25.jpg
|-- Pat Oliphant-2004.04.25.gif
|-- Peanuts-2004.04.25.jpg
|-- Pearls Before Swine-2004.04.25.jpg
|-- Player vs. Player-2004.04.25.gif
|-- Randy Glasbergen-2004.04.25.gif
|-- The 5th Wave-2004.04.25.gif
|-- Tom Toles-2004.04.25.gif
|-- User Friendly-2004.04.25.gif
|-- dailystrips-2004.04.25.html
`-- index.html -> dailystrips-2004.04.25.html

0 directories, 18 files
~~~
{:.terminal}

Czemu nikt wcześniej mi o [tym](http://dailystrips.sourceforge.net/ 'apt-get install dailystrips') nie powiedział, hmmm?
