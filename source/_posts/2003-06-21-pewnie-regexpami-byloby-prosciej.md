---
date: 2003-06-21 12:24:34 +0200
layout: wycinki
tags: [pl, wycinki]
title: Pewnie regexpami byłoby prościej
---

chastell
: 
    ~~~
    foreach ($zawartosc as $linijka) {
      if (substr($linijka, 0, 1) == '.') {
        $kawalki = explode(' ', substr($linijka, 1));
        $zmienna = array_shift($kawalki);
        $opcje[$zmienna] = trim(implode(' ', $kawalki));
      }
    }
    ~~~
    {:.terminal}
: kocham tę robotę

Thoughtscriber
: kawałki, implode, explode
: ja rozumiem
: czemu Ty jesteś taki spokojny
: wyładowujesz agresję w tym tutaj
: potem już cisza błękitu
