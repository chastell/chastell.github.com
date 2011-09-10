---
date: 2004-01-14 19:18:32 +0100
layout: wycinki
tags: [pl, wycinki]
title: The right magic
---

Jak wierni czytelnicy <cite>wycinków</cite> zapewne pamiętają, od pół roku intensywnie i praktycznie do wszystkiego używam oprogramowania open source, co między innymi wiąże się z czytaniem sporej ilości dokumentacji (tu jednak wszystko jest [trochę inne](http://joelonsoftware.com/articles/Biculturalism.html '„Biculturalism” Joela Spolsky’ego, gorąco polecam') i sporo przyzwyczajeń trzeba zmienić). Więc czytam tę dokumentację, czytam, i nie mogę się oprzeć wrażeniu, że ludzie programujący dla siebie/innych i traktujących to jako szeroko rozumiane hobby robią to dużo lepiej i ze znacznie większym entuzjazmem niż ludzie robiący teoretycznie to samo, ale w ramach swojej pracy dla wielkich firm software’owych. Podoba mi się delikatny humor, który prawie zawsze towarzyszy opensource’owym tekstom, podoba mi się ich lekkość, dystans do samych siebie i – ogólnie – sposób w jaki są napisane. Sami zobaczcie:

> Why doesn’t Eterm read my shell profile/rc files (.bashrc, .bash_profile, etc.)?
> ================================================================================
>
> Okay, let me make this very, very clear right off the bat.
>
> Eterm _DOES NOT_ read any shell profile/rc file for any shell. Ever. Never has, never will. Neither does any other terminal program. You are confused.
>
> [Eterm FAQ](http://www.eterm.org/docs/faq/#9 'pytanie nr 9')
{:lang='en'}

> Despite the tons of examples and docs, mod_rewrite is voodoo. Damned cool voodoo, but still voodoo.
>
> [dokumentacja mod_rewrite](http://httpd.apache.org/docs/mod/mod_rewrite.html 'the Swiss Army Knife of URL manipulation')
{:lang='en'}

> Procmail is also a complete drop-in replacement for your MDA. (If this doesn’t mean anything to you, you don’t want to know.)
>
> [Procmail FAQ](http://zer0.org/procmail/mini-faq.html#description 'What is Procmail?')
{:lang='en'}

> indent_string
> =============
>
> Type: string
>
> Default: `"> "`
>
> Specifies the string to prepend to each line of text quoted in a message to which you are replying. You are strongly encouraged not to change this value, as it tends to agitate the more fanatical netizens.
>
> [The Mutt E-Mail Client](http://www.mutt.org/doc/manual/manual-6.html#indent_string 'Reference: Configuration variables')
{:lang='en'}

> This game is widely rumored to be responsible for delaying the Woody release.
>
> `apt-cache show frozen-bubble`
{:lang='en'}

> The `fonts.scale` and `fonts.dir` Files
> =======================================
>
> These files provide the X server with an index of the fonts available in the various fonts files. The <code>fonts.dir</code> file is typically used with non-scaled fonts while <code>fonts.scale</code> is used with (surprise!) scaled fonts. Exactly why they are different files, and exactly why we install both files in directories containing scalable fonts (such as TrueType fonts) remains a bit of a mystery to me. But, we do and it works.
>
> TrueType Fonts on Debian XFree86 4.x Systems
{:lang='en'}

> We trust you have received the usual lecture from the local System Administrator. It usually boils down to these two things:
>
> 1. Respect the privacy of others.
> 2. Think before you type.
>
> pierwsze uruchomienie `sudo`
{:lang='en'}

> The Horde CVS tree is available to be browsed via the web. You can compare arbitrary versions of files with pretty colors, and it’s all kinds of fun.
>
> [About Horde](http://horde.org/about/ 'ich IMP jest podobno całkiem niezły')
{:lang='en'}

> Please remember that inevitably, some people will use this document and screw up their systems. Don’t be one of them.
>
> [Creating custom kernels with Debian’s kernel-package system](http://newbiedoc.sourceforge.net/system/kernel-pkg.html 'amazed at how easy it can be')
{:lang='en'}

Nie mówiąc już o tym, że środowisko opensource’owe wydaje się jakby bardziej twórcze; gdy swego czasu szukałem programiku informującego o nadejściu nowej poczty – bezkonkurencyjnym okazał się [ixbiff](http://ixbiff.sourceforge.net/ ':)'). Teraz pozostaje mi tylko wreszcie dowiedzieć się, co oznacza pewien komunikat, pojawiający się przy każdym starcie systemu…

~~~
cramfs: wrong magic
~~~
{:.terminal}
