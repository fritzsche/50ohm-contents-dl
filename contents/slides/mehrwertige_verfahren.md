--- style="font-size: 0.7em;"

[picture:701:4ask:Quaternäre Amplitudenumtastung (Quaternary Amplitude-shift Keying)]

* Viele digitale Modulationsverfahren verwenden mehr als zwei Symbole.
* So funktioniert zum Beispiel die 4-Fach-Amplitudenumtastung (4ASK) mit vier unterschiedlichen Amplituden, 25 %, 50 %, 75 %, 100 % des Maximums.
* So lassen sich zwei Bits zu einem Symbol zusammenfassen und gleichzeitig übertragen.

---

* Dieses Prinzip lässt sich auf die Frequenz- und Phasenumtastung übertragen.
* Eine einfache Phasenumtastung (Binary Phase-Shift Keying, BPSK) verwendet nur zwei verschiedene Phasenlagen und kann daher nur ein Bit gleichzeitig senden.
* Die Quadraturphasenumtastung (Quadrature Phase-Shift Keying, QPSK) hingegen nutzt vier verschiedene Phasenlagen (0 °, 90 °, 180 ° und 270 °) und überträgt somit zwei Bits in jedem Schritt.

---
[question:AE402]

---

* Da bei Verfahren wie QPSK mehr als ein Bit pro Symbol übertragen wird, müssen wir mit den Einheiten aufpassen.
* Werden nur zwei Symbole verwendet und somit jedes Bit einzeln gesendet, entspricht die Symbolrate in Baud der Datenrate in Bit/s.
* Werden jedoch mehr Symbole verwendet und somit mehrere Bits gleichzeitig übertragen, ist die Datenrate höher als die Symbolrate.

---

* Die Formel $C = R_{ s } \cdot n$ stellt den Zusammenhang dar:

<fragment>
* C → Datenübertragungsrate in Bit/s
* $R_{ s }$ → Symbolrate in Baud
* n → Symbolgröße in Bit/Symbol
</fragment>

---
[question:AA104]

---

Beispiele:

<fragment>
*RTTY*: Umschaltung zwischen zwei Symbolfrequenzen, sodass pro Symbol ein Bit (0 oder 1) übertragen werden kann.
→ Datenrate = Symbolrate
</fragment>

<fragment>
*FT4*: Umschaltung zwischen vier Symbolfrequenzen, so dass pro Symbol zwei Bit (00, 01, 10 oder 11) übertragen werden können.
→ Datenrate = 2 $\cdot$ Symbolrate
</fragment>

---
[question:AE405]
---
#### Lösungsweg
* gegeben: $R_S = 45,45Bd$
* gegeben: $n=1\frac{Bit}{Symbol}$
* gesucht: $C$

<fragment>
$C = R_S \cdot n = 45,45Bd \cdot 1 = 45,45\frac{Bit}{s}$
</fragment>

---
[question:AE406]
---
#### Lösungsweg
* gegeben: $R_S = 23,4Bd$
* gegeben: $n=2\frac{Bit}{Symbol}$
* gesucht: $C$

<fragment>
$C = R_S \cdot n = 23,4Bd \cdot 2 = 46,8\frac{Bit}{s}$
</fragment>