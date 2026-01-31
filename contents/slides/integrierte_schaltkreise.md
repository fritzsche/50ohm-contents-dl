* *Integrated Circuit (IC)*: Integrierte Schaltungen
* Komplexe Schaltung auf einem Halbleitersubstrat
* Erleichtern den Aufbau von elektronischen Schaltungen

---
[question:AC601]
---
## Monolithic Microwave Integrated Circuit (MMIC)

* Breitbandiger Verstärker mit wenigen Bauteilen
* Typischerweise 50Ω Ein- und Ausgangsimpedanz
* Vereint aktive und passive Bauelemente

---
[question:AC602]
---
[question:AC603]
---
[question:AC604]
---
### MMIC Beschaltung

<left>
[picture:773:a_mmic:MMIC-Schaltung]
</left>
<right>
* Arbeitspunkt wird über $R_{\textrm{BIAS}}$ eingestellt
* Kondensatoren isolieren Gleichspannung
* Anschluss 2 und 4 liegen auf Masse gegenüber $U_{\textrm{CC}}$
* Anschluss 1 ist offen
* $U_{\textrm{CC}}$ fällt über $R_{\textrm{BIAS}}$ und MMIC ab
</right>
<note>
</note>

---
[question:AF425]
---
#### Lösungsweg
* gegeben: $U_{\textrm{D}} = 4V$
* gegeben: $U_{\textrm{CC}} = 13,5V$
* gegeben: $I_{\textrm{D}} = 10mA$
* gesucht: $R_{\textrm{BIAS}}$

<fragment>
$R_{\textrm{BIAS}} = \frac{U_{\textrm{CC}} - U_{\textrm{D}}}{I_{\textrm{D}}} = \frac{13,5V -4V}{10mA} = 950\Omega$
</fragment>

---
[question:AF426]
---
#### Lösungsweg
* gegeben: $U_{\textrm{D}} = 4V$
* gegeben: $U_{\textrm{CC}} = 13,8V$
* gegeben: $I_{\textrm{D}} = 15mA$
* gesucht: $R_{\textrm{BIAS}}$

<fragment>
$R_{\textrm{BIAS}} = \frac{U_{\textrm{CC}} - U_{\textrm{D}}}{I_{\textrm{D}}} = \frac{13,8V -4V}{15mA} = 653,3\Omega \rightarrow 680\Omega$
</fragment>

---
[question:AF427]
---
#### Lösungsweg
* gegeben: $U = 9V$
* gegeben: $R_{\textrm{BIAS}} = 470\Omega$
* gegeben: $U_{\textrm{D}} = 4V$
* gesucht: $P$
* Ansatz: Strom durch $R_{\textrm{BIAS}}$ ist überall gleich, weil kein anderer ohmschmer Verbraucher in der Schaltung vorhanden ist

<fragment>
$I_{\textrm{D}} = \frac{U_{\textrm{BIAS}}}{R_{\textrm{BIAS}}} = \frac{U-U_{\textrm{D}}}{R_{\textrm{BIAS}}} = \frac{9V-4V}{470\Omega} = 10,64mA$
</fragment>
<fragment>
$P = U_{\textrm{D}} \cdot I_{\textrm{D}} = 4V \cdot 10,64mA \approx 43mW$ 
</fragment>
