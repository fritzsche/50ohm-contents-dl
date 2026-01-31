* Umsetzer von einer Frequenz auf eine andere durch Frequenzvervielfacher
* Liegt die Oszillatorfrequenz unterhalb des Nutzsignals, lässt sich die höhere Frequenz des Nutzsignals direkt zur höheren Ausgangsfrequenz des Konverters/Transverters mischen
* Liegt die Oszillatorfrequenz darunter, wird ein SSB-Signal invertiert (USB &rarr; LSB und LSB &rarr; USB)

---
[question:AF501]
---
#### Lösungsweg
* gegeben: $\Delta f_o = 440MHz - 30MHz = 410MHz$
* gegeben: $\Delta f_u = 436MHz - 28MHz = 408MHz$
* gegeben: $n = 9$
* gesucht: $f_{Osc,1}, f_{Osc,2}$

<fragment>
$f_{Osc,1} = \frac{\Delta f_u}{n} = \frac{408MHz}{9} = 45,333MHz$
$f_{Osc,2} = \frac{\Delta f_o}{n} = \frac{410MHz}{9} = 45,556MHz$
</fragment>
---
[question:AF502]
---
#### Lösungsweg
* gegeben: $\Delta f_o = 434MHz - 30MHz = 404MHz$
* gegeben: $\Delta f_u = 430MHz - 28MHz = 402MHz$
* gegeben: $n = 9$
* gesucht: $f_{Osc,1}, f_{Osc,2}$

<fragment>
$f_{Osc,1} = \frac{\Delta f_u}{n} = \frac{402MHz}{9} = 44,6667MHz$
$f_{Osc,2} = \frac{\Delta f_o}{n} = \frac{404MHz}{9} = 44,889MHz$
</fragment>
---
Die folgende Frage wird in ein anderes Kapitel einsortiert, da sie für das Thema Konverter und Transverter nicht passend ist.
---
[question:AF301]
