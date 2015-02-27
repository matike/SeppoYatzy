Peli-luokka toimii kaiken keskuksena. Peli-luokassa on metodeja pelin ohjaamista varten, kuten tarkastamaan onko peli viel� kesken vai onko se jo pelattu loppuun. Luokka pit�� my�s kirjaa senhetkisen pelin pisteist� HashMap-rakenteella, johon voidaan lis�t� jokaiselle yhdistelm�lle omat pisteet ja hakea ne sielt� helposti Peli-luokan ja HashMapin omien metodien avulla. Lis�ksi peliss� luodaan Nopat-olio, joka kuvaa peliss� heitett�vi� noppia. Peli perii luokan Yhdistelm�t, jonka metodien avulla voidaan laskea nopista syntyvien yhdistelmien pistem��ri� ja lis�t� ne pistelistalle.

Nopat-luokka luo viisi Noppa-oliota ja lis�� ne ArrayListille. Luokka tarjoaa metodeja noppien k�sittely� varten. Noppia voi heitell� tai hakea sek� asettaa niiden arvon. Noppa-oliossa k�ytet��n Javan tarjoamaa Random-luokkaa satunnaisen kokonaisluvun v�lilt� 1-6 arpomiseen.

Yhdistelm�t-luokkaa k�ytet��n pistem��rien laskemiseen eri yhdistelmill�. Halutun yhdistelm�n pisteet laskevalle metodille annetaan parametrin� Nopat-olio ja metodi palauttaa yhdistelm�n pisteet Nopat-olioon kuuluvista Nopista.