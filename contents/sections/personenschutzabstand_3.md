% In Bearbeitung! Um was geht es denn hier???
% Das habe ich mir alles aus den Fingern gezogen!

In der Formelsammlung findet man unter Punkt  6.2, Formelzeichen, Konstanten und Tabellen, auch die Formel für $Z_{F0}$ den Feldwellenwiderstand des freien Raumes (Vakuum).
$Z_{F0} = \sqrt{\dfrac{\mu_0}{\varepsilon_0}}$

$\mu_0$ die magnetische Feldkonstante, $\varepsilon_0$ die elektrische Feldkonstante

Die in der Frage angesprochene **magnetischen Feldstärke** wird mit Hilfe magnetische Feldkonstante, der magnetischen Flussdichte und der Magnetisierung berechnet. Deutlich komplexer ist der Zusammenhang der elektrischen Feldkonstante und der **elektrischen Feldstärke**.

In einem Medium (z.B. Luft) ist der Wellenwiderstand  $Z_{F}$ von $\mu$, der magnetische Feldkonstante und $\varepsilon$, der elektrische Feldkonstante des Mediums abhängig.

$Z_{F} = \sqrt{\dfrac{\mu}{\varepsilon}}$

Es gibt eine Abhängigkeit von Feldwellenwiderstand, elektrischer und magnetischer Feldstärke. Damit ist auch die elektrische und magnetische Feldstärke von dem Wellenwiderstand des Mediums abhängig.


[question:AK102]

% Wie errechnen Sie die Leistung am Einspeisepunkt der Antenne (Antenneneingangsleistung) bei bekannter Senderausgangsleistung?

Die Leistung am Speisepunkt der Antenne ergibt sich aus der Senderausgangsleistung und der Dämpfung der Speiseleitung. Jede Dämpfung kann in einen Dämpfungsfaktor übertragen werden. Zum Beispiel, bei 10 dB Dämpfung ist der Faktor 0,1.
Die Berechnung ist einfach: $P_{Ant} = D \cdot P_{Sender}$ (D steht für Dämpfungsfaktor)




[question:AK104]
% In Bearbeitung!
 Im § 8, BEMFV ist u.a. festgelegt, dass der standortbezogene Sicherheitsabstand innerhalb des kontrollierbaren Bereichs liegen muss. Oft ist dieser Abstand durch die örtlichen Gegebenheiten festgelegt und kann nicht verändert werden. In diesen Fällen muss die maximale Sendeleistung angepasst werden.
 
In die Strahlungsleistung geht neben der Sendeleistung der Antennengewinn in dBi ein. Angegeben sind 6 dBd. Bezogen auf den isotropen Strahler sind dies 6 dBd + 2,15 dB. Das ergibt einen Gewinnfaktor von $G_i = 4 \cdot 1,64 = 6,56$.

Jetzt kann die maximale Sendeleistung ermittelt werden. Dazu muss die Formel für die Feldstärke im Fernfeld einer Antenne umgestellt werden:
 $E = \dfrac{\sqrt{30\Omega\cdot P_A\cdot G_i}}{d}$
 $E \cdot d = \sqrt{30\Omega\cdot P_A\cdot G_i}$
 $E^2 \cdot d^2 = 30\Omega\cdot P_A\cdot G_i $
 $\dfrac{E^2 \cdot d^2}{30\Omega\cdot G_i} = P_A$
 $P_A = \dfrac{E^2 \cdot d^2}{30\Omega\cdot G_i}$
 $P_A = \dfrac{28^2 \cdot 5^2}{30 \cdot 6,56}$  
 $P_A =  99,59 \textrm{ W}$
Die Sendeleistung muss auf ca. 100 W beschränkt werden.
  
  Nur zur Sicherheit die Einheitengleichung. Das Ergebnis hat die Einheit Watt.
 $ W = \dfrac{(\frac{V}{m})^2 \cdot \textrm{m}^2}{\frac{V}{A}}$
 $ W = \dfrac{V \cdot V \cdot m \cdot A}{V \cdot m}$
 $ W = V \cdot A$
 $ W = W$
 
 Die Formel für die Feldstärke gilt nur für das Fernfeld. Ob das bei den vorgegeben 5 m erfüllt ist, kann schnell überprüft werden.

$ d > \dfrac{\lambda}{2 \cdot \pi}$
$ d = \dfrac{2,06 \textrm{ m}}{2 \cdot \pi}$
$ d = 0,33 \textrm{ m}$
Der Sicherheitsabstand von d = 5 m ist deutlich im Fernfeld.

[question:AK107]

Bei den drei nächsten Fragen ist die Vorgehensweise mehr oder weniger gleich.
Für die Berechnung der elektrischen Feldstärke wird Leistung am Speisepunkt der Antenne, der Gewinnfaktor und die Entfernung gebraucht.
$ P_A$, Leistung am Speisepunkt: 250 W (kein Kabel, direkte Einspeisung)
$ G_i$, Gewinnfaktor: 12,15 dBi oder 10 dBi und 2,15 dBi, das entspricht den Faktoren $10 \cdot 1,64 = 16,4$ 
$d$, Entfernung: 30 m

Die Formel gilt nur für das Fernfeld. Dies kann mit $ d > \dfrac{\lambda}{2 \cdot \pi}$ überprüft werden.
  $ \textrm{ }$
  $E = \dfrac{\sqrt{30\Omega\cdot P_A\cdot G_i}}{d}$
  $E = \dfrac{\sqrt{30\Omega\cdot 250 \textrm{ W}\cdot 16,4}}{30\textrm{ m}}$
  $E = 11,7 \textrm{ V/m}$

[question:AK113]

$ P_A$, Leistung am Speisepunkt: 10 W (kein Kabel, direkte Einspeisung)
$ G_i$, Gewinnfaktor:  2,15 dBi, das entspricht den Faktor 1,64 (Dipol als Antenne)
$d$, Entfernung: 10 m

Die Formel gilt nur für das Fernfeld. Dies kann mit $ d > \dfrac{\lambda}{2 \cdot \pi}$ überprüft werden.
  $ \textrm{ }$
  $E = \dfrac{\sqrt{30\Omega\cdot P_A\cdot G_i}}{d}$
  $E = \dfrac{\sqrt{30\Omega\cdot 10 \textrm{ W}\cdot 1,64}}{10\textrm{ m}}$
  $ E = 2,2 \textrm{ V/m}$
  
[question:AK114]
% AK115: Eine Amateurfunkstelle sendet in FM mit einer äquivalenten Strahlungsleistung (ERP) von 100 W. Wie groß ist die Feldstärke im freien Raum in einer Entfernung von 100 m?

$ P_A$, Leistung am Speisepunkt: 100 W (Strahlungsleistung in ERP)
$ G_i$, Gewinnfaktor:  2,15 dBi, das entspricht den Faktor 1,64 (Strahlungsleistung in ERP, Faktor für EIRP)
$d$, Entfernung: 100 m

Die Formel gilt nur für das Fernfeld. Dies kann mit $ d > \dfrac{\lambda}{2 \cdot \pi}$ überprüft werden.
  $ \textrm{ }$
  $E = \dfrac{\sqrt{30\Omega\cdot P_A\cdot G_i}}{d}$
  $E = \dfrac{\sqrt{30\Omega\cdot 100 \textrm{ W}\cdot 1,64}}{100\textrm{ m}}$
  $ E = 0,7 \textrm{ V/m}$

[question:AK115]