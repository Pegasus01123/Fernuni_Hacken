---
tags:
  - Ghidra
  - Bufferoverflow
---

Eine Benutzerregistrierung die über netcat zu erreichen ist.
Nach eingabe eines Namens und eines Passworts bekommt man diese Meldung:
![[2023-12-01_21-12.png]]

Wenn man sich die Datei main in Ghidra öffnet  findet man in der Funktion main dieses Programm:
![[2023-12-01 21_17_38-CodeBrowser_ fernuni_hacken__main.png]]
In Zeile 49 und 50 sieht man die Eingabe für Namen kleiner als 32 Zeichen und die Eingabe für Passwort kleiner als 256 sein muss.
Also habe ich für Namen 33 "a" eingegeben und für Passwort 257 "a".
Damit ich mich nicht verzähle und neu anfangen muss habe ich die "a" für Passwort im Notepad zählen lassen.
Mit der Eingabe kam ich an die Flag.
 ![[2023-12-01_21-24.png]]
 