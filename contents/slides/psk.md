* Digitales Modulationsverfahren zur Datenübertragung  
* Veränderung der Phase eines Trägersignals zur Repräsentation von Bitwerten  
* Weniger anfällig für Amplitudenrauschen &rarr; ermöglicht höhere Datenraten

---
## Prinzip der Phasenumtastung

<left>
[picture:705:psk:Phasenumtastung (Phase-shift Keying)]
</left>
<right>
<fragment>
*BPSK (Binary Phase Shift Keying)*
* Zwei Phasenwinkel: 0° und 180°  
* Jeder Winkel repräsentiert einen Bitwert (0 oder 1)
</fragment>
</right>

---
Höhere Varianten:  

* *QPSK (Quadrature PSK)*: Vier Phasen (0°, 90°, 180°, 270°) – 2 Bits pro Symbol  
* *8-PSK*: Acht Phasen – 3 Bits pro Symbol


---

## PSK-Signale in der Zeitdarstellung

* Die Amplitude bleibt konstant; nur die Phase ändert sich  
* *BPSK*: Abrupter Sprung von positiver zu negativer Amplitude bei Bitwechsel  
* *QPSK*: Mehrere Phasenwinkel mit kleineren Übergängen, wodurch die Kurve geglättet erscheint

---

## Erkennung von PSK-Signalen

* *Im Zeitbereich*: Deutliche, abrupte Phasenwechsel  
* *Im Phasendiagramm (Constellation Diagram)*: Punkte auf einem Kreis, die die stabilen Phasenlagen anzeigen
* PSK bietet eine robuste digitale Kommunikation mit hoher Datenrate und guter Rauschfestigkeit

---

[question:AE401]
