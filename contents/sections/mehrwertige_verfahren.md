Viele digitale Modulationsverfahren verwenden mehr als zwei Symbole. Anstelle von nur zwei Amplituden (klein und groß) funktioniert Amplitudenumtastung auch mit vier oder noch mehr unterschiedlichen Amplituden, also beispielsweise 25%, 50%, 75%, 100% des Maximums. So lassen sich zwei oder mehr Bits zu einem Symbol zusammenfassen und gleichzeitig übertragen.

[picture:701:4ask:Quaternäre Amplitudenumtastung (Quaternary Amplitude-shift Keying)]

Dieses Prinzip lässt sich auch wieder auf die Frequenz- und Phasenumtastung übertragen. Eine einfache Phasenumtastung (Binary Phase-Shift Keying, BPSK) verwendet nur zwei verschiedene Phasenlagen und kann daher nur ein Bit gleichzeitig senden. Die Quadraturphasenumtastung (Quadrature Phase-Shift Keying, QPSK) hingegen nutzt schon vier verschiedene Phasenlagen (0°, 90°, 180° und 270°). QPSK überträgt somit zwei Bits in jedem Schritt.

[question:AE402]

Da bei Verfahren wie QPSK mehr als ein Bit pro Symbol übertragen wird, müssen wir mit den Einheiten aufpassen. Während wir in Hinblick auf den Datenstrom von einer Datenrate in Bit/s sprechen, wird die Rate der Abfolge unterschiedlicher Symbole in Symbolen pro Sekunde mit der Einheit Baud notiert.

[question:AA104]

Werden nur zwei Symbole verwendet und somit jedes Bit einzeln gesendet, entspricht die Symbolrate in Baud der Datenrate in Bit/s. Werden jedoch mehr Symbole verwendet und somit mehrere Bits gleichzeitig übertragen, ist die Datenrate höher als die Symbolrate. Für den Zusammenhang gilt, dass die Datenrate in Bit/s gleich der Symbolrate in Baud multipliziert mit der Anzahl der pro Symbol übertragenen Bits ist:

$C=R_\mathrm{S}\cdot n$

$C$ Datenübertragungsrate in Bit/s

$R_\mathrm{S}$ Symbolrate in Baud

$n$ Symbolgröße in Bit/Symbol

[question:AE405]
[question:AE406]
