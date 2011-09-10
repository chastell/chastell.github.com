---
date: 2007-06-22 21:52:59 +0200
layout: wycinki
tags: [pl, wycinki]
title: (Chcę Ci powiedzieć „uważaj na te drogi” ale nie mam odwagi)
---

chastell
: <pre class='terminal'>shot@devielle:~$ sudo /etc/init.d/amavisd <a href='http://images.google.com/images?q=sotp' title='no przecież'>sotp</a></pre>
: mam ochotę wszystko pierdolnąć i iść się upić
: debuguję błędy między naszym SOAP-em a Drupalem
: a sudo mi się wcina
: 
    ~~~
    shot@devielle:~$ sudo /etc/init.d/amavis debug
    Password:
    No soap, honkie-lips.
    ~~~
    {:.terminal}
: …

opi
: huh

chastell
: no, złe hasło
: mam `insults` ustawione w `/etc/sudoers`
: 
    ~~~
    shot@devielle:~$ sudo /etc/init.d/amavis debug
    Password:
    No soap, honkie-lips.
    Password:
    You silly, twisted boy you.
    Password:
    Trying to run amavisd-new in debug mode...
    ~~~
    {:.terminal}

opi
: ostatnie najgorsze!
: amavis in debug mode
: …and your mother is a hamster

---

(Bo bywają takie dni, że nic nie wchodzi, od rana do wieczora – choć przecież jeszcze wczoraj z rozważań <cite>mealer</cite>? <cite>george</cite>? <cite>syfun</cite>? <cite>symfuny</cite>? tak gładko wyszedł <cite>art décomp</cite>.)

---

chastell
: <dl><dt>opi</dt><dd><code>9] => 11     [10] => 12     [11] => 46     [12] => 6     [13] => 7     [14] => 8 ) Array (     [0] => 1     [1] => 2     [2] => 3     [3] => 14     [4] => 4     [5] => 10     [6] => 22     [7] => 9     [8] => 5     [9] => 11     [10] => 12     [11] => 46     [12] => 6     [13] => 7     [14] => 8 ) Array (     [0] => 1     [1] => 2     [2] => 3     [3] => 14     [4] => 4     [5] => 10     [6] => 22     [7] => 9     [8] => 5     [9] => 11     [10] => 12     [11] => 46     [12] => 6     [13] => 7     [14] => 8 ) Array (     [0] => 1     [1] => 2     [2] => 3     [3] => 14     [4] => 4     [5] => 10     [6] => 22     [7] => 9     [8] => 5     [9] => 11     [10] => 12     [11] => 46     [12] => 6     [13] => 7     [14] => 8 ) Array (     [0] => 1     [1] => 2     [2] => 3     [3] => 14     [4] => 4     [5] => 10     [6] => 22     [7] => 9     [8] => 5     [9] => 11     [10] => 12     [11] => 46     [12] => 6     [13] => 7     [14] => 8 ) Array (     [0] => 1     [1] => 2     [2] => 3     [3] => 14     [4] => 4     [5] => 10     [6] => 22     [7] => 9     [8] => 5     [9] => 11     [10] => 12     [11] => 46     [12] => 6     [13] => 7     [14] => 8 ) Array (     [0] => 1     [1] => 2     [2] => 3     [3] => 14     [4] => 4     [5] => 10     [6] => 22     [7] => 9     [8] => 5     [9] => 11     [10] => 12     [11] => 46     [12] => 6     [13] => 7     [14] => 8 ) Array (     [0] => 1     [1] => 2     [2] => 3     [3] => 14     [4] => 4     [5] => 10     [6] => 22     [7] => 9     [8] => 5     [9] => 11     [10] => 12     [11] => 46     [12] => 6     [13] => 7     [14] => 8 ) Array (</code></dd></dl>
: dzień jak co dzień
: przyznasz, że w tym świetle nieźle się trzymam.

M.
: oszczędź mi
: bo zacznę się dopytywać
: co to jest
: i będziesz musiał gęsto się tłumaczyć

chastell
: opi tego nie rozumie
: więc ja nawet nie mam szans
: <dl><dt>opi</dt><dd>Matrix to nic</dd><dd><code>w==4882 w2==4882 deklaracja_id==46866 nazwa_kol==kol_18</code></dd><dd>z debuga</dd><dd>właśnie to muszę zamienić na „brak danych”</dd><dd>muszę poleżeć na ziemi z tym problemem</dd></dl>
: to ciekawe, Mover robi to samo
: kładzie się na podłodze w biurze i leży
: potem go budzę[^1]

M.
: fajne chłopaki

---

(W niedzielę wieczorem udaliśmy się na godzinny spacer w Kabaty, ale niestety majaczące w drodze powrotnej zabudowania Metra okazały się domkiem w Powsinie. Powiśle, Wola i Mokotów – ulica każda, każdy dom, ale tam, cóż, [trochę nam nie poszło](http://maps.google.com/maps/ms?msa=0&t=h&msid=103528977183740090396.000001133d1408c9c455b&ll=52.138229,21.080704&spn=0.053627,0.11673&z=13&om=1 'per pedes ad astra'). Dobrze, że ostatnie metro z Natolina to o 0<sup>43</sup> jest.)

[^1]: no, raz się zdarzyło…
