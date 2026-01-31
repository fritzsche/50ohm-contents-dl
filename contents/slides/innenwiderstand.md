### Spannungsquelle
<left>
[photo:182:a_vsource_schematic:Ersatzschaltbild Spannungsquelle]
</left>
<right>
* Reale Spannungsquelle wird mit $R_L$ belastet &rarr; Klemmenspannung $U_k$ sinkt
* Grund ist der Innenwiderstand
* Ohne Belastung / im Leerlauf: $U_q = U_L$
</right>
<note>
</note>

---
### Innenwiderstand

<left>
* Nicht messbar mit einem Multimeter
* Rechnerisch ermitteln: <br/>$R_i$ = $\frac{\Delta U}{\Delta I}$
</left>
<right>
* Leerlauf: $I = 0A$
* Belastung mit $R_L$: <br/>$I_L = \frac{U_L}{R_L}$
</right>

---
### Innenwiderstand Spannungsquelle

$(\Delta U = 0V)$;  $R_i = \frac{\Delta U}{\Delta I} = \frac {0}{xxx} = 0\ \Omega$

<fragment>
Ideale Spannungsquellen sollen einen sehr niedrigen Innenwiderstand $R_i$$\ll$$R_L$ aufweisen, im Idealfall: 0 Ohm, dann bleibt die Ausgangsspannung bei Belastung unverändert.
</fragment>

---

### Strombegrenzung

* In Labornetzteilen eingebaut
* Laststrom übersteigt eine maximale Stromstärke
* &rarr; Klemmenspannung wird abgesenkt
* &rarr; Laststrom bleibt konstant
* Funktion der Konstantstromquelle

---
### Innenwiderstand Stromquelle

$R_i = \frac{\Delta U}{\Delta I}$; $(\Delta I = "\textrm{Null}" A)$;  $R_i = \frac{\Delta U}{"\textrm{Null}"} = "\textrm{unendlich}"\ \Omega$

<fragment>
Ideale Stromquellen sollen einen sehr hohen Innenwiderstand $R_i$$\gg$$R_L$ aufweisen. Idealfall: "unendlich" Ohm, dann bleibt der Laststrom bei Änderung des  Lastwiderstandes konstant, deshalb spricht man auch von Stromanpassung.
</fragment>

---
[question:AB201]
---
### Leistungsanpassung

* Optimale Leistungsabgabe von Sender zu Antenne
* $R_i = R_L$

--- style="font-size: 0.7em;"

|c: Zusammenfassung Innenwiderstand | c: Innenwiderstand |
| Spannungsanpassung bei einer Konstantspannungsquelle| $R_i$ =  "sehr niederhohmig" ; theoretisch  $0\ \Omega$;  $R_i$$\ll$$R_L$ identisch mit $R_L$$\gg$$R_i$| 
|Stromanpassung bei einer Konstantstromquelle|$R_i$ =  "sehr hochohmig" ;  $R_i$$\gg$$R_L$ identisch mit $R_L$$\ll$$R_i$ |
| Leistungsanpassung bei Verstärkern| $R_L$ = $R_i$|
[table:a_Innenwiderstand Zusammenfassung:Zusammenfassung zum Innenwiderstand]

---
[question:AG401]
---
[question:AB202]
---
[question:AB203]
---
[question:AB204]
---
[question:AB207]
---
#### Lösungsweg
* gegeben: $U_0 = 13,5V$
* gegeben: $U_{Kl} = 13V$
* gegeben: $I = 2A$
* gesucht: $R_i$

<fragment>
$R_i = \frac{U_i}{I} = \frac{U_0-U_{Kl}}{I} = \frac{13,5V-13V}{2A} = 0,25Ω$
</fragment>
---
[question:AB208]
---
#### Lösungsweg
* gegeben: $U_0 = 13,8V$
* gegeben: $U_{Kl} = 13,6V$
* gegeben: $I = 20A$
* gesucht: $R_i$

<fragment>
$R_i = \frac{U_i}{I} = \frac{U_0-U_{Kl}}{I} = \frac{13,8V-13,6V}{20A} = 10mΩ$
</fragment>
---
[question:AB206]
---
#### Lösungsweg
* gegeben: $U_0 = 13,5V$
* gegeben: $U_{Kl} = 12,4V$
* gegeben: $I = 0,9A$
* gesucht: $R_i$

<fragment>
$R_i = \frac{U_i}{I} = \frac{U_0-U_{Kl}}{I} = \frac{13,5V-12,4V}{0,9A} = 1,22Ω$
</fragment>
---
[question:AB205]
---
#### Lösungsweg
* gegeben: $U_0 = 5,0V$
* gegeben: $U_{Kl} = 4,8V$
* gegeben: $R_L = 1,2Ω$
* gesucht: $R_i$

<fragment>
$I = \frac{U_{Kl}}{R_L} = \frac{4,8V}{1,2Ω} = 4A$
</fragment>
<fragment>
$R_i = \frac{U_i}{I} = \frac{U_0-U_{Kl}}{I} = \frac{5,0V-4,8V}{4A} = 0,05Ω$
</fragment>

