Wichtige Messungen für den Funkamateur an Sendern sind Messungen von Ausgangsleistungen an Sendern oder die Messung von HF-Spannungen in HF-Schaltungsteilen.

Bei Messung von Senderausgangsleistungen muss der Sender mit einer definierten Impedanz, die zur Ausgangsimpedanz des Senders passt, abgeschlossen werden. Im Amateurfunk beträgt die übliche Impedanz (Senderabschluss) 50 Ohm. Der Abschluss kann auch direkt in der Messschaltung erfolgen, was jedoch nur bei kleine Leistungen sinnvoll ist.

Die Messung von HF-Spannungen erfolgt mittels eines HF-Tastkopfes über Diodengleichrichtung und anschließende Glättung der entstehenden Gleichspannung mit einem nachgeschalteten Kondensator.

Bei HF-Tastköpfen mit nur einer Diode ist am Messausgang die Spitzenspannung der zugeführten HF-Spannung abzüglich der Forward-Spannung der verwendeten Diode und eines ggf. vorhandenen vorgeschalteten Spannungsteilers messbar.

[question:AI608]

Zur Erhöhung der Messgenauigkeit, insbesondere bei kleinen Leistungen im VHF/UHF-Bereich, verwendet man oft eine doppelte Gleichrichtung über 2 Dioden, so dass beide Halbwellen der HF gleichgerichtet werden (Doppelte Spitzenspannung) und, abzüglich 2 mal der Forward-Spannung der verwendeten Dioden, als addierte Messspannung am Messausgang zur Verfügung stehen.

[question:AI605]
[question:AI604]

Bei höheren HF-Leistungen muss ein entsprechend belastbares Dämpfungsglied vorgeschaltet werden, das einen Großteil der Senderausgangsleistung, die gemessen werden soll, aufnimmt. Das Dämpfungsglied ist bei der Berechnung der Leistung zu berücksichtigen.

[question:AI609]

Um Leistungen und HF-Spannungen mit den vorgenannten Schaltungen exakt messen zu können, müssen diese kalibriert werden um entsprechende Korrekturwerte für die Messungen zu erstellen.

[question:AI612]

Betrachten wir nun die Berechnung der Schaltungen im Detail.
Ein HF-Tastkopf mit einfacher Gleichrichtung und anschließender Glättung wird wie folgt berechnet:

Das HF-Eingangssignal wird durch den vorhandenen Widerstand (oder Kombination aus Einzelwiderständen) am Eingang impedanzrichtig abgeschlossen. In der dargestellten Schaltung wird die HF-Spannung durch den nachfolgenden Spannungsteiler halbiert (wobei dieser ebenfalls bzgl. der Impedanz wirksam ist). Anschließend erfolgt die Spitzenwert-Gleichrichtung mittels Diode, deren Ausgansspannung sich als Spitzenwert abzüglich der Forward-Spannung der Diode berechnet und im nachgeschalteten Kondensator gepuffert wird.

Bei 1 Watt Eingangsleistung in einem 50 Ohm System ergibt sich eine Eingangsspannung von 7,07 V Effektiv-Spannung und 10V Spitzenspannung.
Der nachgeschaltete Spannungsteiler halbiert diese Spannung auf 5V Spitzenspannung, die nach Gleichrichtung durch die Diode abzüglich deren Forward-Spannung von 0,23V noch 4,77 Volt beträgt. Gemessen werden dann gerundet ca. 4,8 Volt am Ausgang der Schaltung.

[question:AI610]

Umgekehrt kann aus der gemessenen Gleichspannung die der Schaltung zugeführte Leistung berechnet werden.

Gemessen werden am Ausgang der Schaltung 14,9 V Spitzenspannung. Wegen der Forward-Spannung der Diode beträgt der HF-Spitzenwert vor der Diode 15,6 V. Unter Berücksichtigung des vorgeschalteten Spannungsteilers ergibt dies eine HF-Spitzenspannung von 31,2 V.  Dies entspricht einer Eingangsleistung an einem 50 Ohm-System von 9,73 Watt und damit ca. 9,7 Watt.

[question:AI611]

Bei HF-Tastköpfen und Leistungsmessern mit doppelter Spitzenwertgleichrichtung (2 Dioden) erfolgt die Berechnung wie bei Einfachgleichrichtung, jedoch ist die doppelte Spitzenspannung am Ausgang und der doppelte Spannungsabfall durch 2 Dioden zu berücksichtigen.

[question:AI607]
[question:AI606]

Um anzuzeigen, dass ein Sender über seine Antenne Leistung abstrahlt kann ein Feldstärkeanzeiger verwendet werden. Hierbei wird über eine Messantenne einer Diode die empfangene HF zugeführt und durch die Diode gleichgerichtet. Anschließend wir die gleichgerichtete Spannung über HF-Drosseln einem Kondensator zugeführt, der die gleichgerichtete Spannung puffert. Die Anzeige erfolgt durch ein empfindliches Strommessgerät. Je höher der Zeigerausschlag des Messinstruments ausfällt, desto höher ist die an der Antenne gemessene HF-Feldstärke. Um exakte Messungen vornehmen zu können muss sowohl die Messantenne als auch der Feldstärkemesser kalibriert werden.

[question:AI613]