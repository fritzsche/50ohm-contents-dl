Wir Menschen sind es gewohnt, die zehn Ziffern von 0 bis 9 zu benutzen. Man spricht von einem Zehnersystem oder Dezimalsystem.

Für Computer ist es hingegen einfacher, mit nur 2 Ziffern zu arbeiten: der 0 und der 1. Dies entspricht zwei Zuständen: Beispielsweise ausgeschaltet und eingeschaltet, "Transistor gesperrt" und "Transistor leitend" oder auch 0 V und 5 V. Es entsteht ein binäres Zahlensystem oder Dualsystem.

[question:EA201]

Das Zählen geht in allen Zahlensystemen gleich (siehe Tabelle [ref:binaer_zahlensysteme]): Man fängt bei 0 an und zählt die Ziffern hoch. Wenn der Ziffernvorrat zu Ende ist, fängt man von vorne an und schreibt dabei vor jede Zahl eine 1. Deshalb kommt im Dezimalsystem nach der 9 die 10. Die Ziffer ganz rechts hat den Wert, den sie selbst darstellt. Man nennt das den Stellenwert 1. 

---

Im Dezimalsystem ist die zweite Ziffer von rechts zehnmal so viel Wert wie sie selbst, hat also den Stellenwert 10. Jede weiter links stehende Stelle ist jeweils zehnmal so viel Wert, wie die rechts daneben stehende. Beispielsweise bedeutet die Dezimalzahl 5573 aus der Tabelle [ref:binaer_stellenwert_dezimal] also eigentlich $5 \cdot 1000 + 5 \cdot 100 + 7 \cdot 10 + 3 \cdot 1$.

<margin>
|c: |c: |c: |c: |
|1000 | 100 | 10 | 1 |
| 5 | 5 | 7 | 3 |
[table:binaer_stellenwert_dezimal:Stellenwerte der vierstelligen Dezimalzahl 5573]

|r: Dezimal | r: Dual |
| 0 | 0 |
| 1 | 1 |
| 2 | 10 |
| 3 | 11 |
| 4 | 100 |
| 5 | 101 |
| 6 | 110 |
| 7 | 111 |
| 8 | 1000 |
| 9 | 1001 |
| 10 | 1010 |
| 11 | 1011 |
| 12 | 1100 |
| 13 | 1101 |
| 14 | 1110 |
| 15 | 1111 |
[table:binaer_zahlensysteme:Zahlen im Dezimal- und im Dualsystem]
</margin>

Im Dualsystem gibt es nur zwei Ziffern, nämlich 0 und 1. Wie in Tabelle [ref:binar_stellenwert_dual] zu sehen ist, hat die erste Stelle von rechts den Stellenwert 1, die zweite 2, die dritte 4, die vierte 8 und so weiter. Die Stellenwerte verdoppeln sich, statt sich zu verzehnfachen, weil es nur zwei Ziffern gibt und nicht zehn. Eine Stelle im Dualsystem nennt man auch Bit.

|c: |c: |c: |c: |c: |c: |c: |c: |
| 128 | 64 | 32 | 16 | 8 | 4 | 2 | 1 |
| 1 | 0 | 0 | 0 | 1 | 1 | 1 | 0 |
[table:binar_stellenwert_dual:Stellenwerte der achtstelligen Dualzahl 10001110]

Wenn man die Stellenwerte kennt, ist das Übertragen von Dualzahlen in das Dezimalsystem einfach. Nehmen wir ein Beispiel aus Tabelle [ref:binar_stellenwert_dual]. Die Dualzahl 10001110 soll in eine Dezimalzahl umgerechnet werden.

1. Man schreibt über jede Ziffer der Dualzahl ihren Stellenwert.
2. Man addiert alle Stellenwerte, unter denen eine 1 steht: $128+8+4+2=142$

[question:EA206]
[question:EA207]
[question:EA208]

Auf dem Papier kann man Dualzahlen mit so vielen Bits schreiben, wie man gerade braucht. In der Digitaltechnik ist das anders. Die Hard- oder Software gibt eine bestimmte Stellenzahl vor, die man auch Breite nennt. Beispielsweise haben Mikrocontroller oder Computer häufig Breiten von 8, 16, 32 oder 64 Bits. In der Darstellung werden Dualzahlen oft vorne mit Nullen aufgefüllt, bis diese Breite erreicht ist. Am Wert der Zahl ändert das nichts.

[question:EA205]

Eine feste Breite begrenzt den Wertebereich. Mit einem Bit sind zwei Werte möglich (0 und 1), mit zwei Bits schon vier (00, 01, 10 und 11) und mit jedem weiteren Bit jeweils doppelt so viele. Mit $n$ Bits lassen sich $2^n$ verschiedene Zahlen darstellen.

[question:EA204]
[question:EA202]
[question:EA203]
