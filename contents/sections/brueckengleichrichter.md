Durch den geringen Aufwand ist der Brückengleichrichter eine häufig verwendete Gleichrichterschaltung. Dazu benötigt man einen Trafo und 4 Dioden. In der Abbildung [ref:a_brueckenlgeichrichter] ist ein solcher Brückengleichrichter dargestellt.

<margin>
[picture:965:a_brueckenlgeichrichter:Brückengleichrichter]
</margin>

---

In dem nebenstehenden Applet kann man bei dargestellter Polarität der Trafospannung $U_a$ bzw. $U_s$ den Laststrom in seinem Stromverlauf verfolgen und erkennen, dass der dieser stets in gleicher Richtung durch den Lastwiderstand $R$ fließt. Der Spannungsabfall am Lastwiderstand $R_L$ ist eine pulsierende Gleichspannung (DC), die aus positiven sinusföhrmigen Halbwellen besteht. Diese Spannung hat eine Frequenz $f=\qty{100}{\hertz}$.

<margin>
[include:applet_gleichrichter_2]
</margin>

---

<margin>
[photo:296: Brückengleichrichter Bauformen: Bauformen von Brückengleichrichtern]
Die Beschriftung der Anschlüsse ist zu beachten.

  1. Hochstrom-Brückengleichrichter 26 MB 20 A (200 V 25 A) im Metallgehäuse zur direkten Montage auf einem Kühlkörper
  2. B80 C 5000/3300 bedeutet: maximal 80 V Betriebsspannung, C kapazitive Last max. 2500 µF mit Schutzwiderstand R = 1 Ohm,  maximaler Dauerlaststrom: 5000 mA mit Kühlkörper, 3300 mA ohne Kühlkörper
  3. BY 225 Brückengleichrichter - besonderes Gehäuse
  4. runde Bauform eines Brückengleichrichters B 80 C 1000
  5. B40 C 1500 - die veränderte Anschlussfolge ist zu beachten
  6. FPU 4M ( 1000 V - 4 A)
  7. im Kunststoff eingeprägte Anschlussfolge
</margin>

[question:AD305]

---
% TODO Frage 1180 ggf. bei Restwelligkeit behandeln

Wenn man nach dem Brückengleichrichter einen Ladekondensator $C_L$ und ein LC-Siebglied (vgl. Abbildung [ref:a_netzteil_Ucs] verbaut, erreicht man damit eine kleinere Amplitude in der pulsierenden Ausgangsgleichspannung. Somit haben wir ein konventionelles Netzteil. 

% TODO Schaltungsbild einfügen
<margin>
[picture:66:a_netzteil_Ucs:Gleichrichterschaltung mit Siebung]
</margin>

Um jetzt die Spannung am Siebkondensator $C_S$ zu bestimmen, sollten wir wissen, dass die Kondensatoren sich auf die Spitzenspannung $\hat{U}$ der Sekundärespannung ${U}_{SEK}$ des Trafos aufladen.

$\hat{U}={U}_{eff}\cdot\sqrt{2}$

Weiterhin müssen wir beachten, ob der Trafo ein Übersetzungsverhältniss $ü$ aufweist. In unserem Beispiel hat der Trafo ${\"u}=\frac{8}{1}$ und somit können wir mit der Formel $\frac{8}{1}=\frac{{U}_{PRIM}}{{U}_{SEK}}$ nach ${U}_{SEK}$ umstellen. Wir kommen somit auf folgende Gleichung:
${U}_{SEK}=\frac{{U}_{PRIM}}{8}=\frac{{U}_{eff}\cdot\sqrt{2}}{8}=\frac{230V\cdot 1,414}{8}=\frac{325,22V}{8}=40,65V$

% Anmerkung DC4LW 2024-05-29: Muss die Diodenspannung nicht auch noch von U_{SEK} abgezogen werden? Ergänzung: Habe erfahren, dass bei Leerlauf die Diodenspannung vernachlässigt werden kann.

[question:AD306]