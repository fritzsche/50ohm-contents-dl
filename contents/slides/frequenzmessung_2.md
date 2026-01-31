## Frequenzmessung bei Empfängern

* Empfangsfrequenz lässt sich meist nicht direkt messen, da kein Messpunkt vorhanden ist  
* Zum Überprüfen wird ein genauer Oszillator oder Frequenzgenerator an die Antennenbuchse angeschlossen  
* Vergleich der Generatorfrequenz mit der Empfängeranzeige  
* GPS-disziplinierte Oszillatoren/OCXOs bieten höhere Genauigkeit

<note>
Ein direkt angeschlossener Frequenzgenerator kann einen Empfängereingang leicht beschädigen. Im Zweifelsfall sollte die Messung mit der niedrigsten Spannung des Generators und einem Dämpfungsglied begonnen werden.
</note>

---

[question:AI511]

---

[question:AI504]

---

## Frequenzmessung bei Sendern

* Frequenzmessung bei Sendern ist einfacher  
* Frequenzzähler wird über ein Dämpfungsglied an die Antennenbuchse angeschlossen  
* Messung sinnvoll nur bei unmoduliertem Träger

<note>
SSB-Sender erzeugen ohne Modulation kein Signal. Um ihre Sendefrequenz zu messen, kann man ein Audiosignal mit bekannter Frequenz in die Mikrofonbuchse einspeisen. Bei USB wird die Audiofrequenz vom Messwert des Frequenzzählers am Senderausgang abgezogen, bei LSB addiert.
</note>

---

[question:AI502]

---

[question:AI501]

---

* Die Frequenzmessung mittels Oszilloskop ist nur ein Notbehelf, da diese Geräte selten eine so genaue Zeitbasis wie Frequenzzähler haben.

---

[question:AI503]

---

* Einfache Frequenzzähler arbeiten fast immer mit einer sogenannten *Torzeit*  
* Das Gerät schaltet den Eingang für eine bestimmte Zeit ein, zählt die Perioden und berechnet daraus die Frequenz  
* Eine Torzeit von 1 Sekunde liefert direkt die Frequenz in Hertz  
* Kurze Torzeit: schnelle Aktualisierung
* Lange Torzeit: höhere Messgenauigkeit

---

[question:AI505]


