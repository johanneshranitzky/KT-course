# Fragebogen: Huffman-Codierung (huffman.py)

Nach dem Ausführen des Skripts und **Einfügen der Konsolenausgabe** (Merge-Symbol in der Task-Card):

---

**1. Konsolenausgabe**

*(Wird per „Konsolenausgabe einfügen“ unten eingefügt. Danach bitte kommentieren.)*
Enter the string to compute Huffman Code Tree: ABBABCBBABCA
---------------------------------------------------------
Dictionary of Characters with char frequency:       {'A': 4, 'B': 6, 'C': 2}
Dictionary converted into a list:                   dict_items([('A', 4), ('B', 6), ('C', 2)])
List of characters sorted to descending frequency:  [('B', 6), ('A', 4), ('C', 2)]
Huffman Code Dictionary:                            {'C': '00', 'A': '01', 'B': '1'}

 Char | Huffman code 
----------------------
 'B'  |           1
 'A'  |          01
 'C'  |          00



---

**2. Deine Kommentierung**

- Was zeigen die ausgegebenen Huffman-Codes?  
  *[kurz beschreiben]*
Die ausgegebenen Huffman-Codes zeigen, welcher Binärcode den einzelnen Zeichen zugeordnet wird. In diesem Beispiel hat B den Code 1, A den Code 01 und C den Code 00. Man sieht daran, dass die Zeichen unterschiedlich lange Codes bekommen, abhängig davon, wie oft sie in der Zeichenkette vorkommen.
- Warum haben häufigere Zeichen kürzere Codewörter?  
  *[kurz begründen]*
Häufigere Zeichen haben kürzere Codewörter, weil dadurch die gesamte Nachricht mit weniger Bits codiert werden kann. Da B hier am häufigsten vorkommt, bekommt es mit 1 den kürzesten Code. Seltenere Zeichen wie A und C bekommen längere Codes. So wird die Codierung insgesamt effizienter.