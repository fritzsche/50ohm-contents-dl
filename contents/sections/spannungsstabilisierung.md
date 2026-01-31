In jedem Funkgerät sind eine oder mehrere Spannungsstabilisierungen vorhanden, da die Eingangsspannung,  vor allem bei mit Akku betriebenen Geräten, schwanken kann und dann empfindliche Baugruppen, wie z.B. Oszillatoren, ihre Frequenz ändern würden.

Spannungsstabilisierungen gibt es in 3 Varianten:
1. Die *Schaltung mit Z-Diode* stellt eine sehr einfache Schaltung zur Stabilisierung der Ausgangsspannung dar, da die Z-Diode die Aussgangsspannung in Grenzen stabil halten kann.

<margin>
Zur Erinnerung:
[picture:862:n_diode_kennlinie_uz:Kennline einer Z-Diode]
Die Z-Diode wird immer mit einem Vorwiderstand und in Sperrrichtung (-$U_Z$) betrieben. Z-Dioden mit Durchbruchspannungen $U_Z$ ab 5 V, zeigen einen sehr steilen Verlauf der Kennlinie und eignen sich deshalb sehr gut zur Spannungsstabilisierung.
(siehe auch Klasse E: Abschnitt Diode 1)
</margin>

[picture:323:a_Stabilisierung mit Z-Diode:Spannungsstabilisierung mit Z-Diode]

---
[question:AD321]

Der Wirkungsgrad der Schaltung ist sehr niedrig, da die Verluste im Vorwiderstand $R_V$ und in der Z-Diode berücksichtigt werden müssen. Die Berechnung ist sehr aufwändig.

<tip>
Lösungsweg:
Spannung am Lastwiderstand: $U_L$ = $I_L$ * $R_L$ = 10 mA * 470 Ohm = 4700 mV = 4,7 V
Leistung im Lastwiderstand: $P_{out}$ = 4,7 V * 10 mA = 47 mW
Verlustleistung in der Z-Diode: $P_{VZ}$ = 4,7 V * 15 mA = 70,5 mW
Eingangsstrom: $I_g $ = 10 mA + 15 mA = 25 mA
Eingangsleistung: $P_{in}$ = 13,8 V * 25 mA = 345 mW
Wirkungsgrad: $\eta = \frac{P_{out}}{P_{in}}$ = $ \frac{47\ mW}{345\ mW}$ = 0,14  
  
</tip>


---
2. *Lineare Spannungsregler* stabilisieren die Ausgangsspannung dadurch, indem ein Leistungstransistor als veränderlicher Widerstand betrieben wird und zusammen mit dem Lastwiderstand einen Spannungsteiler bildet.
[picture:490:a_diskret aufgebaute Spannungsstabilisierung:diskret aufgebaute Spannungsstabilisierung]
In der folgenden Frage ist eine diskrete Spannungsstabilisierung mit Längstransistor dargestellt. Über eine Z-Diode wird eine Referenzspannung von 5,6 V an der Basis des Transistors erzeugt. Das Emitterpotential ist im Betriebszustand eines Siliziumtransistor um etwa 0,6 V niedriger als das Basispotential. Die geregelte Ausgangsspannung liegt dann bei etwa 5 V.
%todo nur Schaltung aus Bild 490 darstellen
Der Laststrom fließt auch durch den Transistor und dadurch wird er bei hohem Laststrom sehr warm. Die sogenannten Längstransistoren befinden sich deshalb bei linear geregelten Spannungsstabilisierungen immer auf einem Kühlkörper. 

<margin>
 [photo:246:a_Längstransistor 2N3055 auf Kühlkörper:Der Längstransistor in einem linear geregelten Netzteil muss große Verlustleistungen aushalten und wird deshalb auf einen Kühlkörper montiert.]
</margin>

<margin>
[photo:307:a_linear geregeltes Netzteil:Innenansicht eines linear geregelten Netzteils für 13,8 V und 25 A; Gewicht 7 kg]
Der schwere Netztrafo bestimmt im Wesentlichen das Gesamtgewicht. 
Unter der Regelung befindet sich ein großer Kühlkörper mit den Längstransistoren, die durch den Lüfter gekühlt werden
</margin>


[question:AD315]
Die Verlustleistung $P_V$ ergibt sich aus der Differenz von  $P_{in}$ - $P_{out}$.

