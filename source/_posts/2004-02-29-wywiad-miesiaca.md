---
date: 2004-02-29 01:02:24 +0100
layout: wycinki
tags: [pl, wycinki]
title: Wywiad miesiąca
---

Ja przepraszam, że znowu o komputerach będzie, ale portal użytkowników Windows 2003 opublikował [wywiad](http://windows2003.pl/insideMicrosoft_det.aspx?id=23 'liczbę literówek przemilczę') z Security Program Managerem[^1] polskiego oddziału Microsoftu (poniżej lekko przeredagowane fragmenty plus moje przypisy w nawiasach kwadratowych; najlepszy fragment to chyba ten z rekompilowaniem całych Windows po zmianie trzech linijek kodu):

> — Co zrobił ostatnio polski Microsoft, by krajowi użytkownicy poczuli się bezpieczniej? Może jakieś ciekawe plany na przyszłość?
>
> — No tu akurat mamy się czym pochwalić – np. możemy się pochwalić mną. :) A dokładniej, nową pozycją jaką MS stworzył czyli Security Program Manager. […] Żeby daleko nie szukać – to właśnie tu, na `www.windows2003.pl` pojawią się jako pierwsze Webcasty nt. bezpieczeństwa i konkursy z tym związane (już mam przygotowane nagrody ;)).
>
> — Czy duża ilość biuletynów informacyjnych oznacza, że produkty Microsoftu są mało bezpieczne?
>
> — Hmmm – moim zdaniem nasze produkty nie są ani mniej ani bardziej bezpieczne niż inne systemy. Duża ilość biuletynów dowodzi za to, że nie śpimy tylko pracujemy i poprawiamy nasze błędy. […] Zresztą pokażcie mi takiego, kto w ponad 100 000 000 linijek kodu pisanego przez wiele lat przez tysiące ludzi nie popełni błędu. (Tak – tak właśnie wygląda Windows od strony kodowania – wiecie że kompilacja kodu Windows trwa na farmie komputerów ponad 12 godzin? Czyli jak programista zrobi małą poprawkę w trzech linijkach kodu to musi czekać do następnego dnia żeby sprawdzić czy to działa!)
>
> — Jakie są najczęstsze niedopatrzenia użytkowników i administratorów sieci sprawiające, że ich komputery stanowią dobre cele (i źródła) ataków?
>
> — No oczywiście brak zainstalowanych krytycznych i ważnych uaktualnień na systemach – nie tylko Microsoft. Na razie wirusy są pisane przede wszystkim na nasze systemy bo ich jest najwięcej, bo nas się nie lubi, bo tu można odnieść największy „sukces”, bo każdy wirus dotyka 300 mln. użytkowników na świecie. Ale myślę, że tylko kwestią czasu jest ukazanie się wirusów na np. Linuksa, Solarisa czy Apple.
>
> — Proszę powiedzieć, jak to możliwe że najbardziej widoczny produkt Microsoftu – Internet Explorer – jest powszechnie uważany za najmniej bezpieczny komponent systemu? Jak ma się do inicjatywy Trustworthy Computing fakt, że środowisko internetowe wytyka kolejne błędy tej przeglądarki, które nie mogą doczekać się aktualizacji?
>
> — No cóż – IE to jest nasz podstawowy komponent, który styka się z netem – dlatego jak w nim jest dziura to niedobrze. Dlatego właśnie w nim dziury są tak poszukiwane. Dlaczego i czy w nim jest najwięcej dziur – po prostu nie wiem.
>
> — Jak otwartość/niedostępność źródeł oprogramowania wpływa Pana zdaniem na bezpieczeństwo?
>
> — No cóż – tu mam prywatne zdanie – że czym coś jest tajniejsze tym jest bezpieczniejsze – nikt nie może obejrzeć jak nasz soft wygląda od środka i to dodatkowo go chroni [z wyjątkiem m. in. Chińczyków, którzy dostali wgląd w kod Windows 2000, oraz tej części źródeł Windows 2000 i Windows NT która wyciekła dwa tygodnie temu]. Jakoś nie potrafię zrozumieć jak otwartość kodu ma zapewnić jego większe bezpieczeństwo – chyba co najwyżej tak, że więcej osób znajduje w nim dziury i można wypuścić więcej łatek… Ale to chyba nie do końca o to chodzi [jak to nie?!]…
>
> — Jak przekonałby Pan, że serwery oparte o Windows Server mogą być bezpieczniejsze od serwerów linuksowych?
>
> — Przede wszystkim tak, że my mamy specjalne programy na to, aby każdy mógł zadbać o bezpieczeństwo swojego systemu. Linux niestety – jako platforma niekomercyjna – nie ma nikogo kto by się czymś takim zajął [właśnie zniknęły IBM, Novell i Red Hat…]. Linux nie jest „jako taki” w żaden sposób bezpieczniejszy niż Windows – piszą go tacy sami programiści jak nasi. Ale to my mamy mechanizmy i narzędzia do tego aby dotrzeć z odpowiednią informacją, która może pomóc naszym klientom […Bugtraq…]. To my mamy bazy wiedzy suportowej dostępne za darmo dla naszych klientów […chociażby CVE i DSA…]. My mamy dosłownie tony materiałów nt bezpieczeństwa w naszych systemach dostępne od ręki w Internecie […oraz wiele innych stron].
>
> — Ostatnie wydarzenia z robakiem Mydoom pokazały, że największym niebezpieczeństwem w sieci może stać się technologia ataków DDoS. Czy Microsoft planuje jakąś odpowiedź na to zagrożenie?
>
> — A czy jest jakaś odpowiedź na tego typu ataki? Co zrobić jak nagle miliony komputerów odwołują się do tego samego adresu? Blacklisty to za mało w przypadku takiego ataku jaki zaserwował nam Mydoom. Wiemy, że ostatnio z tego powodu SCO miało problemy (ciekawe na czym działają ich systemy Internetowe…). My – ponieważ mieliśmy lepszą infrastrukturę (Windows!) jakoś daliśmy sobie z tym radę [Microsoft rozwiązał problem przekazując go firmie Akamai, która rozdziela ruch przychodzący do serwerów Microsoftu [za pomocą Linuksa](http://news.netcraft.com/archives/2003/08/17/wwwmicrosoftcom_runs_linux_up_to_a_point_.html 'artykuł na Netcraftcie')].
>
> — A jak Microsoft dba o bezpieczeństwo własnych komputerów?
>
> — Oprócz używania antywirusa od czasu do czasu jak włączam rano komputer do sieci to nagle przez kilka minut SMS coś mi tam sprawdza i instaluje i jak coś jest nie tak to każe natychmiast poprawić czy dograć najnowszą wersję czegoś, bo inaczej nawet nie zacznę pracy. U nas admin może bardzo wiele i oczywiście z tego korzysta. Ale ja wiem, że to i tak dla mojego dobra, bo paraliż sieci jest strasznie kłopotliwy także dla mnie.
>
>  

Odlot. Odlot totalny.

[^1]: kim?
