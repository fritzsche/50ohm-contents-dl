% todo Bild von Spannungswandlervarianten
Einen Spannungswandler benötigen wir immer dann, wenn wir eine Spannung umwandeln müssen. In unserem Hobby kann das z.B. eine 5 V Spannung für einen Microcontroller  aus 13,8 V  sein oder aus einer Batterie mit 12 V eine Versorgungsspannung für einen Laptop mit 19 V zu generieren. Hierbei sprechen wir von DC/DC Wandlern als Step-UP (Hochsetzsteller) oder Step-DOWN (Tiefsetzsteller).
Durch die Spannungswandlung entstehen auch Verluste. Das Verhältnis der abgegebenen Leistung zur zugeführten Leistung nennt man Wirkungsgrad. Dieser berechnet sich aus $\eta=\frac{{P}_{AB}}{{P}_{ZU}}$.

Ein Spannungswandler setzt ${U}_{IN}$ = 12 V auf ${U}_{OUT}$ = 5 V um. Er nimmt ${I}_{IN}$ = 2 A auf und gibt ${I}_{OUT}$ = 3 A ab. Wie groß ist sein Wirkungsgrad? Dazu benötigen wir die Leistungen ${P}_{ZU}$ und ${P}_{AB}$. Diese berechnen sich wie bereits gelernt mit ${P} = {U} \cdot {I}$.
In unserem Beispiel also wie folgt:  
${P}_{ZU} = {U}_{IN} \cdot {I}_{IN} = {12} V \cdot {2} A = {24} W $
${P}_{AB} = {U}_{OUT} \cdot {I}_{OUT} = {5} V \cdot {3} A = {15} W $

somit ergibt sich:
$\eta=\frac{{P}_{AB}}{{P}_{ZU}} = \frac{{15}{W}}{{24}{W}} = 0,625$
Um nun $\eta$ in % anzugeben, wird $\eta \cdot 100 \%$ genommen und somit ist der Wirkunggrad $\eta = 62,5 \%$

[question:AB213]
[question:AB214]
<indepth>
[photo:299:StepUpDownWandler: Abwärts- (Buck) Aufwärts- (Boost) Wandler]
Dieser Buck-Boost Converter kann von 0,5 V bis 25 V am Ausgang eingestellt werden. Die maximale Leistung beträgt 25 W. Da der Wirkungsgrad sehr hoch ist, kommen die Schalttransistoren ohne Kühlkörper aus.  Die Betriebsart Abwärtswandler (Step Down = Buck Mode) oder Aufwärtswandler (Step Up = Boost Mode) kann mit dem rechten Minischalter aktiviert werden.
[photo:300:StepUpWandler: Aufwärtsspannungswandler von 7,2 V auf 24 V]
</indepth>
  
<margin>
  Lösungshilfe
  AB 214: 80 %
</margin>