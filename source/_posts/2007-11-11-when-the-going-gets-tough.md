---
date: 2007-11-11 21:08:04 +0100
layout: wycinki
tags: [pl, wycinki]
title: When the going gets tough, the tough use print()
---

Dawno[^1] nic nie debugowałem, więc dziś będzie o tej właśnie, jakże bliskiej sercu każdego programisty, czynności. Oraz kilku równie bliskich. Przeglądowo tak. Dla odmiany z [Bronikowskim](http://bronikowski.com/ 'geekin’ skank') w roli głównej, skoro się tak stęskniliście[^2].

(Chciałem może dla odmiany mniej tylko-cytatowo, ale okazało się, że czas na <code>./configure --prefix /opt/<a href='http://wesnoth.org/' title='tam, gdzie rosną niziołki'>wesnoth</a>-1.3.10</code>. A skoro wpis i tak już hermetyczny, to jeszcze podlinkuję [Marka, który ładnie pojechał](http://diveintomark.org/archives/2007/11/11/installing-mysql-on-ubuntu 'Installing MySQL on Ubuntu').)

---

chastell
: oo
: RSpec ma wsparcie dla Heckle
: nie wiem czy kojarzysz Heckle
: tudzież Jestera
: czyli oryginał Heckle, javowy
: więc Heckle
: bierze Twój kod
: bierze testy
: odpala testy na kodzie
: testy przechodzą (oczywiście) wszystkie
: po czym Heckle zmienia losowo jakiegoś `if`a na `unless`a
: generalnie mieszka ścieżkę wykonań skryptu
: i znów odpala testy
: i jak znów przechodzą, to nie za dobrze, bo znaczy, że nie testują tamtego
: fajna sprawa.

opi
: każdy dostatecznie skomplikowany system nie jest w stanie przetestować YJCO[^3].
: jedyna optymalizacja to przepuszczanie tego przez `/dev/null`

chastell
: dlatego wynajmują Ciebie.

opi
: jasne, każdy prostak sobie da z tym radę
: wystarczy co jakiś czas wycinać linijki
: albo pisać coś na pałę
: 60% szans, że poprawiłeś poważnego buga
: 30%, że za chwile wybuchnie serwerownia
: 10%, że nic się nie zmieniło

---

opi
: To takie perpetuum mobile, wczoraj pijesz więc dzisiaj pijesz.

---

opi
: najbardziej obsysa
: debugowanie aplikacji
: w popupie
: która
: wywołuje 700 JS
: która
: wywołuje templaty
: które zapisują plik HTML
: które wywołują `system()`
: które generują PDF `html2pdf`
: wstawiam w kod losowo „TU KURWA!” żeby znaleźć się w tej, nowej dla mnie, sytuacji

---

opi
: Wyskoczę wysłać rachunek, to może świeże powietrze mnie otrzeźwi. Mówiłem Ci, że włosy mi się zapaliły u offtzy?

---

chastell
: „On December 29th 2005, Microsoft applied for a patent that allows the operating system to require users to pay attention to ads shown on their computers. According to the patent, a user will be asked to identify her / himself to a webcam or provide some data regarding the advertisement to be entered. The technology that is part of this patent is meant to give Microsoft the right to repossess one’s computer if one does not pay attention to advertisements.”

opi
: e… uu… aa
: nie wiem, jak to skomentować
: Babilon spłonie?

chastell
: spłonie jak pochodnia.

opi
: czekam, aż będzie „bitch-slapping user” z różnych powodów
: nie patrzysz w reklamy, bach po ryju
: nie kupiłeś MS Antyvirus
: przy boocie bach w ryj
: wpisałeś microsoft.com w `hosts` jako `127.0.0.1` – leje Cię, póki nie zmienisz

---

opi
: „Wiesz, że powinieneś posprzątać, gdy sięgając po kartę PCMCIA umazałeś się majonezem.”

---

Michaś
: o żesz chłopie ale jazda

chastell
: dajesz

Michaś
: musiałem sie bronić, że gołych bab nie ściągam – bronić przed panią dziekan
: no i żeby sie obronić znalazłem z którego MAC było ściągane…
: …i to jest prominentny doktor u nas w zakładzie…

M.
: niezła wtopa

chastell
: no, teraz go będą wytykać palcami
: admin sieci, a gołych bab nie ściąga

opi
: nie, nie
: ściąga, ale jest sprytny
: MAC cloning
: i już prominentny doktor ujebany

---

opi
: Wsadziłem czincz do portu szeregowego i już wiem, skąd wzięło się techno.

---

opi
: możesz mi powiedzieć
: JAK JA KURWA WCISNĄŁEM CTRL+ALT+BACKSPACE?
: tak kodowałem z zapałem
: aż GDM powiedział „cześć, kim jesteś?”

chastell
: może sobie wyłącz.

opi
: aha
: — Jak to się stało, że udało mi się uciąć rękę smarując kanapkę?
: — Możesz kupować smarowane.
: dzięki za pomoc

---

opi
: Czy czytanie basha i jabberowanie nie jest najlepszym objawem frajerstwa? Znaczy w knajpie. Telefonem.

---

opi
: przyznaję, to najgłupszy debugoutput jaki zrobiłem:
: 
    ~~~
    300/05  :-(
    302/05  :-(
    304/05  :-(
    303/05  :-)
    305/05  :-)
    306/05  :-(
    307/05  :-(
    308/05  :-(
    309/05  :-)
    310/05  :-(
    311/05  :-)
    312/05  :-)
    313/05  :-(
    315/05  :-)
    316/05  :-)
    317/05  :-)
    ~~~
    {:.terminal}

[^1]: no, z tydzień?
[^2]: Wy wiecie o kim piszę, Moraczewska
[^3]: taki projekt opiego, niefajny deczko
