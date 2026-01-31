<left>
[picture:795:a_einweggleichrichtung_c:Einweggleichrichtung mit Kondensator]
</left>
<right>
* Bei positiver Halbwelle lässt Diode $D$ Strom fließen
* Lädt Kondensator $C_L$ auf Spitzenwert der Wechselspannung und versorgt Lastwiderstand $R_L$
* Bei negativer Halbwelle sperrt Diode $D$
* Kondensator $C_L$ entlädt sich über Lastwiderstand $R_L$
</right>
---
<left>
[picture:75:a_Restwelligkeit:Welligkeit der Ausgangsgleichspannnung $U_L$]
Am Lastwiderstand $R_L$ stellt sich eine pulsierende Gleichspannung $U_L$ ein
</left>
<right>
* Je größer die Kapazität, umso geglätteter die Gleichspannung
* Die Trafospannungen sind Effektivspannungen
* Für die Bemessung des Kondensators muss die Spitzenspannung bestimmt werden
* Für die Diode ist die Spitzen-Spitzen-Spannung relevant
</right>

---
[question:AD302]
---
#### Lösungsweg
* gegeben: $U_{eff} = 15V$
* gesucht: $\hat{U}$

<fragment>
$\hat{U} = U_{eff} \cdot \sqrt{2} = 15V \cdot 1,41 = 21,21V$
</fragment>
---
[question:AD303]
---
#### Lösungsweg
* gegeben: $U_P = 230V$
* gegeben: $ü = 20:1$
* gesucht: $\hat{U} + 50\%$

<fragment>
$ü = \frac{U_P}{U_S} \Rightarrow U_S = \frac{U_P}{ü} = \frac{230V}{20} = 11,5V$
</fragment>
<fragment>
$\hat{U} = U_S \cdot \sqrt{2} = 11,5V \cdot 1,41 \approx 16,26V$
</fragment>
<fragment>
$\hat{U} + 50\% \approx 25V$
</fragment>
---
[question:AD304]
---
#### Lösungsweg
* gegeben: $U_P = 230V$
* gegeben: $ü = 5:1$
* gesucht: $U_{SS} + 20\%$

<fragment>
$ü = \frac{U_P}{U_S} \Rightarrow U_S = \frac{U_P}{ü} = \frac{230V}{5} = 46V$
</fragment>
<fragment>
$\hat{U} = U_S \cdot \sqrt{2} = 46V \cdot 1,41 \approx 65,05V$
</fragment>
<fragment>
$U_{SS} + 20\% = 2 \cdot \hat{U} + 20\% \approx 156V$
</fragment>