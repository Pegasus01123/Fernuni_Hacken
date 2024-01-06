---
tags:
  - Wireshark
---

Als Aufgabe gab es heute den Mitschnitt einiger Datenpakete. Die Endung .pcapng legt nahe das Dokument in Wireshark zu öffnen. 
Das sah dann so aus:
![[2023-12-03_16-47.png]]
Beim durchscrollen viel mir auf dass sich zwei IP Adressen mehr oder weniger Abwechselten. Daraufhin habe ich den Stream auf TCP gefiltert und das erhalten:
![[2023-12-03_16-48.png]]
Wenn man dem Ersten Stream folgt (No 3- 8) sieht man nichts interessantes.![[2023-12-03 16_49_23-kali (Sicherungspunkt 3) [wird ausgeführt] - Oracle VM VirtualBox.png]]
Beim nächsten findet man eine Unterhaltung zwischen zwei Personen:
![[2023-12-03_16-50.png]]Somit ist die Flag auch gefunden.