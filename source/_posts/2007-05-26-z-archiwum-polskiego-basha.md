---
date: 2007-05-26 14:19:59 +0200
layout: wycinki
tags: [pl, wycinki]
title: Z archiwum polskiego Basha
---

chastell
: <blockquote><p>— Taka mrożona kawa to ile ma espresso w środku?</p><p>— Jedno.</p><p>— A taką z dwóch dałoby się zrobić?</p><p>— Jasne.</p><p></p></blockquote>

opi
: więc jak już mówiłem
: BlackBerry nie obsługuje sieci
: tylko e-maile
: prawda?

chastell
: nie wiem.
: (prawda?)

opi
: no więc działa tylko e-mail
: wczoraj zrobiłem sobie `rss2email`
: a dziś

chastell
: A DZIŚ DZIAŁA TYLKO RSS.
: więc! musisz! zrobić! `email2rss`!
: (dobratakawa.)

opi
: `/etc/aliases`
: 
    ~~~
    url: "| /home/emil/bin/url.sh"
    ~~~
    {:.terminal}
: 
    ~~~
    #!/bin/bash
    tofetch=`grep http:// -`
    echo $tofetch >> /tmp/reqlog.log
    tofetch=${tofetch} # trimmmm, biacz.
    if [ "$tofetch" = "" ]; then
      # put whine here
      exit;
    else
      mail_body=`elinks -dump $tofetch`
      echo $mail_body | mail -s {$tofetch} junkyard
    fi
    ~~~
    {:.terminal}
: ślę e-maila, wraca strona

chastell
: o no prosz.
: tak właśnie BlackBerry rozwija kre-a-tyw-ność.

opi
: Ty, nie pij już tego
: zęby Ci nie dzwonią?

chastell
: trudno powiedzieć.

opi
: (o ja, o ja! wysłałem sobie na url@[…] http://slashdot.org i wrócił slashdot. I LOVE UNIX!!!11!!!)

I nerdocore’owy [komentarz polityczny](wycinki/dziendemokracji.png '18. rocznica wolnych wyborów') też mamy.
