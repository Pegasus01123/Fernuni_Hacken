---
tags:
  - Wireshark
---

Als Aufgabe gab es heute den Mitschnitt einiger Datenpakete. Die Endung .pcapng legt nahe das Dokument in Wireshark zu öffnen. 

Das sah dann so aus:

![2023-12-03_16-47](https://github.com/Pegasus01123/fernuni_hacken/assets/72656695/738725eb-6155-4acd-8437-aadb7c1b0593)

Beim durchscrollen viel mir auf dass sich zwei IP Adressen mehr oder weniger Abwechselten. Daraufhin habe ich den Stream auf TCP gefiltert und das erhalten:
![2023-12-03_16-48](https://github.com/Pegasus01123/fernuni_hacken/assets/72656695/8f606a89-0830-462c-aac6-4003ac6b03b5)


Wenn man dem Ersten Stream folgt (No 3- 8) sieht man nichts interessantes.<img width="913" alt="2023-12-03 16_49_23-kali (Sicherungspunkt 3)  wird ausgeführt  - Oracle VM VirtualBox" src="https://github.com/Pegasus01123/fernuni_hacken/assets/72656695/c2182d1f-9122-4597-9782-7e88ddfbed53">

Beim nächsten findet man eine Unterhaltung zwischen zwei Personen:
![2023-12-03_16-50](https://github.com/Pegasus01123/fernuni_hacken/assets/72656695/684d4927-f435-42cc-a937-15720e6f21f4)

Somit ist die Flag auch gefunden.
