<left>
[picture:978:a_swr:Stehende Welle]
</left>
<right>
* Das Stehwellenverhältnis (SWR) kann oft direkt anhand des Speisewiderstands einer Antenne angegeben werden
* Bei einem reinen Wirkwiderstand (ohne induktive oder kapazitive Anteile) berechnet sich das SWR aus dem Verhältnis von Lastwiderstand zu Kabelwellenwiderstand (sodass SWR ≥ 1 ist)
</right>

---

* Beispiel: Eine Antenne mit 100 Ω an einem 50 Ω Kabel führt zu einem SWR von 2, während eine mit 10 Ω zu einem SWR von 5 führt
* Zur Erinnerung: Der Widerstand eines Faltdipols liegt bei knapp 300 Ω

---
[question:AG405]
---
#### Lösungsweg
* gegeben: $Z = 75Ω$
* gegeben: $R_2 \approx 300Ω$ Widerstand Faltdipol
* gesucht: $s$

<fragment>
$s = \frac{R_2}{Z} = \frac{300Ω}{75Ω} = 4$
</fragment>
---

### Einfluss der Leitungsdämpfung auf das Stehwellenverhältnis

* Leitungsdämpfung reduziert sowohl die vorlaufende als auch die rücklaufende Leistung
* Selbst wenn am Kabelende 100% der Energie reflektiert werden, kann am Sender ein niedrigeres (besseres) SWR gemessen werden
* Beispiel: Geht in Hin- und Rückrichtung jeweils die Hälfte der Leistung verloren, so verbleibt nur ein Viertel der ursprünglichen Leistung – dies entspricht einem gemessenen SWR von 3 (25% reflektierte Leistung)

---
[question:AG402]
---
[question:AG403]
---

### Auswirkung von Leitungsdämpfung auf gemessenes SWR

* Bei einer Leitungsdämpfung von 5 dB in Hin- und Rückrichtung (insgesamt 10 dB) entspricht die rücklaufende Leistung nur einem Zehntel der vorlaufenden
* Das gemessene SWR lässt sich mit der Formel berechnen:
  
<fragment>
$s = \frac{\sqrt{P_\mathrm{v}}+\sqrt{P_\mathrm{r}}}{\sqrt{P_\mathrm{v}}-\sqrt{P_\mathrm{r}}}$
</fragment>

---
[question:AG404]
---

#### Lösungsweg
* gegeben: $P_V = 10W$
* gegeben: $a = 5dB$
* gesucht: $s$

<fragment>
Dämpfung auf gesamtes Kabel für Hin- und Rückweg: 10dB
$P_R = 10dB \cdot P_V = \frac{10W}{10} = 1W$
</fragment>
<fragment>
$s = \frac{\sqrt{P_\mathrm{v}}+\sqrt{P_\mathrm{r}}}{\sqrt{P_\mathrm{v}}-\sqrt{P_\mathrm{r}}} = \frac{\sqrt{10W}+\sqrt{1W}}{\sqrt{10W}-\sqrt{1W}} = 1,92$
</fragment>
