---
date: 2003-09-30 10:36:09 +0200
layout: wycinki
tags: [pl, wycinki]
title: Podpuścił mnie, skubany
---

dmr
: cześć
: pytanie kontrolne mam
: jak się sprawuje Linux?
: i na Debianie ostatecznie stanęło?

chastell
: mhm
: no więc tak:
: ciongasz [stable mini-ISO](http://www.debian.org/CD/netinst/ 'stable, bo w testing instaler jest *eksperymentalny*')
: wypalasz
: instalujesz
: `vi /etc/apt/sources.list`
: `:%s/stable/testing/g`
: `apt-get update`
: `apt-get dist-upgrade`
: i potem już tylko `apt-get install` co trzeba
: a, jeszcze
: sobie dopisać unstable
: bo np. KDE 3 jest na razie tylko w unstable chyba

dmr
: aha

chastell
: generalnie
: `http://wiki.debian.net/?DebianKDE`
: i jeszcze `http://www.debianusers.pl/article.php?aid=5`
: i jesteś ustawiony
: jakby co to pytaj
: jak już będziesz miał brykające KDE to oczywiście `apt-get install lbreakout2`

dmr
: no więc z tą demagogią to jest tak, że
: ja tylko pytałem co z Twoim systemem
