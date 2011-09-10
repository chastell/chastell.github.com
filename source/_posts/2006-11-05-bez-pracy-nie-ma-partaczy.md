---
date: 2006-11-05 11:52:23 +0100
layout: wycinki
tags: [pl, wycinki]
title: Bez pracy nie ma partaczy
---

&lt;ona&gt;
: „You and Piotr will be connected on LinkedIn.”
: osom, osom

---

chastell
: <blockquote><dl><dt>opi</dt><dd>oi!</dd><dt>chastell</dt><dd>oi!</dd><dt>opi</dt><dd>słuchaj, nie masz pod ręką jakiejś zbędnej płyty w okolicach Athlona?</dd></dl></blockquote>
: och, dzień jak co dzień.

Ania
: ja widzę, że Ty sporo tracisz na tym, że opi na co dzień jest Łodzi, a nie, na przykład, na Ursynowie

chastell
: no próbowaliśmy go zatrudnić
: ale się nie dał

Ania
: biurko w biurko z opim?

chastell
: Ursynów mógłby tego nie przeżyć, ale spróbować byłoby warto

---

opi
: Jestem oazą spokoju. Pierdoloną małą wysepką szczęścia wśród mórz kłopotów.

chastell
: jem kanapkę.
: to jest nas dwóch.

opi
: o, kanapka
: to nie jest zły pomysł
: jeszcze nic nie zrobiłem w tej sprawie

chastell
: w sprawie kanapki?
: ja już wszystko co było można.

opi
: muszę iść 3 m po nóż

chastell
: ja ją zębami, nie nożem.

opi
: pokażesz mi jak smarujesz zębami serek topiony?

chastell
: idę do coffeeheaven, biorę big bosco i mówię, że na ciepło na wynos?

opi
: ja idę do Presto i w ogóle nic nie mówię

---

Tusz
: słowo „świetnie” słownik proponuje zamienić mi na słowo „Wietnam”.

---

opi
: o kurwa
: <blockquote><p>Niby działa, tylko dlaczego jako opi to przychodzi? Nieakceptowalne!!! Ma być e-mail piszącego wstawiany automatycznie z bazy, bo przecież człowiek jest zalogowany do systemu.!!!</p><p></p></blockquote>
: wow
: kropkatrzywykrzykniki
: ktoś tu nie brał dziś tabletek na spokój ducha

chastell
: nie doceniałem Twoich klientów

opi
: najlepsze jest to, że kompletnie bredzi
: od dwóch lat jest tak, jak pisze
: biedakowi się pojebało

---

Ania
: ze względu na niską jakość mojej dzisiejszej pracy, staram się robić jak najmniej, w ten sposób minimalizuję straty firmy.

---

&lt;ona&gt;
: [bosz, przez moment miałam wątpliwości, który jest prezydentem Polski]
: [ale już nie mam]

---

opi
: Przecież wiesz, że jestem wulkanem optymizmu! Głównie – wygasłym.

---

opi
: z serii „Klienci piszą”
: <blockquote><p>Subject: typowanie</p><p>i jak? :-)</p><p></p></blockquote>
: prawie chcę odpisać: „Pada śnieg.”

---

chastell
: [to](http://flickr.com/photos/dooce/286207083/ 'that dog takes the cake')
: i poprzednie.

Ania
: aaa, no tak, Dooce
: Obi-Wan never told you what happened to your puppy.

---

opi
: <blockquote><blockquote><blockquote><p>Poprosiłbym o zawieszenie na pierwszej stronie listu od Prezydenta Kropiwnickiego z widoczną informacją:</p><p></p></blockquote><p>A skąd mam niby ten list wziąć?</p><p></p></blockquote><p>Bardzo dobre pytanie!</p><p></p></blockquote>
: mój INBOX jest jak zoo

---

chastell
: 
    ~~~
    @@ -57,9 +60,11 @@
         return
       else:
         User(self.env, name).insert()
    +    os.system("psql projects -c \"insert into users (id, password) values ('%s', md5('%s'))\"" % (name, pwd))
    
       self.log.debug("User '%s' added.", name)
       req.data['username'] = None # clear the username field
    ~~~
    {:.terminal}
: dawno tak ciężko nie zgrzeszyłem i potrzebowałem spowiedzi
: dziękuję.
: (bo uczeniu się nowych ORM-ów gdy ma się na coś godzinę mówimy gromkie „fuj!”)

str()
: Halo, dlaczego rozmawia się do mnie w tym wulgarnym języku?

chastell
: siła wyższa.
: ale sam chociaż widzisz, że traktuję go tak, jak na to zasłużył.

str()
: Mam z Pythonem na pieńsku za to, że gdy jestem coraz bardziej w prawo w kodzie i nagle się urywa, z przyzwyczajenia szukam zamykającej klamry.

chastell
: albo chociaż jakiegoś <code>end</code>a.
: dla równowagi pieszczę się na boku
: 
    ~~~
    #!/usr/bin/env ruby
    
    require 'postgres'
    
    class String
      def pg_safe
        PGconn.escape self
      end
    end
    
    user = $stdin.gets.chomp.pg_safe
    pass = $stdin.gets.chomp.pg_safe
    
    confstring = IO.readlines("#{File.dirname __FILE__}/conf/drproject.ini").find { |line| line =~ /^database/ }.chomp
    confdata   = confstring.match('^database = postgres://(.*):(.*)@(.*)/(.*)$').to_a
    
    connection = PGconn.new confdata[3], 5432, '', '', confdata[4], confdata[1], confdata[2]
    result     = connection.query "SELECT * FROM users WHERE id = '#{user}' AND password = md5('#{pass}')"
    
    exit 1 if result.empty?
    ~~~
    {:.terminal}
: takie to słodko-gorzkie zabawy, tak.

str()
: Są języki, w których można się zakochać patrząc na samą składnię.

---

> Szanowni Państwo,
>
> czy w zdaniu: „Poczuj jak kremowy żel z olejkiem avocado otula Cię miękką pianą, dając wyjątkowe uczucie niezwykle gładkiej skóry” powinnam postawić przecinek przed słowem jak?
>
> Poradnia Językowa PWN

---

Ania
: Humor sobie poprawię, myślę. Wyluzuję się przy muzyce, myślę. Pierwsza wylosowana piosenka: <cite>Anthem of Our Dying Day</cite>

chastell
: może już nie losuj

Ania
: <cite>Buried Myself Alive</cite>
: Yes! Yes! Yes!

---

Czy już wspominałem, że – tak na oko w przeciwieństwie do wszystkich w okolicy – kocham [swoją pracę](http://civicrm.org/ 'teraz głównie grzebię przy CiviMailu')? No i <del>lans</del> fejm zostanie, [prawda](http://daily.art.pl/?d=2006-10-30 'daily instant classic'). (A jak ktoś twierdzi, że komputery i przypadek to w ogóle nie jest twórcza kombinacja, to się [grubo myli](wycinki/rssymy.png 'kultura, gazeta, pl').)
