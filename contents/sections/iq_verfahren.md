% TODO neu formulieren
% Idee DL9MJ: Beispiel mit Bild je ein Bit in I und Q und wie das Signal für 00, 01, 10, 11 aussieht

QAM kann besonders einfach mit Hilfe von zwei Trägern derselben Frequenz erzeugt werden. Einer der beiden Träger muss dabei um 90° phasenverschoben sein. Beide Träger werden dann jeweils mit einem eigenen Signal amplitudenmoduliert. Das eine Signal wird als I (für In-Phase Component) und das andere Signal als Q (für Quadrature Phase Component) bezeichnet. Der phasenverschobene Träger wird dabei mit dem Q-Signal moduliert. In Anschluss werden die beiden modulierten Träger überlagert, wobei ein Träger entsteht, der sich sowohl in der Amplitude als auch in der Phase ändert.
<indepth>
[include:applet_iq]
</indepth>
  
%TODO BILD QAM4 QAM8 oder mehr?

[question:AE404]
[question:AF632]

Die Grundidee, ein Signal in zwei Teilen getrennt zu verarbeiten, findet auch in der digitalen Signalverarbeitung breite Anwendung. Es wird nach den beiden Teilsignalen als I/Q-Verfahren bezeichnet. Das I/Q-Verfahren ermöglicht es, jedes beliebige Signal zu erzeugen. Dazu besteht der zu modulierende Datenstrom aus einem I- und einem Q-Anteil. Zwei D/A-Umsetzer wandeln jeweils einen der beiden Anteile in ein analoges I- bzw. Q-Signal um. Mit dem I- und dem Q-Signal werden wiederum die beiden phasenverschobenen Träger moduliert. Im letzten Schritt werden diese zu einem Träger überlagert, der ausgesendet wird.

Entsprechend wird auch auf der Empfängerseite vorgegangen. Das Eingangssignal wird mit einem Träger gemischt, um das I-Signal zu erhalten, das dann mittels A/D-Umsetzer in den I-Anteil eines Datenstroms umgewandelt wird. Gleichzeitig wird das Eingangsignal aber auch mit einem um 90° phasenverschobenen Träger gemischt, um das Q-Signal zu erhalten, das wiederum mittels eines A/D-Umsetzers in den Q-Anteil des Datenstroms umgewandelt wird.

[question:AF633]

Ein solcher digitaler Datenstrom kann immer einen bestimmten Frequenzbereich des Eingangssignals abbilden, der um eine Mittenfrequenz herum liegt. Wird das Eingangssignal beispielsweise mit einem 435 MHz-Träger und einem um 90° phasenverschobenen 435 MHz-Träger gemischt und die beiden entstehenden Signale durch A/D-Umsetzer digitalisiert, dann bildet der entstehende I/Q-Datenstrom den Frequenzbereich um 435 MHz herum ab.

% TODO Verweis auf Abtasttheorem?
Die abgedeckte Bandbreite hängt dabei von der Abtastrate der A/D-Umsetzung ab. Die Bandbreite in Hz entspricht dabei der Abtastrate in Samples pro Sekunde. Werden in unserem Beispiel sowohl der I- als auch der Q-Anteil mit 10 Millionen Samples pro Sekunde abgetastet, dann kann der entstehende I/Q-Datenstrom einen Frequenzbereich von 10 MHz Bandbreite abdecken, also von -5 MHz bis +5 MHz in Bezug auf die Mittenfrequenz. Der Datenstrom deckt dann also die Frequenzen von 430 bis 440 MHz ab.

[question:AF634]
[question:AF635]
[question:AF636]
