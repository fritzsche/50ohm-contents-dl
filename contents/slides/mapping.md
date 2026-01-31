## Mapping in der digitalen Signalverarbeitung

* Wandelt digitale Daten in spezifische Signalpunkte (Symbole) um  
* Entscheidend für Modulationstechniken wie QAM und QPSK  
* Ermöglicht die Übertragung der Daten über das Kommunikationssystem

---

## Schritt 1: Binäre Daten in Symbole umwandeln

* Bei QPSK werden jeweils zwei Bits zu einem Symbol zusammengefasst  
* Es ergeben sich 4 mögliche Kombinationen: 00, 01, 10, 11  
* Jede Kombination wird einem bestimmten Signalpunkt zugeordnet

---

## Schritt 2: Phasenvergabe

* Jedem Symbol wird eine eigene Phase zugewiesen  
* Typische Phasen in 90°-Schritten:
* 00 entspricht 0°
* 01 entspricht 90°
* 10 entspricht 180°
* 11 entspricht 270°

--- style="font-size: smaller;"
## Schritt 3: Mapping auf das Konstellationsdiagramm

<left>
[picture:697:a_8qam:I-Q-Diagramm für ein 8QAM-Mapping]
Die Darstellung ist für ein 8QAM-Mapping. QPSK im Beispiel entspricht dem äußeren Kreis.
</left>
<right>
* Das Konstellations&shy;dia&shy;gramm stellt die Signalpunkte in einem quadratischen Diagramm dar  
* Die X-Achse (*I*n-Phase) und die Y-Achse (*Q*uadratur) zeigen die Amplituden der Signalbestandteile  
* Für QPSK liegen die vier Signalpunkte an den Enden eines Quadrats
</right>

---

## Darstellung der QPSK-Symbole

* 00 bei 0°: Punkt auf der positiven X-Achse  
* 01 bei 90°: Punkt auf der positiven Y-Achse  
* 10 bei 180°: Punkt auf der negativen X-Achse  
* 11 bei 270°: Punkt auf der negativen Y-Achse

* Die klare Trennung der Phasen erleichtert das Auseinanderhalten der Symbole – auch bei Rauschen
