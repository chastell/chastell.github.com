---
date: 2007-05-28 20:50:05 +0200
layout: wycinki
tags: [pl, wycinki]
title: Sic transit gloria Monday
---

(Ja tylko zamykam tryptyk, i może następny wpis znów dla ludzi będzie, kto wie. To poniżej proszę mi przypomnieć jeśli kiedykolwiek będę narzekać na swoją pracę, tak.)

---

opi
: szkoła programistyczna pt. „Nie znam dyrektywy `AS` w SQL-u”
: 
    ~~~
    $deklaracja['dane_mc'][0]['kol_17'] = NULL;
    $deklaracja['dane_mc'][0]['kol_18'] = NULL;
    $deklaracja['dane_mc'][0]['kol_17'] = $deklaracja['dane_mc'][0]['kol_19'];
    $deklaracja['dane_mc'][0]['kol_19'] = NULL;
    $deklaracja['dane_mc'][0]['kol_18'] = $deklaracja['dane_mc'][0]['kol_20'];
    $deklaracja['dane_mc'][0]['kol_20'] = NULL;
    $deklaracja['dane_mc'][0]['kol_19'] = $deklaracja['dane_mc'][0]['kol_28'];
    $deklaracja['dane_mc'][0]['kol_28'] = NULL;
    ~~~
    {:.terminal}
: wszystko jasne? no pewnie
: teraz tylko muszę zrobić, żeby wyświetlało się pole 21
: które nie jest polem 21
: bo.
: i dlatego, że.
: oczywiście nikt nie wie, skąd biorą się te liczby
: oh well

---

chastell
: „Not so straightforward identity following from the C language: `a[i] == *(a + i) == *(i + a) == i[a]`”
: ładne

opi
: ee…
: `a[tablica]` == wskaźnikowi na sumę `a` i `i` równe jest odwrotności sum (co jest jasne) i ostatniego nie kumam, czemu miało by tak być

chastell
: no z pierwszego

opi
: no ale `i` to indeks `a`

chastell
: ale możesz użyć `a` jako indeksu `i`
: i dostaniesz to samo
: to nie ma znaczenia
: to C
: tam się nie patrzy, czy coś ma coś
: tylko na chama jedziesz wskaźnikami do miejsc w pamięci
: więc `a[i]` to tylko adres w pamięci
: ten sam co `i[a]`

opi
: tak, tak. Pamiętam czemu nie lubię C.

---

opi
: właśnie rozgryzam skąd się bierze `mutacje_wydania_deklaracje_id`
: i mam kilka pomysłów: z dupy, z piekła, nazywajmy_jak_najdłużej_pola_nana_land
: „I wish I had a brain!”

chastell
: ♪ I can C clearly now, the brain is gone. ♪

opi
: this is your brain on Ruby: O
: this is your brain on C: o
: this is your brain while browsing […] tree: 8

---

chastell
: „Cztery osoby zostały ranne w rotterdamskim zoo, po tym jak z wybiegu wydostał się goryl. Rozjuszony, ważący niemal 200 kg samiec porwał kobietę i zdemolował restaurację.”
: King Kong

opi
: wiadomo
: tam są narkotyki legalne
: zgnilizna

---

opi
: ten kod nie ma tabów
: ocipieję

chastell
: zaznaczasz w Vimie cały
: i dajesz `=`

opi
: stary!
: Vim nawet go nie koloruje
: nie potrafi
: serio
: łamie mu się
: nigdy czegoś takiego nie widziałem

---

opi
: przyszedł nowy programista na testy
: w CV:
: PHP, VB, C, C++, C#, Delphi
: SQL, OracleForms, MS SQL
: nawet nie usiadł do testów, bo on „ostatnio to pół roku temu robił i nie pamięta”
: piąty facet który nie ukończył zadań „Posortuj tablicę imię varchar, nazwisko varchar. Narysuj drzewo z id fk, name varchar, parent int null.”
: tak sobie myślę, może zatrudnię fretkę?
: potrafi to samo co absolwenci tych uczelni
: a będzie dużo fajniesza

---

opi
: ja pierdolę
: tą samą zmienną przychodzą różne ID.
: 40 minut myślę, czemu mi nie działa
: bo jest tak, `deklaracja_id` i inna `deklaracja_id` która ma `wk_do_deklaracji_id` zawierająca parenta
: chciałem dopisać taki kod, który potrafi „się sam naprawić”
: tylko że `v['deklaracja_id']`
: to raz jest `wk_do_deklaracji`, a raz `deklaracja_id`
: więc jak drugi raz puszczam z tamtym ID to klonuje mi… dane które chcę kasować
: jak myślisz, ile kosztuje wynająć takiego rotterdamskiego goryla?

---

Pokazałem dziś w pracy Moverowi, że jest wreszcie [polski geocoding na Google Maps](http://maps.google.com/maps?saddr=Ch%C5%82odna+25,+Warszawa&daddr=Plac+Inwalid%C3%B3w+10,+Warszawa 'trasa godna polecenia, z Chłodnej do Żywiciela'). Straciłem go na dobre pół godziny.
