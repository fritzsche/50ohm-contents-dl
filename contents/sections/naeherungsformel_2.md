%Um die Feldstärke einer Antenne im Fernfeld ($d>\frac \lambda {2 \pi}$) zu berechnen gibt es die folgende Näherungsformel:

%$E=\frac{\sqrt{30 \Omega \cdot P_\text{A} \cdot G_\text{i}}} {d}=\frac {\sqrt{30 \Omega \cdot P_\text{EIRP}}} d$

%mit der Leistung an der Antenne $P_\text{A}$, dem Gewinnfaktor bezogen auf den Isotropen Strahler %$G_\text{i}$, und dem Abstand $d$

%Für den Gewinnfaktor von Antennen ist gegeben:

%$G_\text{i}=G_\text{d} \cdot 1,64$ 

%bzw.

%$g_\text{i} = g_\text{d}+2,15\text{ dB}$

%Es ist in der Prüfung der Grenzwert für den Personenschutzabstand angegeben. Um den Personenschutzabstand dann zu berechnen, muss daher die Formel umgestellt werden zu

%$d=\frac{\sqrt{30 \Omega \cdot P_\text{A} \cdot G_\text{i}}} {E}$

%Jedoch ist meist nicht die Leistung an der Antenne angegeben, und genauso wenig der Gewinn gegenüber einem Isotropen Strahler. Entsprechend muss dies mit berücksichtigt werden. Dies ergibt dann:

%$d=\dfrac{\sqrt{30 \Omega \cdot P_\text{Transceiver} \cdot G_\text{Kabel} \cdot G_\text{d} \cdot 1,64}} {E}$

%Mit der Leistung am Transceiver $P_\text{Transceiver}$, dem "Gewinn" des Kabels $G_\text{Kabel}$ (hier entsprechend mit negativem Vorzeichen einsetzen) und dem Gewinn gegenüber dem Dipol $G_\text{d}$.

%Der "Gewinn" des Kabels kann z.B. berechnet werden für ein Kabel mit einer Dämpfung von $2 \text{ dB}$:
%$G_\text{Kabel} = 10^{\frac {-2 \text{ dB}} {10 \text{ dB}}} = 10^{-0,2}= 0,631$

% DD4UQ
Bei der Anzeige einer ortsfesten Amateurfunkanlage können die Sicherheitsabstände nach verschiedenen Verfahren ermittelt werden. Eine davon ist die Fernfeldberechnung. 
Für die Berechnung braucht man die Sendeleistung ($P_\text{S}$), den Gewinnfaktor der Antenne bezogen auf den isotropen Strahler ($G_i = 1,64$) und den Grenzwert für die Feldstärke $(E = \text{28 V/m})$ im Fernfeld einer Antenne. Die Wellenlänge (10 m) ist nur angebeben um den Beginn des Fernfeldes zu ermitteln.

$d=\dfrac{\sqrt{30 \Omega \cdot P_\text{A} \cdot G_\text{i}}} {E}$
$d=\dfrac{\sqrt{30 \Omega \cdot 100 \text{W} \cdot1,64}} {28 \text{V/m}}$
$d  \approx 2,50 \text{m}$

Ist der Abstand im Fernfeld (strahlenden Nahfeld)?

 $d = \dfrac{\lambda}{2 \cdot \pi}$
 $d = \dfrac{10 \textrm{ m}}{2 \cdot \pi}$
 $d = 1,59 \textrm{ m}$ 
 
 Der Sicherheitsabstand von 2,50 m liegt deutlich im Fernfeld (strahlenden Nahfeld) und ist damit gültig.

[question:AK106]

Die Frage AK108  ähnelt der vorherigen Frage. Hier muss zusätzlich die Kabeldämpfung beachtet werden. 

Hier bietet sich an, erst die ERIP zu berechnen.

