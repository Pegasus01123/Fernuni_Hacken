---
tags:
  - Ghidra
  - Bufferoverflow
---
# Benutzerregistrierung
<h2>Aufgabe:</h2>
<img width="356" alt="image" src="https://github.com/Pegasus01123/fernuni_hacken/assets/72656695/5593ce62-4b16-48d6-8284-ea2dd307e07f">

<h2>Meine Lösung:</h2>

Eine Benutzerregistrierung die über netcat zu erreichen ist.
Nach eingabe eines Namens und eines Passworts bekommt man diese Meldung:

![2023-12-01_21-12](https://github.com/Pegasus01123/fernuni_hacken/assets/72656695/19687a25-f596-4b60-b274-a81f12693c6d)


Wenn man sich die Datei main in Ghidra öffnet  findet man in der Funktion main dieses Programm:
<img alt="Programm in Ghidra" src="https://github.com/Pegasus01123/fernuni_hacken/assets/72656695/5f07b052-fcd0-4b99-adbd-d408922427f2">

In Zeile 49 und 50 sieht man die Eingabe für Namen kleiner als 32 Zeichen und die Eingabe für Passwort kleiner als 256 sein muss.
Also habe ich für Namen 33 "a" eingegeben und für Passwort 257 "a".
Damit ich mich nicht verzähle und neu anfangen muss habe ich die "a" für Passwort im Notepad zählen lassen.
Mit der Eingabe kam ich an die Flag.

 ![2023-12-01_21-24](https://github.com/Pegasus01123/fernuni_hacken/assets/72656695/cbba077a-d260-4b1d-84d4-f535a00b7bd2)
