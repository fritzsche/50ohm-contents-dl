Bei Hoch- und Tiefpässen haben bei der Grenzfrequenz der reelle Widerstand und das frequenzabhängige Bauteil den gleichen Widerstandswert. So gilt bei RC-Gliedern: $R=X_C$ und bei RL-Gliedern $R=X_L$. Diese Eigenschaft kann man nutzen, um aus dem Widerstand *R* und angegebener Spule *L* oder Kondensator *C* die Grenzfrequenz zu berechnen. Zur Berechnung der Grenzfrequenz eines RC-Gliedes werden zwei Formeln aus der Formelsammlung benötigt:
Kreisfrequenz: $\omega = 2 \cdot \pi \cdot f$
Kapazitiver Blindwiderstand: $\displaystyle X_C = { 1 \over {\omega \cdot C}}$
Fügen wir diese zusammen, indem wir $\omega$ einsetzen, erhalten wir daraus: $\displaystyle X_C = { 1 \over {2 \cdot \pi \cdot f \cdot C}}$
Diese stellen wir nun nach $f$ um, indem wir beide Seiten durch $X_C$ teilen und mit $f$ multiplizieren: 
$\displaystyle { {X_C \cdot f} \over X_C } = { f \over {2 \cdot \pi \cdot f \cdot C \cdot X_C}}$
$\displaystyle {X_C \over X_C}$ sowie $\displaystyle {f \over f}$ kürzen sich, und wir erhalten somit die fertig umgestellte Formel: 
$\displaystyle f = { 1 \over {2 \cdot \pi \cdot C \cdot X_C}}$
Bei der Grenzfrequenz ist $X_C$ genauso groß wie $R$.
Somit kann man für $X_C$ den gegebenen Widerstandswert $R$ einsetzen und für $C$ den gegebenen Kondensatorwert einsetzen.

Hierdurch ergibt sich folgende Formel für die Berechnung der Grenzfrequenz von RC-Gliedern:

$\displaystyle f = { 1 \over {2 \cdot \pi \cdot R \cdot C}}$

Dabei sollte man natürlich auch die richtigen Zehnerpotenzen (Einheiten) verwenden. Diese sind in der Formelsammlung ganz oben auf der ersten Seite zu finden. 

---
<margin>
*Lösungshinweis*
Hier setzen wir unsere umgestellte Formel ein: 
$\displaystyle f = { 1 \over {2 \cdot \pi \cdot R \cdot C}}$
Mit eingesetzten Werten:
$\displaystyle f = { 1 \over {2 \cdot \pi \cdot 4,7 \cdot 10^{3}Ω \cdot 2,2 \cdot 10^{-9}\text{ F} }}$
$=15395 \text{ Hz}=15,4 \cdot 10^3 \text{ Hz} = 15,4 \text{ kHz}$
</margin>
[question:AD201] 

---
<margin>
*Lösungshinweis*
Hier wieder: $\displaystyle f = { 1 \over {2 \cdot \pi \cdot R \cdot C}}$
Mit eingesetzten Werten:
$\displaystyle f = { 1 \over {2 \cdot \pi \cdot 10 \cdot 10^{3}Ω \cdot 47 \cdot 10^{-9}\text{ F} }}$
$= 339 \text{ Hz}$
</margin>
[question:AD202] 

---
<margin>
*Lösungshinweis*
Auch hier wieder: $\displaystyle f = { 1 \over {2 \cdot \pi \cdot R \cdot C}}$
Aber Vorsicht: Welche Werte müssen hier denn überhaupt berücksichtigt werden?
Schauen wir uns $C_2$ näher an, sehen wir, dass dieser nicht Teil des Tiefpasses ist, sondern nur zur Abblockung von Störungen in der Versorgungsspannung der Schaltung dient. Daher darf $C_2$ hier auch nicht berücksichtigt werden.
Die hohe Grenzfrequenz und sehr hohe Eingangsimpedanz des Audioverstärkers sind zu vernachlässigen und müssen ebenfalls nicht berücksichtigt werden. Als Werte setzen wir daher nur $R_1 = 4,7 kΩ$ und $C_1 = 6,8 \text{nF}$ ein.
Mit eingesetzten Werten:
$\displaystyle f = { 1 \over {2 \cdot \pi \cdot 4,7 \cdot 10^{3}Ω \cdot 6,8 \cdot 10^{-9}\text{ F} }}$
$= 4979\text{ Hz}$
</margin>
[question:AD203] 

