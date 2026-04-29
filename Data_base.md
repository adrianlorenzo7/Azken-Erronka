---
layout: page
title: Data base
---
Hasteko datu basearen diseinua egin dugu. MongoDb-tik hartutako datuekin, MariaDB-n datu base bat sortu dugu, datuak laburtuz.
![captura1](img/image%20(1).png)
![captura1](img/image.png)

Ondoren, VSCode-n javascript bat sortu dugu.
1. Fasea: Erauzketa eta Transformazioa (MongoDB Aggregations)
Script-ak ez ditu datuak banan-banan kopiatzen; MongoDB-ren ahalmen estatistikoa erabiltzen du informazioa laburtzeko aggregate funtzioaren bidez:

igoerak agregazioa: $group operadorearen bidez, eski-estazio bakoitzeko (resortId) eta igogailu bakoitzeko (liftId) igoera guztiak batzen ditu. Emaitza ez da "nork igo duen", baizik eta "zenbat bider erabili den igogailu hori".

demografia agregazioa: Forfait motaren (forfaitType) arabera banatzen ditu datuak. Horri esker, estazio bakoitzak badaki bere bezeroek denboraldiko txartela, egunekoa edo bestelakoren bat erabili duten.

gailurrak agregazioa: Denbora-analisia egiten du $hour erabiliz. Honek estazioko "ordu gorenak" (peak hours) identifikatzeko balio du, ordu bakoitzeko igoera kopurua kalkulatuz.

2. Fasea: MariaDB-ren Prestaketa (Garbitasuna)
Datu berriak sartu aurretik, script-ak TRUNCATE TABLE aginduak exekutatzen ditu.

Zergatik? Datu zaharkituak ezabatzeko eta informazioa ez bikoizteko.

Garrantzitsuak diren mugak: MariaDB-n Foreign Key-ak aktibatuta badituzu, TRUNCATE aginduak errorea emango du (Error 1701). Horregatik, script-aren bertsio aurreratuetan SET FOREIGN_KEY_CHECKS = 0 erabili behar da garbiketa hau egin ahal izateko.

3. Fasea: Karga (SQL Inserzioak)
Azken urratsa MongoDB-n lortutako array-ak (emaitzak) MariaDB-ra pasatzea da for begizten bidez:

Datu bakoitza bere taula espezifikoan sartzen da: stats_igoerak, stats_demografia edo stats_gailurrak.

Hemen funtsezkoa da Foreign Key egitura: resort_id edo skier_id bezalako eremuek bat etorri behar dute lehenago sortutako taula gurasoekin, bestela MariaDB-k Error 150 emango luke.

![captura1](img/image%20(2).png)
Hauek dira MariaDB-n sortutako query-ak eta haien azalpenak:
![captura1](img/5.png)
![captura1](img/4.png)
![captura1](img/3.png)
![captura1](img/2.png)
![captura1](img/1.png)

Eta hauek dira MongoDB-n sortutako kontsultak eta haien azalpenak:

![captura1](img/16.png)
![captura1](img/15.png)
![captura1](img/14.png)
![captura1](img/13.png)
![captura1](img/12.png)
![captura1](img/11.png)
![captura1](img/10.png)
![captura1](img/9.png)
![captura1](img/8.png)
![captura1](img/7.png)
![captura1](img/6.png)


![captura1](img/image%20(3).png)
![captura1](img/image%20(4).png)



