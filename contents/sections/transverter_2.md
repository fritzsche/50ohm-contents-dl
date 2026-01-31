Um bei Transvertern die benötigten Oszillatorfrequenzen zu berechnen, ist die Kenntnis der gewünschten Ein- und Ausgabefrequenzen notwendig. Weiter benötigt man die Information, ob sich der Oszillator unterhalb oder oberhalb des Nutzsignals befinden soll.

<indepth>
Wenn sich die Oszillatorfrequenz unterhalb des Nutzsignals befindet, bleibt die Seitenbandlage eines SSB-Signals (USB/LSB) erhalten.
Befindet sich die Oszillatorfrequenz oberhalb des Nutzsignals, wird die Seitenbandlage eines SSB-Signals invertiert (aus USB wird LSB und umgekehrt).
</indepth>

Rechenbeispiel:

Liegt die Oszillatorfrequenz unterhalb des Nutzsignals, so gehört zur höheren Frequenz des Nutzsignals auch die höhere Frequenz des Ausgangssignals des Konverters/Transverters.

Soll z.B. ein Frequenzbereich von 438 bis 440 MHz auf einen Frequenzbereich von 28-30 MHz umgesetzt werden (bei Annahme, dass sich die Oszillatorfrequenz unterhalb des Nutzsignals befindet), so benötigt man eine Oszillatorfrequenz von 440 MHz - 30 MHz oder 438 MHz - 28 MHz, was in beiden Fällen 410 MHz ergibt. Wird diese Oszillatorfrequenz mittels Frequenzvervielfachung erzeugt, so muss man diese bei der Rückrechnung auf die benötigte Frequenz des Quarzoszillators noch durch Teilen berücksichtigen.

Gleich verhält es sich für den Frequenzbereich von 436 bis 438 MHz, wenn dieser wieder auf einen Frequenzbereich von 28-30 MHz umgesetzt werden soll (ebenfalls bei Annahme, dass sich die Oszillatorfrequenz unterhalb des Nutzsignals befindet).
Hierbei ergibt sich bei der Rechnung 438 MHz - 30 MHz bzw. 436 MHz - 28 MHz eine Oszillatorfrequenz von 408 MHz.

Werden die oben berechneten 408 MHz bzw. 410 MHz durch Verneunfachung der Quarz-Oszillatorfrequenz gewonnen, so ergeben sich die beiden Quarz-Oszillatorfrequenzen zu 408 MHz / 9 = 45,333 MHz und 410 MHz / 9 = 45,556 MHz (jeweils gerundet).

[question:AF501]
[question:AF502]

%TODO: Die Frage 1472 gehört aus unserer Sicht nicht hier her, da es sich um einen Sender handelt und diese Frage nichts mit Konvertern oder Transvertern zu tun hat. Müsste evtl. in das Kapitel Sender und Senderstufen verschoben werden
[question:AF301]