**Resonanzfrequenz**
Schaltet man eine Spule und einen Kondensator entweder seriell oder parallel, entsteht ein Schwingkreis. Wir erinnern uns: Bei hohen Frequenzen hat die Spule einen hohen Widerstand. Beim Kondensator verhält es sich sich genau umgekehrt, so dass eine niedrige Frequenz zu einem hohen Kondensatorwiderstand führt. Bei der Frequenz, bei der Spule und Kondensator den gleichen Widerstand haben, handelt es sich um die Resonanzfrequenz - unabhängig davon, ob es sich um einen Serien- oder Parallelschwingkreis handelt. 
[question:AD206] 
Je nachdem, ob die Schaltung nun als Serien- oder Parallelschwingkreis ausgeführt wird, ändert sich aber nun das Filterverhalten bei der Resonanzfrequenz. 
Bei einem **Parallelschwingkreis** lässt sich durch die Eigenresonanz im Schwingkreis nur wenig Energie zuführen - und zwar nur soweit, wie es im Schwingkreis Verluste gibt (z.B. durch den Drahtwiderstand der Spule). Lässt man die Verluste jedoch außer Acht, findet im Schwingkreis eine kontinuierliche Umladung zwischen größtmöglichem elektrischen Feld im Kondensator und dem größtmöglichen magnetischen Feld in der Spule statt. Theoretisch ist im verlustfreien Schwingkreis im Resonanzfall die Impedanz also unendlich groß. 
Abseits dieser Resonanzfrequenz bestimmt das Bauteil mit dem geringeren Widerstand den gesamten Widerstand (Impedanz) des Schwingkreises, da beide Bauteile parallel liegen. So ist bei hohen Frequenzen der Kondensator niederohmiger als die Spule. Bei niedrigen Frequenzen ist die Spule niederohmiger als der Kondensator. Bei Frequenzen über und unter der Resonanzfrequenz hat ein Parallelschwingkreis also einen geringeren Widerstand (Impedanz). 

Bei einem **Serienschwingkreis** handelt es sich um einen geöffneten Schwingkreis, bei dem die Energie zur Umladung zwischen Kondensator und Spule immer durch Ein- und Ausgang hindurchmuss. Bei der Resonanzfrequenz schwingt der Serienschwingkreis also immer "durch" den Frequenzerzeuger und eine evtl. anhängende Last. Der Widerstand (Impedanz) ist bei der Resonanzfrequenz also sehr gering. Theoretisch und ohne Berücksichtigung von Verlusten z.B. durch den Drahtwiderstand der Spule liegt dieser sogar bei 0 Ohm. Das liegt unter anderem auch daran, dass sich durch die Phasenlagen zwischen Spule und Kondensator die Spannungen über die einzelnen Komponenten gegenseitig aufheben. 
Da Spule und Kondensator in Reihe liegen, bestimmt in diesem Fall das Bauteil mit dem höchsten Widerstand den Gesamtwiderstand der Schaltung. Bei hoher Frequenz hat die Spule einen hohen Widerstand. Bei niedriger Frequenz hat der Kondensator einen hohen Widerstand. Bei Frequenzen über und unter der Resonanzfrequenz haben wir beim Serienschwingkreis daher jeweils einen hohen Gesamtwiderstand (Impedanz). 

[question:AD207] 
[question:AD204] 

Bei Parallel- und Serienschwingkreisen gilt im Resonanzfall folgender Zusammenhang:

$X_C$ = $X_L$

