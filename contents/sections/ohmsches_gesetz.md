Wir haben bereits die drei wichtigsten Größen der Elektrotechnik kennengelernt, und zwar die elektrische Spannung, den elektrischen Strom und den Widerstand:
* Zunächst haben wir gelernt, dass elektrische Ladungen in Spannungsquellen getrennt werden und dadurch eine elektrische Spannung entsteht. Diese bezeichen wir mit dem Buchstaben $U$ und messen sie in Volt (V).
* Dann haben wir gelernt, dass die elektrische Spannung dafür sorgt, dass in einem geschlossenen Stromkreis ein elektrischer Strom fließt, den wir mit dem Buchstaben $I$ bezeichnen und in Ampere (A) messen.
* Und zu Beginn dieses Kapitels haben wir dann noch gelernt, dass Verbraucher in einem Stromkreis einen Widerstand ausüben und somit den Stromfluss ausbremsen. Den Widerstand bezeichnen wir mit dem Buchstaben $R$ und messen ihn in Ohm (Ω).

%<margin>
%[p-h-o-t-o:147:ohmsches_gesetz_comic:Bildhafte Darstellung der Zusammenhänge des Ohmschen Gesetzes]
%</margin>

[question:NA203]

---

Aber wie hängen diese drei Größen zusammen? Schauen wir uns ein Beispiel in der Abbildung [ref:n_ohmsches_gesetz_stromkreis_mit_batterie] an. Wir haben einen Stromkreis, der aus einer Batterie als Spannungsquelle und einem Widerstand besteht. Wir kennen die Spannung und wir können den Strom messen. Die Batterie hat eine Spannung von 10 V, und es fließt ein Strom von 1 mA.

<margin>
[picture:664:n_ohmsches_gesetz_stromkreis_mit_batterie:Stromkreis mit Batterie]
</margin>

Würde man die 10 V-Batterie in dem Beispiel durch eine 20 V-Batterie ersetzen, dann würde sich auch der Strom von 1 mA auf 2 mA erhöhen. Wenn man also die Spannung verdoppelt, dann verdoppelt sich auch der Strom. Entsprechend würde sich auch der Strom auf 0,5 mA halbieren, wenn man die Spannung auf 5 V halbieren würde.

Wir können ein Muster erkennen: In unserem Beispiel ist die Spannung $U$ in Volt immer 10000-fach größer als der Strom $I$ in Ampere. Oder mathematisch ausgedrückt:

$\dfrac{U}{I} = \dfrac{10 \ \text{V}}{0,001 \ \text{A}} = \dfrac{20 \ \text{V}}{0,002 \ \text{A}} = \dfrac{5 \ \text{V}}{0,0005 \ \text{A}} = 10000 \frac{\text{V}}{\text{A}}$

---

In der Fachsprache nennt man dies Proportionalität: $I$ ist proportional zu $U$. Die Einheiten mal außen vor gelassen, beträgt der sogenannte *Proportionalitätsfaktor* in unserem Beispiel 10000: Nimmt man den einen Wert mal 10000, dann erhält man den anderen Wert.
%Dieses Verhalten kann man sich auch wieder am Wasserkreislauf vorstellen: Wenn die Pumpe mit mehr Druck pumpt, wird auch mehr Wasser durch den Kreislauf fließen.

<indepth>
Der *Proportionalitätsfaktor* ist das zahlenmäßige Verhältnis zweier Größen, die proportional zueinander sind.
</indepth>

Es bleibt aber eine Frage. Wo kommt jetzt dieser Faktor von 10000 her? Die Antwort ist simpel: Das ist unser Widerstand $R$! Und wenn wir jetzt noch die Einheiten betrachten, fügt sich ein Gesamtbild zusammen: Die Einheit Ohm ist nämlich so definiert, dass $1 \ Ω$ dasselbe wie $1 \frac{\text{V}}{\text{A}}$ ist. Daher dürfen wir statt $10000 \frac{V}{A}$ einfach $10000 \ Ω$ schreiben! Unser Widerstand beträgt also 10000 Ω oder kurz 10 kΩ:

$10000 \frac{\text{V}}{\text{A}} = 10000 \ Ω$

%Es stellt sich aber immer noch folgende Frage: Warum fließen in unserem Beispiel genau 1 mA, wenn die Spannung 10 V beträgt? Die Höhe des Stroms hängt vom Wert des Widerstands ab. Ist der Widerstand groß, so wird der Strom klein sein, ist der Widerstand hingegen klein, dann wird der Strom groß sein.

Wir haben gelernt: Den Wert des Widerstands kann man aus der Spannung und dem Strom berechnen. Er ist das *Verhältnis von Spannung und Strom*, oder anders formuliert: Wenn man die Spannung durch den Strom teilt, erhält man den Wert des Widerstands.

---

Diesen Zusammenhang kann man durch die folgende Formel darstellen, die als *Ohmsches Gesetz* bezeichnet wird: 

$ R = \dfrac{U}{I} $

<person>
Der deutsche Physiker *Georg Simon Ohm* hat im Jahre 1826 den Zusammenhang zwischen der elektrischen Spannung, dem elektrischen Strom und dem Widerstand entdeckt. Ihm zu Ehren wird die Formel $ R = \frac{U}{I} $ als Ohmsches Gesetz bezeichnet.
</person>

[question:NB505]

Wenn man allerdings nur den Widerstand und die Spannung kennt und den entsprechenden Strom berechnen möchte, dann kann man das Ohmsche Gesetz wie folgt verwenden: 

$ I = \dfrac{U}{R} $

Für den Fall, dass man nur den Widerstand und den Strom kennt und die entsprechende Spannung berechnen möchte, gibt es eine weitere Variante der Formel: 

$ U = R\cdot I $

[question:NB504]

Man muss sich diese Formeln nicht unbedingt merken. Sie sind auch in der Formelsammlung zu finden, die bei der Prüfung als Hilfsmittel zur Verfügung gestellt wird. Für die Berechnungen kann man in der Prüfung einen Taschenrechner verwenden.

[question:NB502]
[question:NB503]
[question:NB501]
