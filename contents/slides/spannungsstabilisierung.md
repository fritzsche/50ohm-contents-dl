* Eingangsspannung kann variieren
* Beispielsweise bei durch Akku betriebenen Geräten
* Empfindliche Baugruppen (z.B. Oszillatoren) würden die Frequenz ändern
* Abhilfe: Spannungsstabilisierung

---
## Stabilisierung mit Z-Diode
<left>
[picture:323:a_Stabilisierung mit Z-Diode:Spannungsstabilisierung mit Z-Diode]
</left>
<right>
* Sehr einfache Schaltung
* Kann die Ausgangsspannung in Grenzen stabil halten
</right>
<note>
</note>
---
[question:AD321]
--- style="font-size: 0.7em;"
#### Lösungsweg
* gegeben: $R_L = 470Ω$
* gegeben: $I_L = 10mA$
* gegeben: $I_Z = 15mA$
* gegeben: $U_{IN} = 13,8V$
* gesucht: $\eta = \frac{P_L}{P_{IN}}$

<fragment>
$P_L = I_L^2 \cdot R_L = (10mA)^2 \cdot 470Ω = 47mW$
</fragment>
<fragment>
$P_{IN} = U_{IN} \cdot I_{IN} = U_{IN} \cdot (I_Z + I_L) = 13,8V \cdot (15mA + 10mA) = 345mW$
</fragment>
<fragment>
$\eta = \frac{P_L}{P_{IN}} = \frac{47mW}{345mW} \approx 0,14$
</fragment>
---
## Linarer Spannungsregler

<left>
[picture:985:a_spannungsregler_linear:Schaltbild eines linearen Spannungsreglers]
</left>
<right>
* Leistungstransistor wird als veränderlicher Widerstand betrieben
* Bildet zusammen mit dem Lastwiderstand einen Spannungsteiler
* Wirkungsgrad ist oft sehr niedrig
</right>

---
[question:AD315]
---
[question:AD319]
---
#### Lösungsweg
* gegeben: $U_{zu} = 13,8V$
* gegeben: $U_{ab} = 9V$
* gegeben: $I = 900mA$
* gesucht: $P_V$

<fragment>
$U_{IC1} = U_{zu} - U_{ab} = 13,8V - 9V = 4,8V$
</fragment>
<fragment>
$P_V = U_{IC1} \cdot I = 4,8V \cdot 900mA = 4,32W$
</fragment>
---
[question:AD320]
---
#### Lösungsweg
* gegeben: $U_{zu} = 13,8V$
* gegeben: $U_{ab} = 5V$
* gegeben: $I_{zu} = 455mA$
* gegeben: $I_{ab} = 450mA$
* gesucht: $\eta$

<fragment>
$\eta = \frac{P_{ab}}{P_{zu}} = \frac{U_{ab} \cdot I_{ab}}{U_{zu} \cdot I_{zu}} = \frac{5V \cdot 450mA}{13,8V \cdot 455mA} \approx 0,36$
</fragment>
---
## Festspannungsregler
<left>
[picture:200:a_Festspannungsregler:Festspannungsregler]
</left>
<right>
* Ausgelegt als IC
* Arbeiten wie linare Spannungsregler mit sehr genauer Spannungsreferenzquelle und optimaler elektronischer Regelung
* Auch bei starker Schwankung auf der Eingangsseite ist die Ausgangsseite sehr stabil
</right>

---
[question:AD317]
---
[question:AD316]
---
[question:AD318]
---
#### Lösungsweg
* gegeben: $U_{zu} = 13,8V$
* gegeben: $U_{ab} = 5V$
* gegeben: $R_L = 10Ω$
* gesucht: $P_V$

<fragment>
$I = \frac{U_{zu}}{R_L} = \frac{5V}{10Ω} = 500mA$
</fragment>
<fragment>
$U_{IC1} = U_{zu} - U_{ab} = 13,8V - 5V = 8,8V$
</fragment>
<fragment>
$P_V = U_{IC1} \cdot I = 8,8V \cdot 500mA = 4,4W$
</fragment>
