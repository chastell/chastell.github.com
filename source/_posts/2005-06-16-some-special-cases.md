---
date: 2005-06-16 18:50:06 +0200
layout: wycinki
tags: [pl, wycinki]
title: 10.3.11. Some Special Cases Where the Collation Determination Is Tricky
---

~~~
mysql> SELECT text FROM testutf
    -> ORDER BY text COLLATE utf8_polish_ci;
+---------+
| text    |
+---------+
| Kaczka  |
| Kazik   |
| Kąkol   |
| Laka    |
| Lżenie  |
| Łazarz  |
| Łąka    |
| Łzawy   |
| Łżenie  |
| Mamona  |
| Mąderek |
| Mąż     |
+---------+
12 rows in set (0.00 sec)

mysql> SELECT LOWER(text) AS lista FROM testutf
    -> ORDER BY lista;
+---------+
| lista   |
+---------+
| kaczka  |
| kąkol   |
| kazik   |
| laka    |
| lżenie  |
| łąka    |
| łazarz  |
| łzawy   |
| łżenie  |
| mąderek |
| mamona  |
| mąż     |
+---------+
12 rows in set (0.00 sec)

mysql> SELECT LOWER(text) AS lista FROM testutf
    -> ORDER BY lista COLLATE utf8_polish_ci;
ERROR 1054 (42S22): Unknown column 'lista' in 'order clause'
~~~
{:.terminal}

Zabierzcie mi MySQL-a bo kogoś zagryzę.
