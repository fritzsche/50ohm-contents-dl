%TODO: Dieses Kapitel ist noch nicht abschließend bearbeitet und muss noch Überarbeitet werden!!!

Der Verstärkungsfaktor vor Verstärkern wird meist in Dezibel (1/10 Bel) ausgedrückt. Dabei ist immer zu berücksichtigen, ob man die Spannungsverstärkung oder die Leistungsverstärkung eines Verstärkers betrachtet.
*Leistung und Spannung verhalten sich nämlich quadratisch zueinander* und müssen unterschiedlich berechnet werden!
Eine Verdoppelung der Spannung durch einen Verstärker entspricht einer Leistungsvervierfachung (bei gleicher Impedanz am Ein- und Ausgang des Verstärkers).

Bei Betrachtung der Spannungsverstärkung eines Verstärkers können wir diese in Dezibel (dB) angeben. Hierzu müssen wir die beiden Spannungspegel im Quadrat (Ausgangspegel und Eingangspegel) zueinander ins Verhältnis setzen und dann den Zehner-Logarithmus ziehen. Wir erhalten dann das Ergebnis in Bel. Um dieses noch in Dezibel umzurechnen, muss es noch mit dem Faktor 10 multipliziert werden.
Um direkt die Spannungspegel in der Berechnung verwenden zu können und diese vorher nicht quadrieren zu müssen, kann man das Quadrat als Faktor 2 aus dem Zehner-Logarithmus herausziehen.
Daher muss das Ergebnis in diesem Fall noch mit dem Faktor 2 multipliziert werden. Insgesamt also mit dem Faktor 10 * 2 = 20.

<tip>
Kurzer Exkurs in die Lograrithmen-Rechnung

Ein Quadrat innerhalb des Logarithmus kann aus dem Logarithmus "herausgezogen" werden. Hierbei wird aus dem Quadrat der Faktor 2. Analog verhält es sich mit höheren Potenzen. Hierbei wird die Potenz immer zum Multiplikator vor dem Logarithmus, wenn man diese aus dem Logarithmus "herauszieht".

Beispiel: log(x^2) = 2 * log(x) 
</tip>

%TODO: Tip mit Berechnung von Bel und Dezibel bei Spannungs und Leistungsverhältnissen mit Erklärung warum der Faktor 2 noch vor den Logarithmus wandert (Quadrat aus Logarithmus wird zu Faktor 2 bei rausziehen).

Bei Betrachtung der Leistungsverstärkung eines Verstärkers können wir diese ebenfalls in Dezibel (dB) angeben. Hierzu müssen wir die beiden Leistungspegel (Ausgangspegel und Eingangspegel) zueinander ins Verhältnis setzen und dann den Zehner-Logarithmus ziehen. Anschließend muss das Ergebnis noch mit dem Faktor 10 multipliziert werden, um die Leistungsverstärkung in dB zu erhalten.

Die entsprechenden Formeln zur Berechnung der Leistungsverstärkung und Spannungsverstärkung von Verstärkern findet man auch in der Formelsammlung.

[question:AD427]
[question:AD428]

Will man nun umgekehrt aus der Leistungsverstärkung in dB das Verhältnis von Ausgangs- zu Eingangsleistung berechnen, so muss man zunächst den dB-Wert wieder in Bel umrechnen, indem man ihn zunächst durch den Faktor 10 teilt. Diesen Wert muss man dann als 10er-Exponent berechnen.
Daraus ergibt sich der Verstärkungsfaktor, der mit der Eingangsleistung multipliziert werden muss, um die Ausgangsleistung eines Verstärkers zu erhalten.
Hierbei sollte man sich bestimmte Verhältnisse in dB merken (siehe Formelsammlung!). Hierdurch kann die Berechnung deutlich vereinfacht werden.

Beispiel:
Um eine Verstärkung von 13dB in den Verstärkungsfaktor umzurechnen, kann man sich merken, dass 3 dB immer einer Leistungsverdoppelung entsprechen und 10dB einer Leistungsverzehnfachung. Man multipliziert in diesem Fall die Verstärkungen 2 und 10 miteinander und erhält für 13dB den Verstärkungsfaktor 20.

<tip>
Man kann sich bei Rechnung mit dB-Werten merken, dass eine Addition von einzelnen (bekannten) dB-Werten immer einer Mulplikation der entsprechenden Verstärkungsfaktoren entspricht.

Beispiel:
  
3 dB = Faktor 2 für Leistung und Faktor $\sqrt{2}$ für Spannung
6 dB = Faktor 4 für Leistung und Faktor $\sqrt{4}$ für Spannung
10 dB = Faktor 10 für Leistung und Faktor $\sqrt{10}$ für Spannung
20 dB = Faktor 100 für Leistung und Faktor $\sqrt{100}$ für Spannung

26 dB für Leistung = 20dB + 6dB = Faktor 100 * Faktor 4 = Faktor 400
Damit entspricht eine Leistungsverstärkung von 26 dB einem Leistungsverstärkungsfaktor von 400.
  
Die entsprechende Spannungsverstärkung errechnet sich zu:
Faktor 10 * Faktor 2 = Faktor 20
Alternativ: $\sqrt{400}$, wenn man den Leistungsverstärkungsfaktor zugrunde legt.
</tip>

[question:AD426]