Dies bedeutet, dass im Resonanzfall die Widerstände (Impedanzen) beider Bauteile (Spule und Kondensator) genau gleich groß sind. Ohmsche Widerstände und Verluste haben keinen Einfluss auf die Resonanzfrequenz und können daher bei der Berechnung der Resonanzfrequenz von Schwingkreisen vernachlässigt werden.

<tip>
Ohmsche Widerstände in Parallel- und Serienschwingkreisen wirken sich jedoch auf die Güte (Q) und damit auf die Bandbreite (B) des Schwingkreises aus - hierauf werden wir später noch genauer eingehen.
</tip>

Um die Resonanzfrequenz von Parallel- und Serienschwingkreisen zu berechnen, verwenden wir die sog. Thomso´sche Schwingkreisformel (die jeder Funkamateur auswendig kennen muss):

$\displaystyle f = { 1 \over {2 \cdot \pi \cdot \sqrt{L \cdot C}}}$

---
<margin>
*Lösungshinweis*
Hier setzen wir die Thomson´sche Schwingkreisformel ein:
Hinweis: Der Widerstand innerhalb des Schwingkreises hat keine Relevanz für die Berechnung der Resonanzfrequenz!
$\displaystyle f = { 1 \over {2 \cdot \pi \cdot \sqrt{L \cdot C}}}$
Mit eingesetzten Werten:
$\displaystyle f = { 1 \over {2 \cdot \pi \cdot \sqrt{1,2 \cdot 10^{-6}\text{ H} \cdot 6,8 \cdot 10^{-12}\text{ F}}}}$
$= 55715374,27 \text{ Hz}=55,7 \cdot 10^6 \text{ Hz} = 55,7 \text{ MHz}$
</margin>
[question:AD208] 

---

<margin>
*Lösungshinweis*
Hier setzen wir die Thomson´sche Schwingkreisformel ein: 
$\displaystyle f = { 1 \over {2 \cdot \pi \cdot \sqrt{L \cdot C}}}$
Mit eingesetzten Werten:
$\displaystyle f = { 1 \over {2 \cdot \pi \cdot \sqrt{10 \cdot 10^{-6}\text{ H} \cdot 1 \cdot 10^{-9}\text{ F}}}}$
$= 1591549,43 \text{ Hz}=1,592 \cdot 10^6 \text{ Hz} = 1,592 \text{ MHz}$
</margin>
[question:AD209]

---

<margin>
*Lösungshinweis*
Hier setzen wir die Thomson´sche Schwingkreisformel ein: 
$\displaystyle f = { 1 \over {2 \cdot \pi \cdot \sqrt{L \cdot C}}}$
Mit eingesetzten Werten:
$\displaystyle f = { 1 \over {2 \cdot \pi \cdot \sqrt{100 \cdot 10^{-6}\text{ H} \cdot 0,01 \cdot 10^{-6}\text{ F}}}}$
$= 159154,94 \text{ Hz}=159 \cdot 10^3 \text{ Hz} = 159 \text{ kHz}$
</margin>
[question:AD210] 

---

Die Resonanzfrequenz von Parallelschwingkreisen wird genau wie bei Serienschwingkreisen mit der zuvor genannten Thomson´schen Schwingkreisformel berechnet. Auch hier hat ein parallel geschalteter Widerstand keinen Einfluss auf die Resonanzfrequenz, jedoch auf die Güte (Q) und Bandbreite (B).

<margin>
*Lösungshinweis*
Hier setzen wir die Thomson´sche Schwingkreisformel ein:
Hinweis: Der Widerstand innerhalb des Schwingkreises hat keine Relevanz für die Berechnung der Resonanzfrequenz!
$\displaystyle f = { 1 \over {2 \cdot \pi \cdot \sqrt{L \cdot C}}}$
Mit eingesetzten Werten:
$\displaystyle f = { 1 \over {2 \cdot \pi \cdot \sqrt{2,2 \cdot 10^{-6}\text{ H} \cdot 56 \cdot 10^{-12}\text{ F}}}}$
$= 14338865,06 \text{ Hz}=14,34 \cdot 10^6 \text{ Hz} = 14,34 \text{ MHz}$
</margin>
[question:AD211] 

