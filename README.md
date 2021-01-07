# Seznamy slov vytvořené z korpusu SYN2020

## Ke stažení

* [Česká podstatná jména, sg., 1. pád (CSV, 118 545 slov, 3.17 MB)](csv/substantives-sg-case-1.csv)

## Sloupce CSV

Každý záznam v odkazovaných CSV souborech má následující strukturu:

```csv
ID;slovo;četnost;<nepoužito>
```

Toto je pro představu prvních 10 záznamů ze seznamu podstatných jmen v singuláru a 1. pádu:

```csv
"1";"člověk";"42459";""
"2";"muž";"27029";""
"3";"žena";"23147";""
"4";"otec";"20101";""
"5";"Praha";"20044";""
"6";"většina";"18320";""
"7";"matka";"17689";""
"8";"pan";"16889";""
"9";"cena";"16535";""
"10";"společnost";"16134";""
```

## Co je v korpusu za slova?

Korpus SYN2020 je synchronní reprezentativní a referenční korpus současné psané češtiny, obsahující 100 milionů textových slov, tedy včetně interpunkce (tokenů).

Ta dlouhá přídavná jména znamenají tohle:

* **Synchronní**: Texty pocházejí z určitého časového období.
* **Reprezentativní**: Jsou zastoupené různé formy psaného slova (hlavní členění: beletrie, oborová literatura a publicistika).
* **Referenční**: Jednou vytvořený a už se neměnící.

## Jak se to generuje?

Vygenerováno aplikací [kontext](https://www.korpus.cz/kontext/query?corpname=syn2020).

Pokud si chcete vygenerovat vlastní seznamy slov dle různých kritérií a neumíte do korpusů přistupovat a dotazovat se, tak se to nejlíp naučíte zde: https://wiki.korpus.cz/doku.php/kurz:uvod

Pokud nevíte, co za formát je to CSV: https://cs.wikipedia.org/wiki/CSV