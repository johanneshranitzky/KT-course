# Fragebogen: Entropie-Analyse (entropy1.py)

Nach dem Ausführen von `entropy1.py` mit eigenem Text in `sampletext.txt`:

**Konsolenausgabe einfügen:** Nutze das Merge-Symbol in der Task-Card, um die Ausgabe aus `console_log.txt` hier einzufügen. Anschließend die Ausgabe **kommentieren**.

---

**1. Konsolenausgabe**

*(Wird per „Konsolenausgabe einfügen“ unten eingefügt. Danach bitte kommentieren.)*

## 1. Konsolenausgabe

```text
-------Table of characters:----------------
      | cnt= 44    p=0.145   H=2.788 bit/char  H_av=0.404 bit/char
e     | cnt= 39    p=0.128   H=2.963 bit/char  H_av=0.380 bit/char
n     | cnt= 25    p=0.082   H=3.604 bit/char  H_av=0.296 bit/char
t     | cnt= 21    p=0.069   H=3.856 bit/char  H_av=0.266 bit/char
i     | cnt= 21    p=0.069   H=3.856 bit/char  H_av=0.266 bit/char
s     | cnt= 18    p=0.059   H=4.078 bit/char  H_av=0.241 bit/char
a     | cnt= 17    p=0.056   H=4.160 bit/char  H_av=0.233 bit/char
h     | cnt= 15    p=0.049   H=4.341 bit/char  H_av=0.214 bit/char
r     | cnt= 13    p=0.043   H=4.547 bit/char  H_av=0.194 bit/char
c     | cnt= 11    p=0.036   H=4.788 bit/char  H_av=0.173 bit/char
u     | cnt= 10    p=0.033   H=4.926 bit/char  H_av=0.162 bit/char
o     | cnt=  9    p=0.030   H=5.078 bit/char  H_av=0.150 bit/char
d     | cnt=  8    p=0.026   H=5.248 bit/char  H_av=0.138 bit/char
b     | cnt=  7    p=0.023   H=5.441 bit/char  H_av=0.125 bit/char
m     | cnt=  6    p=0.020   H=5.663 bit/char  H_av=0.112 bit/char
f     | cnt=  4    p=0.013   H=6.248 bit/char  H_av=0.082 bit/char
.     | cnt=  4    p=0.013   H=6.248 bit/char  H_av=0.082 bit/char
l     | cnt=  4    p=0.013   H=6.248 bit/char  H_av=0.082 bit/char
g     | cnt=  3    p=0.010   H=6.663 bit/char  H_av=0.066 bit/char
,     | cnt=  3    p=0.010   H=6.663 bit/char  H_av=0.066 bit/char
k     | cnt=  3    p=0.010   H=6.663 bit/char  H_av=0.066 bit/char
H     | cnt=  2    p=0.007   H=7.248 bit/char  H_av=0.048 bit/char
ä     | cnt=  2    p=0.007   H=7.248 bit/char  H_av=0.048 bit/char
B     | cnt=  2    p=0.007   H=7.248 bit/char  H_av=0.048 bit/char
p     | cnt=  2    p=0.007   H=7.248 bit/char  H_av=0.048 bit/char
I     | cnt=  1    p=0.003   H=8.248 bit/char  H_av=0.027 bit/char
D     | cnt=  1    p=0.003   H=8.248 bit/char  H_av=0.027 bit/char
T     | cnt=  1    p=0.003   H=8.248 bit/char  H_av=0.027 bit/char
x     | cnt=  1    p=0.003   H=8.248 bit/char  H_av=0.027 bit/char
Z     | cnt=  1    p=0.003   H=8.248 bit/char  H_av=0.027 bit/char
w     | cnt=  1    p=0.003   H=8.248 bit/char  H_av=0.027 bit/char
R     | cnt=  1    p=0.003   H=8.248 bit/char  H_av=0.027 bit/char
M     | cnt=  1    p=0.003   H=8.248 bit/char  H_av=0.027 bit/char
v     | cnt=  1    p=0.003   H=8.248 bit/char  H_av=0.027 bit/char
G     | cnt=  1    p=0.003   H=8.248 bit/char  H_av=0.027 bit/char
E     | cnt=  1    p=0.003   H=8.248 bit/char  H_av=0.027 bit/char
-------------------------------------------

Average Entropy H = 4.289 bit/char
Total Entropy of 304 characters H=1303.97 bit = 163.00 byte
---

**2. Deine Kommentierung:**

- Was fällt dir bei der Entropie deines Textes auf?  
  *[z. B. Vergleich mit anderen Texten, Zeichenverteilung, Redundanz]*
Bei meinem Text sieht man, dass die Entropie mit 4,289 bit/char im mittleren Bereich liegt. Das liegt daran, dass die Zeichen nicht gleichmäßig verteilt sind. Einige Zeichen kommen sehr oft vor, vor allem das Leerzeichen sowie häufige Buchstaben wie e, n, t, i. Dadurch ist der Text teilweise vorhersagbar und enthält Redundanz.
Auffällig ist auch, dass seltene Zeichen wie einzelne Großbuchstaben oder Sonderzeichen zwar einen höheren Informationsgehalt pro Zeichen haben, aber insgesamt nur wenig zur mittleren Entropie beitragen, weil sie nur selten vorkommen.
Im Vergleich zu anderen Texten würde ein stark wiederholender Text eine kleinere Entropie haben, während ein zufälligerer Text mit gleichmäßigerer Zeichenverteilung eine größere Entropie hätte. Man sieht also gut, dass die Entropie direkt von der Häufigkeitsverteilung der Zeichen abhängt: je gleichmäßiger die Verteilung, desto höher die Entropie; je mehr Wiederholungen, desto größer die Redundanz und desto kleiner die Entropie.