---

<margin>
*Lösungshinweis*
Hier setzen wir die Thomson´sche Schwingkreisformel ein:
Hinweis: Parallel geschaltete Kapazitäten addieren sich.
$\displaystyle f = { 1 \over {2 \cdot \pi \cdot \sqrt{L \cdot C}}}$
Mit eingesetzten Werten:
$C_1 + C_2 + C_3 = C_{Ges} $
$0,1 \cdot 10^{-9}\text{ F} + 1,5 \cdot 10^{-9}\text{ F} + 220 \cdot 10^{-12}\text{ F} = 1,82 \cdot 10^{-9}\text{ F}$
$\displaystyle f = { 1 \over {2 \cdot \pi \cdot \sqrt{1,2 \cdot 10^{-3}\text{ H} \cdot 1,82 \cdot 10^{-9}\text{ F}}}}$
$= 107694,57 \text{ Hz}=107,7 \cdot 10^3 \text{ Hz} = 107,7 \text{ kHz}$
</margin>
[question:AD212] 

---

Um die Resonanzfrequenz von Schwingkreisen zu verändern, kann entweder die Induktivität der Spule oder die Kapazität des Kondensators im Schwingkreis verändert werden.
Wie aus der Thomson´schen Schwingkreisformel ersichtlich befinden sich die Größen $L$ und $C$ jeweils unter dem Bruchstrich. Hierdurch bewirkt eine Vergrößerung von $L$ oder $C$ eine Verringerung der Schwingkreisfrequenz, da der Nenner der Formel größer wird. Die Quadratwurzel hat auf diesen Zusammenhang keinen Einfluss, da die Wurzel aus einer größeren Zahl ebenfalls eine größere Zahl ist. Der Zusammenhang hierbei ist jedoch nicht linear.
Bei einer Verkleinerung von $L$ und $C$ gilt umgekehrt, dass die Resonanzfrequenz des Schwingkreises sich vergrößert.
Die Induktivität einer Spule kann durch Vergrößern der Windungszahl, durch Zusammenschieben oder Einführen eines Ferritkerns vergrößert werden.
Umgekehrt kann die Induktivität einer Spule verringert werden durch Verringerung der Windungszahl, durch Auseinanderziehen oder durch Entfernen eines Ferritkerns oder durch Einführen eines Kupferkerns.
Die Kapazität von Kondensatoren kann durch Austausch oder die Verwendung von Trimm- oder Drehkondensatoren beeinflusst werden.

[question:AD213] 
[question:AD214] 
[question:AD215] 
[question:AD216] 
[question:AD217] 

Oft ist es in Schaltungen erforderlich, die Resonanzfrequenz eines Schwingkreises durch eine Steuerspannung zu beeinflussen (z.B. bei einem VCO - Voltage Controlled Oscillator). Hierfür kann man z.B. eine Kapazitätsdiode verwenden, die in Sperrrichtung betrieben wird. Je höher die Gegenspannung der Diode wird, desto geringer wird deren Kapazität, welche durch die Größe der Grenzschicht (P-N-Übergang) bestimmt wird. Die Grenzschicht vergrößert sich bei Vergrößerung der angelegten Sperrspannung, wodurch sich die Kapazität verringert und damit die Frequenz des Schwingkreises gemäß Thomson´scher Schwingkreisformel steigt.
Umgekehrt verkleinert sich die Grenzschicht der Kapazitätsdiode bei Verringerung der angelegten Sperrspannung, wodurch sich die Kapazität erhöht und damit die Frequenz des Schwingkreises kleiner wird.
Die Sperrspannung kann z.B. durch ein Potentiometer oder einen Steuerkreis erzeugt werden.

%TODO: Evtl. Grafik zu Sperrschicht und Verhalten in Kapazitätsdiode.

[question:AD218] 

