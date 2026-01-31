* *Verstärkerklasse A*: Kann das gesamte Signal verstärken
* *Verstärkerklasse B*: Das halbe Signal wird gut verstärkt
* *Verstärkerklasse A/B*: Kombination aus A und B mit Verstärkung von etwas mehr als dem halben Signal
* *Verstärkerklasse C*: Weniger als das halbe Signal wird gut verstärkt

<fragment>
Die Verstärkerklassen werden durch die Wahl des Arbeitspunktes bestimmt
</fragment>

<note>
Die Buchstabenbezeichnungen gehen auf eine frühe systematische Klassifizierung von Röhren- und Transistorverstärker zurück
</note>
---
<left>
[picture:377:a_kennlinien_transistor_arbeitspunkt:Kennlinie eines Transistors mit Arbeitspunkten]
</left>
<right>
* Transistorkennlinie zeigt den Zusammenhang zwischen Eingangssignal und Ausgangssignal
* Basis-Emitter- oder Gate-Source-Spannung und Kollektor- oder Drainstrom
* In linearen Bereichen ist die Änderung proportional
* Andere Bereiche sind nichtliniear
</right>
---
### Arbeitspunkt

* Optimaler Betrieb bei optimaler Wahl des Arbeitspunktes auf der Kennlinie
* Arbeitspunkt wird durch die Vorspannung an Basis oder Gate festgelegt
* Verstärkung wirkt dann um den gewünschten Arbeitspunkt herum

---
### Ruhestrom

* Ruhestrom ergibt sich duch die Wahl des Arbeitspunktes
* Fließt auch ohne Eingangssignal
* Beeinflusst die Effizienz eines Verstärkers
* Erhöht thermische Verlustleistung
* Verringert Wirkungsgrad

--- style="font-size: smaller;"
### AP1
<left>
[picture:377:a_kennlinien_transistor_arbeitspunkt:Kennlinie eines Transistors mit Arbeitspunkten]  
</left>
<right>
* C-Betrieb des Verstärkers
* ohne Vorspannung
* Ruhestrom null
* Wirkungsgrad ca. 80-87%
* hoher Oberwellenanteil
</right>
--- style="font-size: smaller;"
### AP2
<left>
[picture:377:a_kennlinien_transistor_arbeitspunkt:Kennlinie eines Transistors mit Arbeitspunkten]  
</left>
<right>
* B-Betrieb des Verstärkers
* Geringe Vorspannung bis zum Einsetzen des Kollektorstroms
* Ruhestrom fast null (gering)
* Wirkungsgrad bis zu 80%
* geringer Oberwellenanteil
</right>
--- style="font-size: smaller;"
### AP3
<left>
[picture:377:a_kennlinien_transistor_arbeitspunkt:Kennlinie eines Transistors mit Arbeitspunkten]  
</left>
<right>
* A/B-Betrieb des Verstärkers
* Höhere Vorspannung als im B-Betrieb, jedoch geringer als im A-Betrieb
* Ruhestrom größer als im B-Betrieb, aber deutlich geringer als im A-Betrieb
* Wirkungsgrad zwischen 50% bis 80%
* geringer Oberwellenanteil
</right>
--- style="font-size: smaller;"
### AP4
<left>
[picture:377:a_kennlinien_transistor_arbeitspunkt:Kennlinie eines Transistors mit Arbeitspunkten]  
</left>
<right>
* A-Betrieb des Verstärkers
* Höhe der Vorspannung so gewählt, dass der Ruhestrom ca. 50% des maximal zulässigen Wertes erreicht
* Wirkungsgrad ca. 40%
* sehr geringer Oberwellenanteil
</right>
---
[question:AD416]
---
[question:AD419]
---
[question:AD420]
---
[question:AD421]
---
### Ausgangsleistung

* Bei Kenntnis des Arbeitspunkt ist der Wirkungsgrad bekannt
* Gleichspannungsleistung ausrechnen
* Ausgangsleistung ist das Produkt aus Gleichspannungsleistung und Wirkungsgrad

---
[question:AD424]
---
#### Lösungsweg
* gegeben: $U=50V$
* gegeben: $I = 2A$
* gegeben: $\eta_A \approx 40\%$
* gesucht: $P_{ab}$

<fragment>
$P_{zu} = U \cdot I = 50V \cdot 2A = 100W$
</fragment>
<fragment>
$\eta_A = \frac{P_{ab}}{P_{zu}} \Rightarrow P_{ab} = \eta_A \cdot P_{zu} = 0,4 \cdot 100W = 40W$
</fragment>
---
[question:AD425]
---
#### Lösungsweg
* gegeben: $U=50V$
* gegeben: $I = 2A$
* gegeben: $\eta_C \approx 85\%$
* gesucht: $P_{ab}$

<fragment>
$P_{zu} = U \cdot I = 50V \cdot 2A = 100W$
</fragment>
<fragment>
$\eta_C = \frac{P_{ab}}{P_{zu}} \Rightarrow P_{ab} = \eta_C \cdot P_{zu} = 0,85 \cdot 100W = 85W$
</fragment>
---
[question:AD418]
---
[question:AD417]
---
### SSB-Betrieb

* Lineare Verstärkung wird benötigt
* Verstärkung im A-, A/B- oder B-Betrieb
* Bei Übersteuerung kommt es zu Verzerrungen des Signals &rarr; Splatter auf benachbarten Frequenzen

---
[question:AD422]
---
[question:AJ218]
---
[question:AD423]
---
### C-Betrieb

* Nichtlinearer Betriebspunkt erzeugt Oberwellen
* Müssen anschließend durch Filterung unterdrückt werden
* Abschirmung durch ein Metallgehäuse

---
[question:AF402]
---
[question:AF403]
