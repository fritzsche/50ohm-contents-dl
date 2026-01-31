In der Klasse N haben wir gelernt: Ist eine Antenne perfekt an die Zuleitung (z. B. ein Koaxialkabel) angepasst, zeigt das SWR-Meter den Wert 1 an. Dies ist der bestmögliche Fall, da die gesamte Sendeleistung von der Antenne aufgenommen wird und keine Leistung zum Sender zurückreflektiert wird. Ist hingegen gar keine Antenne angeschlossen oder ist die Übertragungsleitung unterbrochen bzw. kurzgeschlossen, steigt der SWR-Wert gegen unendlich ($\infty$). In diesen Fällen wird die Sendeleistung nahezu vollständig reflektiert. Eine solche vollständige Rückreflexion kann im schlimmsten Fall zur Beschädigung der Endstufe des Senders führen. In der Klasse E vertiefen wir das Thema nun etwas und lernen auch Werte zwischen 1 und $\infty$ kennen.

Das Stehwellenverhältnis (SWR), als Formelsymbol $s$, lässt sich aus der vorlaufenden Leistung $P_\text{V}$ und der rücklaufenden Leistung $P_\text{R}$ berechnen. Den entsprechenden Zusammenhang finden wir in der Formelsammlung:

$s = \frac{\sqrt{P_\text{V}}+\sqrt{P_\text{R}}} { \sqrt{P_\text{V}}-\sqrt{P_\text{R}}}$

Gibt zum Beispiel der Sender eine Leisung von $P_\text{V}=\qty{100}{\text{Watt}}$ ab, und es werden $P_\text{R}=\qty{25}{\text{Watt}}$ von der Antenne in Richtung Sender zurück reflektiert, so ergibt sich:

$s = \frac{\sqrt{100}+\sqrt{25}}{\sqrt{100}-\sqrt{25}} = \frac{10+5}{10-5} = \frac{15}{5} = 3$

Das bedeutet, dass ein SWR von $3$ einer Reflektion von $\frac{\qty{25}{\watt}}{\qty{100}{\watt}}=\qty{25}{\percent}$ entspricht. Weitere entsprechungen sind in der Tabelle [ref:e_swr_werte] dargestellt.

<margin>
| l: SWR | l: Reflektierte Leistung |
| 1 | 0% |
| 1,5 | 4% |
| 2 | 11,1% |
| 2,5 | 18,4% |
| *3* | *25%* |
| 4 | 36% |
| 6 | 51% |
| 10 | 66.9% |
| 20 | 81.9% |
| $\infty$ | 100% |
[table:e_swr_werte:SWR-Werte in Bezug auf die reflektierte Leistung]
</margin>

---

<tip>
Zur Beantwortung der folgenden Fragen reicht es aus zu wissen, dass ein ein Stehwellenverhältnis von 3 einer Reflexion von 25% der Energie entspricht, d.h. die rücklaufende Welle überträgt ein Viertel der Energie der vorlaufenden Welle. Entsprechend werden nur 75% der Energie am Ende der Leitung z. B. an eine Antenne oder einen Verlustwiderstand abgegeben (also nicht reflektiert). 
</tip>

[question:EG401]
[question:EG402]
[question:EG403]