Eine Kombination aus Parallel- und Serienschwingkreisen kann bei geeigneter Anordnung als Bandpassfilter verwendet werden. Im Resonanzfall verhalten sich die parallelen Schwingkreise wie hochohmige Widerstände und der Serienschwingkreis wie ein niederohmiger Widerstand.

[question:AD205]

Die Bandbreiten von Filtern und Bandpässen werden in dB bezogen auf einen Referenzwert des Filters angegeben. Hierbei kann die Bandbreite bei einer vorgegebenen Dämpfung oder in Bezug auf die minimale Dämpfung der Durchlasskurve des Filters gemessen werden.
Üblicherweise wird die *Bandbreite* eines Filters als der sog. *-3dB-Wert* angegeben, bei dem nur noch die halbe Leistung eines Signals das Filter passieren kann; dies entspricht dem *0,7-fachen der Signalspannung*.
Die Bandbreite wird als die *Differenz zwischen dem oberen und unteren -3dB-Wert* gemessen.
So wird z.B. die -3dB-Dämpfung bezogen auf die minimale Dämpfung der Filterkurve verwendet, um die Eignung eines Filters für bestimmte Betriebsarten (SSB, CW, RTTY) anzugeben.
Ein schmalbandiges Filter (500 Hz/-3dB-Bandbreite) wird beispielsweise für Telegrafie (CW) verwendet.
Ein breitbandiges Filter mit (2,7kHz/-3dB-Bandbreite) wird beispielsweise für Sprachmodulation (SSB) verwendet.
Für Filter mit hoher Güte werden hierfür in der Regel Quarzfilter eingesetzt.

[question:AD219]
[question:AD221] 
[question:AD222]
[question:AD220]

Die Güte eines Schwingkreises (Q-Faktor) wird durch das Verhältnis der Blindwiderstände von Kapazität und Induktivität im Resonanzfall zum ohmschen Verlustwiderstand bestimmt. Wenn ein Schwingkreis keinerlei ohmschen Verlustwiderstände enthalten würde, so wäre dessen Q-Faktor unendlich. Reale Bauteile sind jedoch immer verlustbehaftet. Induktivitäten haben immer einen ohmschen Verlustwiderstand, Kapazitäten haben dielektrische Verluste, die sich ebenfalls als ohmscher Widerstand auswirken.
Je größer die ohmschen Widerstände in einem Schwingkreis sind, desto geringer wird dessen Q-Faktor.

Für die Berechnung des Q-Faktors verwenden wir die entsprechenden Formeln aus der Formelsammlung je nachdem ob es sich um einen Parallel- oder Serienschwingkreis handelt:

Für den Serienschwingkreis gilt im Resonanzfall ($X_L = X_C$):
$\displaystyle Q = { f_0 \over B} = { X_L \over R_S}$

Für den Parallelschwingkreis gilt im Resonanzfall ($X_L = X_C$):
$\displaystyle Q = { f_0 \over B} = { R_P \over X_L}$

---
<margin>
*Lösungsweg*
Zunächst müssen wir aus den Werten von *L* und *C* die Resonanzfrequenz des Schwingkreises gemäß Thomson´scher Schwingkreisformel bestimmen, da die vorgenannten Gleichungen nur für den Resonanzfall gelten!

$\displaystyle f = { 1 \over {2 \cdot \pi \cdot \sqrt{L \cdot C}}}$
Mit eingesetzten Werten:
$\displaystyle f = { 1 \over {2 \cdot \pi \cdot \sqrt{100 \cdot 10^{-6}\text{ H} \cdot 0,01 \cdot 10^{-6}\text{ F}}}}$
$= 159154,94 \text{ Hz}=159,2 \cdot 10^3 \text{ Hz} = 159,2 \text{ kHz}$
  
Damit kann der induktive Widerstand $X_L$ wie folgt berechnet werden (Formeln aus der Formelsammlung):

Kreisfrequenz: $\omega = 2 \cdot \pi \cdot f$
Induktiver Widerstand: $X_L = \omega \cdot L$

