## Konverter

* Signale auf einem Frequenzband werden in ein anderes Frequenzband umgesetzt
* z.B. wird ein 2m-Signal im Empfang als ein 70cm-Signal ausgesendet
* Signal wird nur in eine Richtung umgewandelt
* Im Grunde ein einfacher Mischer

---
[question:EF504]

<note>
* TCXO und PLL kommen später dran
* Aber die Mischung kann berechnet werden
</note>

---
[question:EF505]
---
## Transverter

* Beim Transverter funktioniert die Umsetzung in beide Richtungen
* Die Umsetzung erfolgt auch hier durch Mischung

---
[question:EF501]
---
[question:EF502]
---
[question:EF503]
<note>
* Lösungsweg auf der kommenden Folie
</note>
---
### Lösungsweg

Frequenz des Generators wird ver-3-facht: $38,666MHz \cdot 3 = 116MHz$

<left>
*TX Weg*
* Die 28-30 MHz vom TRX werden mit 116 MHz gemischt
* Das Signal kann 80-90MHz oder 144-146 MHz sein
</left>
<right>
[picture:843:e_transverter_tx:Transverter im TX-Pfad]
</right>

---

<left>
*RX Weg*
* Das Antennensignal wird mit 116 MHz gemischt und es kommen 28-30 MHz raus
* Das Antennensignal liegt somit u.a. bei 144-146 MHz
* &rarr; Es ist nur die Antwort mit 2 m und der Transverter richtig
</left>
<right>
[picture:842:e_transverter_rx:Transverter im RX-Pfad]
</right>

---
## Frequenzstabilität

* Konverter und Transverter sollten mit frequenzstabilen Oszillatoren gebaut werden
* Weicht die Frequenz ab, ist die Ausgangsfrequenz auch abweichend

---
<left>
* Grafik aus vorheriger Frage
* Aus 10 MHz werden 2,256 GHz, also 225,6 Vervielfachung
* Statt 10 MHz erzeugt der Oszillator aufgrund eines Fehlers 10,01 MHz
* 10,01 MHz &times; 225,6 = 2,258256 GHz
* Mischer: 144 MHz + 2,258256 GHz = 2,402256 GHz &rarr; 2,256 MHz daneben
</left>
<right>
[picture:651:e_konverter_13cm:Konverter für das 13cm-Band]
</right>