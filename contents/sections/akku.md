Neben den bekannten Bleiakku (Pb), Nickel-Metallhydrid (NiMH) verwenden auch wir in der Funktechnik z.B. bei Portabelbetrieb immer mehr Lithium-Eisen-Phosphat-Mischungen (LiFePO4). Doch schauen wir uns erstmal ein Akku und dessen Aufschriften in Abbildung [ref:a_akku_lifepo4] an.

% TODO Bild LiFePO4 einfügen
[photo:175:a_akku_lifepo4:LiFePO4]

* Kapazität: 4200 mAh
* Spannung: 4S1P / 13,2 V
* Entladung: 30C Constant / 40C Burst
* Balance Stecker: JST-XH
* Entlastung Stecker: 5.5mm Kugel-Stecker

Die für uns wichtigsten Kenndaten sind die Nennspannung 13,2 V und die Verschaltung 4S1P. Das bedeutet, dass sich die Nennspannung von 13,2 V aus 4 in Serie bzw. Reihe und 1 mal parallel, also alle 4 in Serie geschalten sind. Überlicherweise besitzen LiFePO4 eine Zellnennspannung von 3,2 V bis 3,3 V. Und somit ergibt sich 3,3 V · 4 = 13,2 V · 1 = 13,2 V.

---

<margin>
| l: Zellspannung | l: Bemerkung |
| 3,3 V | Nennspannung |
| 2,5 V | min. Spannung |
| 3,6 V | max. Spannung |
[table:a_akku_lifepo4spannung:LiFePO4 Zellspannung]
</margin>

<attention>
Beachte bei dem Einsatz von einem LiFePO4 als 4S1P verschalten, dass Spannungen zwischen 10 V bis 14,4 V anliegen können. Nicht jedes Funkgerät kann mit diesen Spannungen arbeiten.
</attention>

Bei einem 4S2P sind insgesamt 8 Zellen verbaut. 4 in Serie und das 2 mal parallel. Dies würde dann eine Spannung von 13,2 V aber eine Kapazität von 8400 mAh ergeben.

Bei dem Beispiel-Akku sind 4200 mAh angegeben. Dies entspricht  4,2 Ah. Das würde theoretisch bedeuten, wir können unseren Akku 1 h lang mit 4,2 A oder 2h lang mit 2,1 A usw. belasten. 
$t=\frac{Q}{I}$
$t=\frac{4,2Ah}{1A} =1 h$
Wenn die Kapazität Q in As zu berechnen ist, dann erfolgt die Umrechnung  dadurch, dass die Angabe Stunden (h) durch 3600 s ersetzt wird. Daraus ergibt sich 4,2 A * 3600 s = 15120 As.
Nun wollen wir aber auch wissen, wie viel elektrische Energie in dem Akku gespeichert ist. Energie (Wh) ist die Ladung Q (Ah) des Akkus multipliziert mit der Gesamtspannung U in Volt.

1 Wh = 1 Ah · 1 V

Für unser Beispiel berechnen wir  4,2 Ah · 13,2 V = 55,44 Wh als gespeicherte Energie.
Die Entladung dieses Akkus kann mit einem konstanten Entladestrom von  "30 C" erfolgen. Das bedeutet,  dass der Akku mit 30 · Kapazität Q entladen werden kann.
Endladestrom = 30 · 4200 mA = 126 A
Das ist allerdings nur ein theoretisch möglicher Wert, da unser Akku somit innerhalb von 108 s entladen wäre. Auch der Kabelquerschnitt ist dabei zu berücksichtigen.
Bei Reihen- bzw. Serienschaltung von Akkus, wie in Abbildung [ref:a_akku_4S1P] addieren sich die Spannungen und die Kapazität bleibt gleich. 

% TODO Bild Reihenschaltung liegt bei DG1HXJ als .tex
[photo:176:a_akku_4S1P:Reihenschaltung]

Bei der Paralellschaltung wie in Abblidung [ref:a_akku_4S2P] bleibt die Spannung gleich und die Kapazitäten addieren sich. 

% TODO Bild Paralellschaltung liegt bei DG1HXJ als .tex
[photo:177:a_akku_4S2P:Parallelschaltung]

---

Wichtig ist jedoch, dass wir nur Zellen/ Akkus mit gleichen Daten zusammenschalten, da sich die Zellen gegenseitig beeinflussen und sonst beschädigt werden können.
Insbesondere bei den aktuellen Lithium-Akkumulatoren ist es sinnvoll eine Überwachungseinrichtung (Balancer, Batteriemonitor) zu verbauen. Dieser sorgt u.a. für den notwendigen Ausgleich der Zellspannungen und für eine optimale Ladung. In der Abb. [ref:a_akku_lifepo4_anschluss]

% TODO Bild Infobox Anschluss Akku liegt bei DG1HXJ als .tex
<margin>
[photo:178:a_akku_lifepo4_anschluss:LiFePO4 Anschlüsse]
</margin>
[question:AB210]

Die Akku-Nennkapazität Q wird auch als Ladung bezeichnet und, wie bereits bekannt, in Ah oder mAh angegeben. 

------

[question:AB209]
Die Gesamtspannung ist die Summe der Zellenspannungen. Die Gesamtladung entspricht der Ladung einer Zelle.


[question:AB211]

Zuerst muß die entnehmbare Ladungsmenge von 90 % ermittelt werden.
Die Entladezeit t ergibt sich aus: $t=\frac{Q}{I}$


[question:AB501]
Die im Akku gespeicherte Energie in Wh oder VAh ergibt sich aus der Multiplikation der Akkuspannung U (V) mit der Ladung Q (Ah).
Beispiel:
1 V *  1Ah = 1 Wh
<margin>
  
  Lösungshilfe:
  
  AB 209: 6 * 2 V = 12 V / 10 Ah
  AB 210: Nennkapazität
  AB 211: 90% = 54 Ah; 54 Ah / 0,8 A = 67,5 h oder   67 Stunden und 30 Minuten
  AB 501: 12 V * 5 Ah = 60,0 Wh
  
</margin>