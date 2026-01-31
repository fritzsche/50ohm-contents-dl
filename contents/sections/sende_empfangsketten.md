Durch die geschickte Kombination von Quellencodierung und Kanalcodierung kann die Bandbreite effektiv genutzt werden. Zugleich können Übertragungsfehler erkannt und berichtigt werden. Die Reihenfolge der Verfahren ist für einen Sender dabei immer die folgende:

1. Quellencodierer: Daten komprimieren
2. Kanalcodierer: Hinzufügen von Redundanz zur Fehlererkennung und -korrektur
3. Mapper: Abbilden binärer Daten auf Symbole z. B. Amplitude und Phase für QAM

Für einen Empfänger funktioniert das Ganze rückwärts: 

1. De-Mapper: Abbilden der Symbole auf binäre Daten
2. Kanaldecodierer: Erkennen und korrigieren von Fehlern
3. Quellendecodierer: Daten dekomprimieren

[question:AF626]
[question:AF628]
[question:AF629]
[question:AF627]
