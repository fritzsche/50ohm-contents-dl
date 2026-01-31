<left>
[picture:343:a_Brückenschaltung:Typische Brückenschaltung mit 4 Widerständen]
  
$\frac{R_1}{R_2} = \frac{R_3}{R_4}$
</left>
<right>
* Schaltung aus 4 Widerständen zur Widerstandsmessung
* Zwei parallel geschaltete Spannungsteiler
* Bei gleich großen Spannungsteilerverhältnissen fließt kein Strom über die Brücke
</right>
<note>
Messbrücke nach Wheatstone
</note>

---
[question:AD111]
---
[question:AD112]
---
[question:AD113]
--- style="font-size: 0.7em;"
#### Lösungsweg
* gegeben: $R_1 = R_4 = 1kΩ$
* gegeben: $R_2 = R_3 = 10kΩ$
* gegeben: $U = 11V$
* gesucht: $U_{AB}$

<fragment>
$\frac{U_A}{U} = \frac{R_1}{R_1 + R_2} \Rightarrow U_A = \frac{R_1}{R_1 + R_2} \cdot U = \frac{1kΩ}{1kΩ + 10kΩ} \cdot 11V = 1V$
</fragment>
<fragment>
$\frac{U_B}{U} = \frac{R_3}{R_3 + R_4} \Rightarrow U_B = \frac{R_3}{R_3 + R_4} \cdot U = \frac{10kΩ}{10kΩ + 1kΩ} \cdot 11V = 10V$
</fragment>
<fragment>
$U_{AB} = |U_A - U_B| = |1V - 10V| = 9V$
</fragment>