$P_\text{EIRP} = P_S \cdot {10^\dfrac{g_d  −  a  +  2,15 \textrm{ dB}}{10 \textrm{ dB}}}$
Bei einer Richtantenne muss der Wert für $g_d$ angegeben werden. Ein einfacher Dipol hat nur einen Gewinn in Bezug auf einen isotropen Strahler. Hier ist  $g_d = 0 \textrm{ dBd}$ .
$P_\text{EIRP} = 300 \textrm{ W}\cdot {10^\dfrac{0 \textrm{ dBd} −  0,5  \textrm{ dB} +  2,15 \textrm{ dB}}{10 \textrm{ dB}}}$
$P_\text{EIRP} = 300 \textrm{ W}\cdot {10^\dfrac{1,65 \textrm{ dB}}{10 \textrm{ dB}}}$
$P_\text{EIRP} = 300 \textrm{ W}\cdot {10^{0,165}}$
$P_\text{EIRP} = 438,65 \textrm{ W}$

Nun kann der Sicherheitsabstand berechnet werden.

$d=\dfrac{\sqrt{30 \Omega \cdot P_\text{EIRP}}} {E}$
$d=\dfrac{\sqrt{30 \Omega \cdot 438,65 \textrm{ W}}} {28 \text{V/m}}$
$d  \approx 4,10 \text{m}$

Ist der Abstand im Fernfeld (strahlenden Nahfeld) ?

 $d = \dfrac{\lambda}{2 \cdot \pi}$
 $d = \dfrac{20 \textrm{ m}}{2 \cdot \pi}$
 $d = 3,18 \textrm{ m}$ 
 
 Der Sicherheitsabstand von 4,10 m liegt auch hier im Fernfeld (strahlenden Nahfeld)  und ist damit gültig.

[question:AK108]

Hier kann geauso vorgegangen werden, wie bei der vorherigen Frage.
$P_\text{EIRP} = P_S \cdot {10^\dfrac{g_d  −  a  +  2,15 \textrm{ dB}}{10 \textrm{ dB}}}$
$P_\text{EIRP} = 700 \textrm{ W}\cdot {10^\dfrac{0 \textrm{ dBd} −  0,5  \textrm{ dB} +  2,15 \textrm{ dB}}{10 \textrm{ dB}}}$
$P_\text{EIRP} = 700 \textrm{ W}\cdot {10^\dfrac{1,65 \textrm{ dB}}{10 \textrm{ dB}}}$
$P_\text{EIRP} = 700 \textrm{ W}\cdot {10^{0,165}}$
$P_\text{EIRP} = 1023,52 \textrm{ W}$

$\text{ }$

$d=\dfrac{\sqrt{30 \Omega \cdot P_\text{EIRP}}} {E}$
$d=\dfrac{\sqrt{30 \Omega \cdot 1023,52 \textrm{ W}}} {28 \text{V/m}}$
$d  \approx 6,26 \text{m}$

[question:AK109]

Bei der nächsten Frage muss der Sicherheitsabstand für ein Richtantenne berechnet werden . Der Gewinn $g_d = 11.5 \textrm{ dBd}$ .

$P_\text{EIRP} = P_S \cdot {10^\dfrac{g_d  −  a  +  2,15 \textrm{ dB}}{10 \textrm{ dB}}}$
$P_\text{EIRP} = 75 \textrm{ W}\cdot {10^\dfrac{11,5 \textrm{ dBd} −  1,5  \textrm{ dB} +  2,15 \textrm{ dB}}{10 \textrm{ dB}}}$
$P_\text{EIRP} = 75 \textrm{ W}\cdot {10^\dfrac{12,15 \textrm{ dB}}{10 \textrm{ dB}}}$
$P_\text{EIRP} = 75 \textrm{ W}\cdot {10^{1,215}}$
$P_\text{EIRP} = 1230,44 \textrm{ W}$

$\text{ }$

