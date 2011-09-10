---
date: 2007-06-09 13:48:35 +0200
layout: wycinki
tags: [pl, wycinki]
title: Kocham RSpeca i będę o tym pisał
---

Herma 200%, no ale.

---

opi
: kiedyś robiliśmy zawody: jaki UNIX-owy tool robi najwięcej

chastell
: `rm`?

opi
: wyszło nam, że `cat`

chastell
: [useless use of `cat`](http://partmaps.org/era/unix/award.html 'nagroda taka')

opi
: I fed my `/bin/cat` with `STDOUT` and now it’s `DEAD`!
: (chyba mi wali w czaszkę)
: <blockquote lang='en'><p>I had a cat. She died, she died! Mom told me she was sleeping. She lied, she lied! Why, o’ why my cat is dead? Couldn’t this Chrysler hit me instead?!</p><p>(<cite>The Simpsons</cite>, wiersz Lisy o Snowball II)</cite></p></blockquote>

chastell
: <blockquote><p>— Mojego kota nawet schabem trzeba karmić w ten sposób, że po kawałeczku z miseczki do pyszczka wsadzać.</p><p>— Może nie żyje?</p><p>DeJotPe i Kajko, pl.pregierz</p></blockquote>

opi
: zaczyna mi serio bić
: lubię ten stan

chastell
: 
    ~~~
    Index: spec/truth_table_spec.rb
    ===================================================================
    --- spec/truth_table_spec.rb\t(revision 134)
    +++ spec/truth_table_spec.rb\t(working copy)
    @@ -89,6 +89,11 @@
         dont_table[['0','1','c']].should == ['a']
       end
     
    +  it 'raise the proper exception when asked for ambiguous output' do
    +    multi_table = TruthTable.new [['0','0'],['0','1'],['c','c']], [['a','b']]
    +    lambda{multi_table[['0','-','c']]}.should raise_error(RuntimeError, 'ambiguous query')
    +  end
    +
       it 'be able to have its columns replaced with another table’s contents' do
         replace_table = TruthTable.new([['init0','init1','init2','init4','IOwait','RMACK','WMACK','read0','read1','write0']],
                                        [['a',    'b',    'b',    'c',    'd',     'a',    'a',    'b',    'c',    'c'],
    Index: lib/truth_table.rb
    ===================================================================
    --- lib/truth_table.rb\t(revision 134)
    +++ lib/truth_table.rb\t(working copy)
    @@ -40,6 +40,7 @@
         array.each_with_index do |enc, i|
           block &= blankets[i][enc]
         end
    +    raise 'ambiguous query' if block.size > 1
         row = block.to_a.first
         outputs.map { |col| col[row] }
       end
    ~~~
    {:.terminal}
: nawet coś do doktoratu zrobiłem, ha.

opi
: noc, kanapa, dwa kieliszki wina, świece. „oooh, your diff is SO big!”
: „Nah, it’s just an implant. I do branch mergin’.”

---

…co mi przypomina, że w pracy pół piątku mizialiśmy się [Ohlohem](http://www.ohloh.net/accounts/3764 'ja tam'), sympatyczne to.

opi
: I pity you, foo.
: +1348[^1]
: „Nie mam życia i mogę to udowodnić matematycznie!”

Coś w ten deseń, tak.

[^1]: chwilowy skok w rankingu
