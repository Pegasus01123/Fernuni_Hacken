---
tags:
  - Wireshark
  - PDF
  - PasswortSchutz
---

Eine weitere .pcapng Datei. 
Das folgen der verschiedenen TCP Streams brachte diese drei  Unterhaltungen.

![[Pasted image 20231214151004.png]]
In diesem Stück sieht man das eine Datei mit dem Namen `streng-geheim.pdf`übertragen wurde.
![[Pasted image 20231214151041.png]]
![[Pasted image 20231214151111.png]]
Das Passwort fand sich in einem UDP Stream.
![[Pasted image 20231214150842.png]]
Da mich das Speichern des PDFs in ASCII Codierung nicht weiterbrachte habe ich den Stream noch mal im RAW Format gespeichert. Diese Datei lies sich dann mit dem Passwort entpacken und Anzeigen.
![[Pasted image 20231214171157.png]]
![[Pasted image 20231214171111.png]]