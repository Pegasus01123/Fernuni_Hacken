---
tags:
  - Wireshark
  - PDF
  - PasswortSchutz
---
# Nochmal zugehört
<h2>Aufgabe:</h2>
<img width="351" alt="image" src="https://github.com/Pegasus01123/fernuni_hacken/assets/72656695/734f14c7-45f4-4240-8a05-6f822321dce3">

<h2>Meine Lösung:</h2>

Eine weitere .pcapng Datei. 
Das folgen der verschiedenen TCP Streams brachte diese drei  Unterhaltungen.
<img width="525" alt="Pasted image 20231214151004" src="https://github.com/Pegasus01123/fernuni_hacken/assets/72656695/35a56810-745b-4d86-ab99-65f533eef1de">
<img width="557" alt="Pasted image 20231214151041" src="https://github.com/Pegasus01123/fernuni_hacken/assets/72656695/9266c7ae-73ba-447a-ac52-536f9b58ee99">

In diesem Stück sieht man das eine Datei mit dem Namen `streng-geheim.pdf`übertragen wurde.

<img width="255" alt="Pasted image 20231214151111" src="https://github.com/Pegasus01123/fernuni_hacken/assets/72656695/199a8107-3731-4027-9210-0dbf3f1d6274">

Das Passwort fand sich in einem UDP Stream.

<img width="575" alt="Pasted image 20231214150842" src="https://github.com/Pegasus01123/fernuni_hacken/assets/72656695/66415aa9-d287-499a-bdd6-2dea49fbadc3">

Da mich das Speichern des PDFs in ASCII Codierung nicht weiterbrachte habe ich den Stream noch mal im RAW Format gespeichert. Diese Datei lies sich dann mit dem Passwort entpacken und anzeigen.

<img width="551" alt="Pasted image 20231214171157" src="https://github.com/Pegasus01123/fernuni_hacken/assets/72656695/5b845279-ce5e-40c4-80e4-132621087e08">

<img width="394" alt="Pasted image 20231214171111" src="https://github.com/Pegasus01123/fernuni_hacken/assets/72656695/1aff1174-a536-42ef-9e07-ffb4e2c97d74">
