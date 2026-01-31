Im Rahmen der digitalen Signalverarbeitung beschreibt das *Mapping* den Schritt, bei dem digitale Daten in spezifische Signalpunkte (Symbole) umgewandelt werden, die über das Übertragungssystem gesendet werden können. Dies ist ein entscheidender Prozess in der Modulation, insbesondere bei Quadraturamplitudenmodulationen (QAM) und Phasenumtastungen wie QPSK (Quadrature Phase Shift Keying).

Beispiel für schrittweises Mapping bei QPSK

1. *Binäre Daten in Symbole umwandeln*:

Bei QPSK werden jeweils zwei Bits zu einem Symbol zusammengefasst. Da wir zwei Bits pro Symbol haben, ergeben sich vier mögliche Kombinationen (00, 01, 10, 11). Jede dieser Kombinationen wird einem spezifischen Signalpunkt zugeordnet, der durch eine bestimmte Phase repräsentiert wird.

2. *Phasenvergabe*:

Bei QPSK hat jedes Symbol eine eigene Phase. Die Phasen werden typischerweise in 90°-Schritten definiert:

- 00 entspricht \(0^\circ\)
- 01 entspricht \(90^\circ\)
- 10 entspricht \(180^\circ\)
- 11 entspricht \(270^\circ\)

3. *Mapping auf das Konstellationsdiagramm*:

% TODO Bessere Darstellung für das Beispiel mit QPSK
[picture:697:a_8qam:I-Q-Diagramm für ein 8QAM-Mapping]
Die Darstellung ist für ein 8QAM-Mapping. QPSK im Beispiel entspricht dem äußeren Kreis.

Ein *Konstellationsdiagramm* ist eine grafische Darstellung der möglichen Symbole in einem quadratischen Diagramm, wobei die X-Achse (In-Phase) und die Y-Achse (Quadratur-Phase) die Amplitude der Signalbestandteile darstellen. Bei QPSK befinden sich die vier Signalpunkte an den Enden eines Quadrats im Diagramm:

- Signalpunkt für 00: auf der positiven X-Achse (0°)
- Signalpunkt für 01: auf der positiven Y-Achse (90°)
- Signalpunkt für 10: auf der negativen X-Achse (180°)
- Signalpunkt für 11: auf der negativen Y-Achse (270°)

Jeder dieser Punkte repräsentiert ein Symbol, und der Empfänger kann anhand der Phasenlage bestimmen, welche Bitkombination gesendet wurde.

Beispielhafte Darstellung im Konstellationsdiagramm bei QPSK

Die vier Punkte im Konstellationsdiagramm bei QPSK lassen sich einfach darstellen:

- *00* bei 0°: Repräsentiert einen Punkt auf der positiven X-Achse.
- *01* bei 90°: Ein Punkt auf der positiven Y-Achse.
- *10* bei 180°: Ein Punkt auf der negativen X-Achse.
- *11* bei 270°: Ein Punkt auf der negativen Y-Achse.

%TODO: Bild zum Mapping am Beispiel von QPSK einfügen und die Punkte im Diagramm im Bezug zum Text setzen.

Das Konstellationsdiagramm bei QPSK hat also vier Signalpunkte im rechten Winkel zueinander, was die vier Phasen darstellt, die für die Übertragung verwendet werden. Die klare Trennung der Phasen hilft, die Symbole auch bei Rauschen gut auseinanderzuhalten.