<left>
[picture:489:a_frequenzvervielfacher_schaltung:Beispiel für eine Schaltung eines Frequenzvervielfachers mit Klasse-C-Verstärker ohne Basis-Vorspannung]
</left>
<right>
* Eingangssignal wird einer nichtlinearen Verzerrerstufe zugeführt
* Z.B. Klasse-C-Verstärker, durch Betrieb ohne Basis-Vorspannung
* Signal wird stark verzerrt
* Mit Filter wird die gewünschte Oberschwingung selektiert
</right>
<note>
Verstärkerschaltungen kommen später im Kapitel.
</note>
---
<left>
[picture:489:a_frequenzvervielfacher_schaltung:Beispiel für eine Schaltung eines Frequenzvervielfachers mit Klasse-C-Verstärker ohne Basis-Vorspannung]
</left>
<right>
* Nur ganzzahlige Vielfache möglich
* In der Regel wird die 2. oder 3. Harmonische verwendet
* Höhere Frequenzvervielfachung mit hinteinander geschalteten Stufen
</right>
<note>
</note>
---
[question:AF312]
---
[question:AF311]
---
### Schirmung

* Es werden Zwischenfrequenzen erzeugt
* Diese führen oft zu Störungen
* Alle Stufen müssen gut abgeschirmt sein

---
[question:AF313]
---
### Mehrere Vervielfacher-Stufen

* Die einzelnen Frequenzen zwischen den Vervielfacher-Stufen können zu Störungen führen
* Weg durch die einzelnen Stufen verfolgen und die einzelnen Frequenzen berechnen
* Die Reihenfolge der Stufen ist wichtig zur Ermittlung der Störfrequenzen

---
[question:AF314]
---
#### Lösungsweg
* gegeben: $f_{Sender} = 432MHz$
* gegeben: $f_{Grund} = 12MHz$
* gegeben: $f_{QRM} = 144MHz$
* gesucht: Vervielfachungskombination

<fragment>
$n = \frac{f_{Sender}}{f_{QRM}} = \frac{432MHz}{144MHz} = 3$
</fragment>
<fragment>
Es ist nur die Kombination aus $\textrm{Grundfrequenz}\,\cdot 2\cdot 2\cdot 3\cdot 3$ möglich, da diese als letzte eine Verdreifachung der Frequenz vornimmt.
</fragment>
---
Gegenprobe:
$\begin{split}f_{Sender} &= f_{Grund}\cdot 2\cdot 2\cdot 3\cdot 3\\ &= 12MHz\cdot 2\cdot 2\cdot 3\cdot 3\\ &= 24MHz\cdot 2\cdot 3\cdot 3\\ &= 48MHz\cdot 3\cdot 3\\ &= \bold{144MHz}\cdot 3\\ &= 432MHz\end{split}$
