## QAM und I/Q-Verfahren

* Digitale Modulationstechnik, die zwei Träger derselben Frequenz verwendet  
* Einer der Träger ist um 90° phasenverschoben  
* Erzeugt ein Signal, das sich in Amplitude und Phase ändert

---

### Erzeugung von QAM

<left>
* Zwei Träger:  
* Einer wird mit dem I-Signal (In-Phase) moduliert  
* Der andere, um 90° verschoben, mit dem Q-Signal (Quadrature)
</left>
<right>
* Beide modulierten Träger werden überlagert  
* Das resultierende Signal ändert sich in Amplitude und Phase  
</right>

---

[include:applet_iq]

---

[question:AE404]

---

[question:AF632]

---

### I/Q-Verfahren – Senderseite

* Der digitale Datenstrom wird in zwei Teile aufgeteilt: I und Q  
* Zwei D/A-Umsetzer wandeln die digitalen I- und Q-Werte in analoge Signale um  
* Diese modulieren die beiden phasenverschobenen Träger, die anschließend kombiniert werden

---

### I/Q-Verfahren – Empfängerseite

* Das empfangene Signal wird mit einem 0°-Träger gemischt, um das I-Signal zu extrahieren  
* Gleichzeitig erfolgt eine Mischung mit einem um 90° phasenverschobenen Träger, um das Q-Signal zu erhalten  
* Beide Signale werden A/D-umgesetzt und bilden so den digitalen I/Q-Datenstrom

---

[question:AF633]

---

### Abbildung des Frequenzbereichs

* Der I/Q-Datenstrom bildet den Frequenzbereich um eine Mittenfrequenz ab  
* Beispiel:  
* 435 MHz-Träger  
* Abtastrate von 10 Mio. Samples/s &rarr; Bandbreite = 10 MHz (±5 MHz um die Mittenfrequenz)  
* Abgedeckter Bereich: ca. 430 bis 440 MHz

---

[question:AF634]

---

### Abhängigkeit der Bandbreite von der Abtastrate

* Die abgedeckte Bandbreite in Hz entspricht der Abtastrate in Samples pro Sekunde

---

[question:AF635]

---

[question:AF636]
