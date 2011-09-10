---
date: 2003-01-08 00:31:21 +0100
layout: wycinki
tags: [pl, wycinki]
title: Drug dealer, and proud of it
---

Tak się ostatnio zastanawiałem, czy jeśli będę tu pisał plus/minus codziennie, to ktokolwiek będzie w stanie to wszystko czytać.

Postanowiłem więc zrobić Test.

~~~
shotpl=# SELECT substring(czas for 16) AS kiedy
FROM statystyki WHERE adres = 'bestia.chlip.pl'
AND uri LIKE '%wycinki/' ORDER BY kiedy DESC;
      kiedy       
------------------
 2003-01-06 10:26 
 2003-01-05 16:11 
 2003-01-05 12:37 
 2003-01-05 02:22 
 2003-01-04 13:23 
 2003-01-03 16:27 
 2003-01-03 09:18 
 2003-01-03 09:17 
 2003-01-02 17:02 
 2003-01-01 20:33 
~~~
{:.terminal}

A potem coś mnie Tknęło.

~~~
shotpl=# SELECT adres, count(*) AS ile FROM
statystyki WHERE czas > '2003-01-01' AND uri
LIKE '%wycinki/' GROUP BY adres ORDER BY ile DESC;
            adres             | ile 
------------------------------+-----
 systemy114.toya.net.pl       |  22 
 aah158.warszawa.sdi.tpnet.pl |  17 
 180-moc-3.acn.waw.pl         |  11 
 bestia.chlip.pl              |  10 
~~~
{:.terminal}

Panowie, mi jest bardzo miło, ale zaczynam się o Was niepokoić…

([22 wizyty](http://tenteges.net/ 'systemy114.toya.net.pl = Klus') w tym roku? _Dwadzieścia dwie‽_)
