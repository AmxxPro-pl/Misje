<div align="center">
<h1><p></p>System Misji<p></p></h1>
<img src="https://github.com/AmxxPro-pl/.github/blob/main/Banner-new.png"></img>
</div>

---

### Description
- !! Plugin został wystawiony ze względu na współpracę Smiguela z AmxxPro.pl (posiadamy zezwolenie na sprzedaż jego pluginów) !!
- Plugin dodaje na serwer misje, które dzielą się na akty, w każdym akcie może być nieokreślona ilość misji.
- Akty trzeba zaliczać po kolei, kolejny akt nie odblokuje się dopóki nie zostanie zaliczony w całości poprzedni akt.
- W aktach znajdują się misje, które także trzeba wykonywać po kolei, aby odblokować kolejne misje z danego aktu.
- Po wybraniu misji musimy ją ukończyć, aby móc rozpocąć kolejną misję.
- Po ukończeniu misji otrzymujemy nagrodę (zależnie od gustu klienta może to być: exp, monety, szlugi jailbreak, exp + monety itd...)
- Akty wczytywane z pliku *.ini (nazwę można dać dowolną, nie musi to być koniecznie nazwa akt)
- Misje wczytywane z pliku *.ini
- Zróżnicowane misje + możliwość przypisania do misji wybranej broni, której trzeba używać, aby wykonać misję np. "Zabij x osób z broni DEAGLE"
- Po ukończeniu misji pokazuje nam się wiadomość w DHUD oraz odgrywa się dźwięk z GTA SA

### Configure
<details>
  <summary><b>misje.ini</b></summary>

```
//=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=//
//=-=-=-=-=                             Misje                           =-=-=-=-=//
//=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=//
//
// Schemat:
// "Akt misji" "Nazwa misji" "Typ misji" "Cel misji" "Nagroda misji" "Bron misji"
//
// Wyjasnieie schematu:
// Akt misji - akt do ktorego misja ma zostac dodana
// Nazwa misji - nazwa misji
// Typ misji - typ misji, typy wybieraj z listy ponizej
// Cel misji - ilosc jaka ma byc celem misji (liczba podstawiana za x w typach misji)
// Nagroda misji - ilosc nagrody za ukonczenie misji
// Bron misji - id broni jaka ma byc uzywana podczas misji, dziala tylko z misjami zabij/zadaj
//
// Typy misji:
// 1 - Rozegraj x rund
// 2 - Zabij x osob
// 3 - Zabij x osob w glowe
// 4 - Zadaj x dmg
// 5 - Zadaj x dmg w glowe
// 6 - Podloz/Rozbroj C4 x razy
// 7 - Podnies x amunicji
// 8 - Przetrwaj x rund bez zgonu
// 9 - Zabij x osob bez zgonu
// 10 - Zabij x osob w glowe bez zgonu
// 11 - Zadaj x dmg bez zgonu
// 12 - Zadaj x dmg w glowe bez zgonu
// 13 - Rozegraj x rund w TT
// 14 - Rozegraj x rund w CT
//
// Bronie:
// 0 - DOWOLNA BRON
// 1 - P228
// 3 - SCOUT
// 4 - HEGRENADE
// 5 - XM1014
// 7 - MAC10
// 8 - AUG
// 10 - ELITE
// 11 - FIVESEVEN
// 12 - UMP45
// 13 - SG550
// 14 - GALIL
// 15 - FAMAS
// 16 - USP
// 17 - GLOCK
// 18 - AWP
// 19 - MP5NAVY
// 20 - M249
// 21 - M3
// 22 - M4A1
// 23 - TMP
// 24 - G3SG1
// 26 - DEAGLE
// 27 - SG552
// 28 - AK47
// 29 - KNIFE
//
//=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=//


"1" "Witamy na serwerze" "1" "5" "5" "0"
"1" "Pierwsza krew" "2" "10" "10" "0"
"1" "Nauka aima" "3" "15" "15" "0"
"1" "Siweca terroru" "4" "10000" "20" "0"
"1" "Cicha paka" "6" "6" "12" "0"
"1" "Zlomiarz" "7" "10000" "20" "0"
"1" "Wiecej krwi" "2" "50" "50" "0"

"2" "Shadow" "6" "12" "24" "0"
"2" "Wiecej zlomu" "7" "25000" "50" "0"
"2" "Deagle Master" "2" "25" "25" "26"
"2" "Survivalowiec" "8" "10" "20" "0"
"2" "Grajek TT" "13" "50" "50" "0"
"2" "Grajek CT" "14" "50" "50" "0"
"2" "Damage Master" "5" "25000" "50" "0"
```
</details>

<details>
  <summary><b>akty.ini</b></summary>

```
//=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=//
//=-=-=-=-=                             Akty                            =-=-=-=-=//
//=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=//
//
// Schemat:
// "Numer aktu (numeruj od 1 w gore)" "Nazwa aktu"
//
//=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=//


"1" "Akt I"
"2" "Akt II"
```
</details>

### ScreenShots

<details>
  <summary><b>Server</b></summary>
  <img src="https://github.com/AmxxPro-pl/Misje/blob/main/img/misje_info.png"></img>
  
  <img src="https://github.com/AmxxPro-pl/Misje/blob/main/img/misje_wykonywane.png"></img>
  
  <img src="https://github.com/AmxxPro-pl/Misje/blob/main/img/misje_menu.png"></img>
  
  <img src="https://github.com/AmxxPro-pl/Misje/blob/main/img/misje_topka.png"></img>
  
  <img src="https://github.com/AmxxPro-pl/Misje/blob/main/img/misje_akty.png"></img>
  
  <img src="https://github.com/AmxxPro-pl/Misje/blob/main/img/misje_akty2.png"></img>
  
  <img src="https://github.com/AmxxPro-pl/Misje/blob/main/img/misja.png"></img>
  
  <img src="https://github.com/AmxxPro-pl/Misje/blob/main/img/misja2.png"></img>
  
  <img src="https://github.com/AmxxPro-pl/Misje/blob/main/img/misja_zrobiona.png"></img>
</details>

### Requirements 
- AMXModX 1.8.3+
