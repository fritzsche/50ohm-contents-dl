%Bei der Berechnung der effektiven Strahlungsleistung (ERP) ist nur die Energie zu berücksichtigen, die auch tatsächlich der Antenne zugeführt wird, d. h. möglicherweise vorhandene Kabelverluste können abgezogen werden, bevor mit dem Gewinnfaktor multipliziert wird.

Die effektiven Strahlungsleistung (ERP) einer Antenne bezieht sich auf den Halbwellendipol. Bei der Strahlungsleistung ist nur die Energie relevant, die tatsächlich an der Antenne ankommt. Durch Kabeldämpfung etc. kann die Leistung des Senders in der realen Welt nicht vollständig der Antenne zugeführt werden. Diese verlorene Leistung darf nicht in die Berechnung Stahlungsleistung eingehen. Der Antennengewinn in der Vorzugsrichtung ist natürlich Teil der Rechnung. ERP ist das Produkt aus zugeführter Leistung und dem Antennengewinn.

[question:AG501]

Bei der nächsten Frage ist unbedingt auf die Rechenzeichen zu achten. Die Verluste werden von der Sendeleistung subtrahiert und danach mit dem Gewinnfaktor ($G_{Antenne}$) multipliziert.
Da die ERP berechnet werden soll, muss der Bezug auf einen Halbwellendipol erfolgen.

[question:AG502]

---

Einen Hinweis auf die richtige Lösung gibt schon der Frequenzplan für den Amateurfunkdienst. Dort ist als maximale Leistung für das 630-m-Band 1 W ERP vorgegeben.

Ein Halbwellendipol hätte eine Länge von 315 m. Das ist für die meisten Funkamateure nicht realisierbar. Zwangsläufig kommen stark verkürzte Antenne zum Einsatz. Verkürzte Antenne haben leider einen schlechteren Wirkungsgrad als ein Halbwellendipol in voller Länge. Ein "Antennengewinn" von -20dBd ist also nicht überraschend. Da das Koaxialkabel kurz ist kann dessen Dämpfung in diesem Frequenzbereich vernachlässigt werden.

Zu Lösung der Frage AG503 kann auf die Tabelle mit den Leistungsverhältnissen in der Formelsammlung zurückgreifen. Dort ist für -20 dB der Faktor 0,01 angegeben.

$50  \textrm{ W }\cdot 0,01 = 0,5  \textrm{ W }$

Die richtige Lösung ist 0,5 W.

%Ein Sender für das 630 m-Band mit 50 W Ausgangsleistung ist mittels eines kurzen Koaxialkabels an eine Antenne mit 20 dBd Verlust angeschlossen. Welche ERP wird von der Antenne abgestrahlt?

[question:AG503]

<tip>
 Diese Tabelle ist in der Formelsammlung enthalten und steht während der Prüfung zur Verfügung.
  
| r:   | r: Leistungsverhältnis | r: Spannungsverhältnis |
| -20 dB | 0,01 | 0,1 |
| -10 dB | 0,1 | 0,32 |
| -6 dB | 0,25 | 0,5 |
| -3 dB | 0,5 | 0,71 |
| -1 dB | 0,79 | 0,89 |
| 0 dB | 1 | 1 |
| 1 dB | 1,26 | 1,12 |
| 3 dB | 2 | 1,41 | 
| 6 dB | 4 | 2 |
| 10 dB | 10  | 3,16 |
| 20 dB | 100 | 10 |
[table:Pegel_Verhältnis:Leistungs- und Spannungsverhältnisse für wichtige Dämpfungs- und Verstärkungswerte]

</tip>