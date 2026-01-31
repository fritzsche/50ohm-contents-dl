Die Genauigkeit von Frequenzen und Messbereichen bei Sendern, Empfängern, Oszillatoren, Frequenzzählern usw. wird entweder in % ($1 \cdot {10^{-2}}$) oder in parts per million (ppm = $1 \cdot {10^{-6}}$) angegeben. Manchmal erfolgt die Angabe auch direkt in Exponentialschreibweise wie z.B. Genauigkeit von $1 \cdot {10^{-7}}$.
Mit dieser Genauigkeit ist die Frequenz zu multiplizieren um die mögliche Abweichung von Messwerten oder Anzeigen zu berechnen.

<indepth>
  Hinweis bzgl. Umrechnung/Darstellung von 10er Potenzen:
  
  $1 \cdot {10^{-2}} = \frac{1}{10^2}$
  $1 \cdot {10^{-6}} = \frac{1}{10^6}$
  
  usw.
</indepth>
  
[question:AA115]

Lösungsweg
* gegeben: $f = 435MHz$
* gesucht: $1ppm$ von $f$

$435MHz \cdot \frac{1}{10^6} = \frac{435\cdot \cancel{10^6}Hz}{\cancel{10^6}} = 435Hz$

[question:AA116]

Lösungsweg
* gegeben: $f = 14,200.000MHz$
* gegeben: $\textrm{Abw.} = 10ppm$
* gesucht: $f_{min}, f_{max}$

$f_{min} = f - f \cdot \frac{10}{10^6} = 14,2MHz - \frac{14,2\cdot \cancel{10^6}Hz\cdot 10}{\cancel{10^6}} = 14,2MHz - 142Hz = 14,199858MHz$
$f_{max} = f + f \cdot \frac{10}{10^6} = 14,2MHz + \frac{14,2\cdot \cancel{10^6}Hz\cdot 10}{\cancel{10^6}} = 14,2MHz + 142Hz = 14,200142MHz$

[question:AI508]

Lösungsweg
* gegeben: $f = 100MHz$
* gegeben: $\textrm{Abw.} = \pm1ppm$
* gesucht: $\Delta f$

$\Delta f = 100MHz \cdot \frac{1}{10^6} = \frac{100\cdot \cancel{10^6}Hz}{\cancel{10^6}} = 100Hz$

[question:AI509]

Lösungsweg
* gegeben: $f = 145MHz$
* gegeben: $\textrm{Abw.} = 10ppm$
* gesucht: $f_{min},f_{max}$

$\Delta f = 145MHz \cdot \frac{10}{10^6} = \frac{145\cdot \cancel{10^6}Hz \cdot 10}{\cancel{10^6}} = 1450Hz$

$f_{min} = f - \Delta f = 145MHz - 1450Hz = 144,99855MHz$
$f_{max} = f - \Delta f = 145MHz + 1450Hz = 145,00145MHz$

[question:AI510]

Lösungsweg
* gegeben: $f = 144,400MHz$
* gegeben: $\textrm{Abw.} = 1ppm$
* gegeben: $f_{B,max} = 2,7kHz$
* gesucht: $f_{B,max,Abw}$

Vorüberlegung:
Bei dieser Frage muss zunächst der Abstand zur Baken-Frequenz aufgrund der SSB-Bandbreite (2,7 kHz) berücksichtigt werden und dieser der maximale Fehler aufgrund der gegebenen Genauigkeit addiert werden, so dass man das Bakensegment sicher nicht stört.

$\Delta f = 144,4MHz \cdot \frac{1}{10^6} = \frac{144,4\cdot \cancel{10^6}Hz}{\cancel{10^6}} = 144,4Hz$

$f_{B,max,Abw} = f_{B,max} + \Delta f = 2,7kHz + 144,4Hz = 2,8444kHz$

%TODO - Evtl. sollte hier eine Grafik zur Veranschaulichung mit eingebunden werden für die Aufgabe 1823

[question:AI506]

Lösungsweg
* gegeben: $f = 29MHz$
* gegeben: $\textrm{Abw.} = 0,01\%$
* gesucht: $\Delta f$

Vorüberlegung:
1% entspricht $1 \cdot {10^{-2}}$
0,01% entspricht $1 \cdot {10^{-4}}$
Um einen gemeinsamen Exponenten, den man im Anschluss kürzen kann, zu erhalten, kann man $1 \cdot {10^{-4}}$ auch zu $100 \cdot {10^{-6}}$ umwandeln (Komma schieben). Hierdurch wird die anschließende Rechnung deutlich vereinfacht.

$\Delta f = 29MHz \cdot 0,01\% = 29\cdot \cancel{10^6}Hz \cdot 100\cdot \cancel{10^{-6}} = 2900Hz$

[question:AI507]

Lösungsweg
* gegeben: $f = 14100kHz$
* gegeben: $\textrm{Abw.} = \pm0,00001\%$
* gesucht: $\Delta f$

Vorüberlegung:
1% entspricht $1 \cdot {10^{-2}}$
0,00001% entspricht $0,1 \cdot {10^{-6}}$

$\Delta f = 14100kHz \cdot 0,00001\% = 14,1\cdot \cancel{10^6}Hz \cdot 0,1\cdot \cancel{10^{-6}} = 1,41Hz$