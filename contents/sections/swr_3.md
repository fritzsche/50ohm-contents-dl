<margin>
[picture:978:a_swr:Stehende Welle]
</margin>
In vielen Fällen kann man das Stehwellenverhältnis einfach angeben, wenn der Speisewiderstand einer Antenne bekannt ist. Sofern sich eine Antenne (oder Dummy-Load) weder induktiv noch kapazitiv verhält, sie also einen reinen Wirkwiderstand darstellt, ergibt sich das Stehwellenverhältnis aus dem Verhältnis zwischen Lastwiderstand und Wellenwiderstand der Leitung, wobei Zähler und Nenner so zu wählen sind, dass sich ein SWR von größer gleich eins ergibt.

Eine Antenne mit einem Speisewiderstand von 100 Ω verursacht bei Speisung mit einem 50 Ω Kabel ein Stehwellenverhältnis von 2, da der Speisewiderstand doppelt so groß ist. Eine Antenne mit einem Speisewiderstand von 10 Ω hätte ein Stehwellenverhältnis von 5, da der Wellenwiderstand der Leitung fünf mal so groß ist.

Zur Beantwortung der folgenden Frage müssen wir uns außerdem daran erinnern, dass der Widerstand eines Faltdipols knapp 300 Ω beträgt.

[question:AG405]

Ein trügerischer Effekt ist die Auswirkung von Leitungsdämpfung auf das Stehwellenverhältnis. Je mehr Verluste eine Leitung aufweist, umso kleiner (also "besser") kann das Stehwellenverhältnis auf dieser Leitung ausfallen. Dies liegt daran, dass eine verlustbehaftete Leitung sowohl die vorlaufende als auch die rücklaufende Leistung reduziert. Selbst wenn am Ende einer Leitung keine Antenne angeschlossen ist (Leerlauf oder Kurzschluss), und dort 100% der Energie reflektiert wird, also das Stehwellenverhältnis *dort* $\infty$ beträgt, so kann man am anderen Ende ein deutlich besseres Stehwellenverhältnis messen. Geht z. B. in Hin-Richtung die Hälfte der Leistung verloren und in Rück-Richtung erneut die Hälft verloren, so reduziert sich die Energie auf ein Viertel ($\frac{1}{2} \cdot \frac{1}{2} = \frac{1}{4}$). Entsprechend zeigt ein Stehwellenmessgerät an der Senderseite des Kabels ein Stehwellenverhältnis von 3 an, was 25% reflektierter Leistung entspricht, obwohl am Ende 100% reflektiert werden – es kommen jedoch nur 25% am Stehwellenmessgerät an.
[question:AG402]
[question:AG403]

Bei einer Leitungsdämpfung von 5 dB und vollständiger Reflektion am Ende des Kabels, z. B. aufgrund einer abgeklemmten Antenne, messen wir gar ein überraschend gutes SWR, obwohl gar keine Antenne angeschlossen ist! Dies können wir wie folgt berechnen:

$s = \frac{\sqrt{P_\mathrm{v}}+\sqrt{P_\mathrm{r}}}{\sqrt{P_\mathrm{v}}-\sqrt{P_\mathrm{r}}}$

Damit lässt sich die folgende Frage berechnen, sofern wir beachten, dass die gemessene rücklaufende Welle nur ein Zehntel der Energie der vorlaufenden Welle ausmacht: 5 dB Dämpfung in Hin-Richtung und 5 dB Dämpfung in Rück-Richtung, entsprechend 10 dB Dämpfung insgesamt. $P_\mathrm{r}$ ist also in diesem Falle nur ein Zehntel von $P_\mathrm{v}$.

[question:AG404]