Mit eingesetzten Werten:
$X_L = 2 \cdot \pi \cdot 159,2 \cdot 10^3 \text{ Hz} \cdot 100 \cdot 10^{-6}\text{ H}$ = 100,03 Ohm
  
Die Güte errechnet sich damit unter Einbeziehung des ohmschen Widerstands $R_S$ zu:
  
$Q = { X_L \over R_S}$
  
Mit eingesetzten Werten:
$Q = { 100,03 \over 10} = 10 $
</margin>
[question:AD225]

---

Entsprechend dem obigen Rechenbeispiel können wir jetzt auch den Gütefaktor des Parallelschwingkreises errechnen. Die Resonanzfrequenz wird wie im vorigen Beispiel berechnet. Es ist jedoch zu beachten, dass für die Berechnung von Q die Formel für den Parallelschwingkreis zu verwenden ist:

$\displaystyle Q = { f_0 \over B} = { R_P \over X_L}$

[question:AD226]

Die Bandbreite von Parallel- und Serienschwingkreisen lässt sich nun ebenfalls einfach aus der Resonanzfrequenz des Schwingkreises und dessen Gütefaktor wie folgt berechnen (Formel hierzu in der Formelsammlung):

$\displaystyle Q = { f_0 \over B}$

Durch Umstellen der Formel ergibt sich die Bandbreite B:

$\displaystyle B = { f_0 \over Q}$

Die vorgenannte Formel gilt sowohl für den Serien- als auch den Parallelschwingkreis!

---

<margin>
Lösungshinweis:
Gemäß Thomson´scher Schwingkreisformel ergibt sich für einen Parallelschwingkreis mit 2,2 µH und 56 pF eine Resonanzfrequenz von 14,339 MHz. Für $X_L$ errechnet sich daraus ein Wert in Höhe von 198,21 Ohm. Der Gütefaktor Q kann errechnet werden zu 5,05. Nun können wir die Bandbreite B nach der vorgenannten Formel berechnen und erhalten 2,84 MHz.
</margin>
[question:AD224]

---

Entsprechend kann nun auch mit dem zuvor beschriebenen Wissen die folgende Frage schrittweise berechnet werden.
[question:AD223]

Zur Übertragung von Signalen zwischen Schaltungsstufen sowie in Filtern in Sendern und Empfängern werden häufig gekoppelte Schwingkreise verwendet. Hierbei werden zwei Schwingkreise induktiv oder kapazitiv aneinander gekoppelt. Diese Kopplung kann je nach Anwendung *lose*, *unterkritisch*, *kritisch* oder *überkritisch* erfolgen. Der Grad der Kopplung bestimmt die gegenseitige Beeinflussung und damit die Bandbreite und Durchlasskurve der gesamten Anordnung.
Bei loser und unterkritischer Kopplung gibt es kaum eine gegenseitige Beeinflussung; Dafür ist die Durchlassdämpfung der Anordnung relativ hoch und die Bandbreite relativ gering.
Bei kritischer Kopplung beeinflussen sich beide Schwingkreise gerade so, dass eine im Durchlassbereich flache Durchlasskurve mit geringer Dämpfung entsteht und diese im gewünschten Durchlassbereich völlig eben ist (Plateau). Die Bandbreite der Anordnung ist hierbei größer als bei loser und unterkritischer Kopplung. Hieran ist eine kritische Kopplung auch gut zu erkennen.
Bei überkritischer Kopplung ist die gegenseitige Beeinflussung der beiden Schwingkreise sehr stark, was zu einer starken Änderung beider Resonanzfrequenzen und damit zu einer großen Bandbreite führt. Hierdurch wird die Durchlasskurve im Durchlassbereich stark verzerrt und es bilden sich links und rechts der Mittenfrequenz zwei Resonanzpunkte. Die Durchlasskurve bekommt eine "Delle". Hieran ist die überkritische Kopplung gut zu erkennen.

[question:AD227] 
[question:AD228] 
[question:AD229] 