$d=\dfrac{\sqrt{30 \Omega \cdot P_\text{EIRP}}} {E}$
$d=\dfrac{\sqrt{30 \Omega \cdot 1230,44 \textrm{ W}}} {28 \text{V/m}}$
$d  \approx 6,86 \text{m}$

 Ist der Abstand im Fernfeld?

 $d = \dfrac{\lambda}{2 \cdot \pi}$
 $d = \dfrac{2 \textrm{ m}}{2 \cdot \pi}$
 $d = 0,32 \textrm{ m}$ 
 
 Der Sicherheitsabstand von 6,86 m liegt auch hier im Fernfeld und ist damit gültig.

[question:AK110]

Die Vorgehensweise ist analog der, der vorhergehenden Frage.

$P_\text{EIRP} = P_S \cdot {10^\dfrac{g_d  −  a  +  2,15 \textrm{ dB}}{10 \textrm{ dB}}}$
$P_\text{EIRP} = 100 \textrm{ W}\cdot {10^\dfrac{10,5 \textrm{ dBd} −  1,5  \textrm{ dB} +  2,15 \textrm{ dB}}{10 \textrm{ dB}}}$
$P_\text{EIRP} = 100 \textrm{ W}\cdot {10^\dfrac{11,15 \textrm{ dB}}{10 \textrm{ dB}}}$
$P_\text{EIRP} = 100 \textrm{ W}\cdot {10^{1,115}}$
$P_\text{EIRP} = 1303,17 \textrm{ W}$

$\text{ }$

$d=\dfrac{\sqrt{30 \Omega \cdot P_\text{EIRP}}} {E}$
$d=\dfrac{\sqrt{30 \Omega \cdot 1303,17 \textrm{ W}}} {28 \text{V/m}}$
$d  \approx 7,1 \text{m}$

 Der Sicherheitsabstand von 7,1 m liegt auch hier im Fernfeld.

[question:AK111]

Das 13-cm-Band reicht von  2.320 - 2.450 MHz. Für den Frequenzbereich  2.000 – 300.000 MHz ist der Grenzwert für die elektrische Feldstärk 61 V/m.

$P_\text{EIRP} = P_S \cdot {10^\dfrac{g_d  −  a  +  2,15 \textrm{ dB}}{10 \textrm{ dB}}}$
$P_\text{EIRP} = 40 \textrm{ W}\cdot {10^\dfrac{18 \textrm{ dBd} −  2  \textrm{ dB} +  2,15 \textrm{ dB}}{10 \textrm{ dB}}}$
$P_\text{EIRP} = 40 \textrm{ W}\cdot {10^\dfrac{18,15 \textrm{ dB}}{10 \textrm{ dB}}}$
$P_\text{EIRP} = 40 \textrm{ W}\cdot {10^{1,815}}$
$P_\text{EIRP} = 2612,52 \textrm{ W}$

$\text{ }$

$d=\dfrac{\sqrt{30 \Omega \cdot P_\text{EIRP}}} {E}$
$d=\dfrac{\sqrt{30 \Omega \cdot 2612,52 \textrm{ W}}} {61 \text{V/m}}$
$d  \approx 4,6 \text{m}$

Ist der Abstand im Fernfeld?

 $d = \dfrac{\lambda}{2 \cdot \pi}$
 $d = \dfrac{0,13 \textrm{ m}}{2 \cdot \pi}$
 $d = 0,02 \textrm{ m}$ 

 Der Sicherheitsabstand von 4,6 m liegt deutlich im Fernfeld.

[question:AK112]

<indepth>
Warum wird in den Fragen in diesem Abschnitt auf Modulationsverfahren RTTY  und FM hingewiesen?
Bei der Anzeige einer ortsfesten Amateurfunkanlage (nach § 9, BEMFV) ist bei der Konfiguration der Umrechnungsfaktor $\textrm{Faktor}_\textrm{FmodPers}$ einzutragen.
Mit dem Faktor wird die angegebene Spitzenleistung (PEP) in die mittlere Leistung P umgerechnet. Die so korrigierte Leistung kann in die Fernfeldformel zur Berechnung des Sicherheitsabstandes Personenschutz eingesetzt werden. 
$\text{ }$
RTTY und FM haben den Faktor 1, so wie die meisten Modulationsverfahren.
</indepth>