------
[question:AD319]
Die Verlustleistung $P_V$ bestimmt auch den Wirkungsgrad eines Spannungsreglers. Bei linearen Spanungsreglern ist der Wirkungsgrad systembedingt oft sehr niedrig. Mit der folgenden Formel läßt sich der Wirkungsgrad berechnen: 
Wirkungsgrad = abgegebene Leistung auf der Lastseite : gesamte Eingangsleistung
$\eta = \frac{P_{out}}{P_{in}}$

<tip>
Eingangsleistung = Eingangsspannung x Laststrom
$P_{in} = U_{in} \cdot I_{L}$
$P_{in}$ = 13,8 V * 0.9 A = 12,42 W
Ausgangsleistung =  Ausgangsspannung x Laststrom
$P_{out} = U_{out} \cdot I_{L}$
$P_{out}$ = 9 V * 0.9 A =  8,1 W
</tip>
---
[question:AD320]

<tip>
Der Lösungsweg beginnt mit der Berechnung der Einzelleistungen. 
Eingangsleistung = Eingangsspannung x Laststrom
$P_{in} = U_{in} \cdot I_{L}$
$P_{in}$ = 13,8 V * 0.455 A =  6,28 W
Ausgangsleistung =  Ausgangsspannung x Laststrom
$P_{out} = U_{out} \cdot I_{L}$
$P_{out}$ = 5 V * 0.450 A  = 2,25 W
  
$\eta = \frac{P_{out}}{P_{in}} = \frac{2,25W}{6,28W}$ =  0,36
</tip>

3. *Festspannungsregler* in einer integrierten Schaltung
[picture:200:a_Festspannungsregler:Festspannungsregler]

Festspannungsregler arbeiten wie lineare Spannungsregler mit Längstransistor und  beinhalten eine sehr genaue Spannungsreferenzquelle zusammen mit einer optimalen elektronischen Regelung. Auch wenn die Eingangsspannung stark  schwankt (z.B. +-2 V) ist auf der Lastseite die Spannungsänderung nur im Millivoltbereich messbar. Die Kondensatoren auf beiden Seiten des Festspannungsreglers müssen nach Vorgaben des Herstellers gewählt werden, sonst kann es zu unerwünschten Schwingungen im Regelverhalten der Schaltung kommen.

---
[question:AD318]

<tip>
Der Lösungsweg beginnt mit der Berechnung des Laststromes: $I_L$ = $\frac{5V}{10\ Ohm}$ = $0,5A$
Eingangsleistung = Eingangsspannung x Laststrom
Hinweis: Der Strom in der Masseleitung des Festspannungsreglers ist vernachlässigbar klein und wird deshalb nicht berücksichtigt.
$P_{in} = U_{in} \ \cdot I_{L}$ = 13,8 V * 0,5 A = 6,9 W
  
Ausgangsleistung =  Ausgangsspannung x Laststrom
$P_{out} = U_{out} \cdot \ I_{L}$ = 5 V * 0,5 A = 2,5 W
</tip>
Die Verlustleistung $P_V$ des Festspannungsreglers ergibt sich aus der Differenz von  $P_{in}$ und $P_{out}$.

$P_V = P_{in}\  -\  P_{out}$ = 6,9 W - 2,5 W = 4,4 W

<margin>
[photo:245:a_Festspannungsregler:Festspannungsregler für 5 V, 12 V und 9 V auf Kühlkörper]  
</margin>
---
[question:AD317]

<tip>
Damit die interne Regelschaltung optimal funktioniert, muß die Eingangsspannung bei Standard-Festspannungsregler (z.B. Typ 7812) um ca. 3 V größer als die Ausgangsspannung sein. Es gibt Feststspannungsregler, bei denen die Eingangsspannung nur um 1 V größer als die Ausgangsspannung sein muss. Diese Regler heißen Low-Drop-Spannungsregler.
</tip>
  
[question:AD316]

<margin>
Lösungshilfe
AD 315: 5 V
AD 316:  Die Eingangsspannung muss größer als die gewünschte Ausgangsspannung sein.
AD 317:  Die Spannungsschwankung beträgt nahezu null Volt.
AD 318:  4,4 W
AD 319: 12,42 W - 8,1 W = 4,32 W
AD 320: 0,36
AD 321: 0,14
  
</margin>
  
