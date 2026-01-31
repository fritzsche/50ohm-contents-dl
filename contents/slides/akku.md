## Akku-Typen

Die häufigsten Akku-Typen im Amateurfunk:
* Bleiakku (Pb)
* Nickel-Metallhydrid (NiMH)
* Lithium-Eisenphosphat (LiFePO4)

---
[photo:175:a_akku_lifepo4:LiFePO4]

<left>
* Kapazität: 4200 mAh
* Spannung: 4S1P / 13,2 V
</left>
<right>
* Entladung: 30C Constant / 40C Burst
* Balance-Stecker: JST-XH
</right>

---
### Verschaltungen

Beispiele:

* 4S1P: 4 Zellen in Serie, 1 in Parallel
* 4S2P: 4 Zellen in Serie, 2 in Parallel

<fragment>
Pro Zelle ca. 3,2V bis 3,3V, also<br/>$3,3V \cdot 4 = 13,2V$
</fragment>

---
### Kapazität

Beispiel-Akku: 4200 mAh = 4,2 Ah

<fragment>
&rarr; 1 Stunde mit 4,2 A oder 2 Stunden mit 2,1 A belasten
</fragment>
<fragment>
$t = \frac{Q}{I}$
</fragment>
<fragment>
$t = \frac{4,2Ah}{1A} = 1h$
</fragment>
<note>
ggf. Stunden in Sekunden mit 1h=3600s umrechnen
</note>
---
### Elektrische Energie

Gespeicherte elektrische Energie im Akku

$E = Q \cdot U$

<fragment>
Beispiel-Akku: $E = 4,2Ah \cdot 13,2V = 55,44Wh$
</fragment>
---
### Entladestrom

Angabe auf dem Beispiel-Akku: 30C

Die Entladung kann mit 30 mal der Kapazität Q erfolgen

<fragment>
Entladestrom = $30\frac{1}{h} \cdot 4,2Ah = 126A$ 
</fragment>

<fragment>
Der Akku wäre in 128 Sekunden entladen.
</fragment>

<note>
Kabelquerschnitt ist zu beachten
</note>

---
### Reihenschaltung von Akkus

<left>
[photo:176:a_akku_4S1P:Reihenschaltung]
</left>
<right>
* Spannungen addieren sich
* Nur Zellen mit gleichen Daten zusammenschalten
</right>
<note>
Bei ungleichen Daten beeinflussen oder beschädigen sich die Zellen
</note>

---
### Parallelschaltung von Akkus

<left>
[photo:177:a_akku_4S2P:Parallelschaltung]
</left>
<right>
* Spannungen bleiben gleich
* Kapazitäten addieren sich
</right>
<note>
</note>

---
### Balancer

<left>
[photo:178:a_akku_lifepo4_anschluss:LiFePO4 Anschlüsse]
</left>
<right>
* Balanceranschluss kann auf die Spannung jeder Zelle zugreifen
* Balancerschaltung zum Ausgleich der Spannungen
* Schutz der Zellen
* Batteriemonitor
</right>
<note>
</note>

---
[question:AB210]
---
[question:AB209]
---
#### Lösungsweg
* gegeben: $U = 2V$
* gegeben: $Q = 10Ah$
* gegeben: $N = 6$
* gesucht: $U_{ges}, Q_{ges}$

<fragment>
$U_{ges} = N \cdot U = 6 \cdot 2V = 12V$
</fragment>
<fragment>
$Q_{ges} = Q \cdot 1 =10Ah$
</fragment>
---

[question:AB211]
---
#### Lösungsweg
* gegeben: $Q_{max} = 60Ah$
* gegeben: $Q_{10\%} = 0,1 \cdot Q_{max} = 6Ah$
* gegeben: $I = 0,8A$
* gesucht: $t$

<fragment>
$Q = I \cdot t \Rightarrow t = \frac{Q}{I} = \frac{Q_{max} - Q_{10\%}}{I} = \frac{54Ah}{0,8A} = 67,5h$
</fragment>

---
[question:AB501]
---
#### Lösungsweg
* gegeben: $U = 12V$
* gegeben: $Q = 5Ah$
* gesucht: $W$

<fragment>
$W = P \cdot t = U \cdot I \cdot t = U \cdot Q = 12V \cdot 5Ah = 60,0Wh$
</fragment>