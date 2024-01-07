---
tags:
  - ZIP
  - fcrackzip
  - CaesarCipher
  - PasswortSchutz
---
# Zipped
<h2>Aufgabe:</h2>
<img width="351" alt="image" src="https://github.com/Pegasus01123/fernuni_hacken/assets/72656695/b11d1629-16fe-4578-b71d-4b6f19b28edb">

<h2>Meine Lösung:</h2>

Ein Passwort geschütztes Zip File.

Nachkurzem Googeln bin ich auf ein Writeup gestoßen in dem die Verwendung von __fcrackzip__
gezeigt wurde.

Mit `fcrackzip -b -D -p /usr/share/wordlists/rockyou.txt -u flag.zip` war das Passwort "Divabeer1" schnell gefunden und das Textdokument entsperrt.
Der Inhalt von flag.txt war 

mshn{w4zZd0yK_jy4Jr3k!}


Mit dem zweiten Tipp habe ich die Info bekommen das es sich um eine Caesar Cipher handelt.
Bei www.dcode.fr/caesar-cipher habe ich die Flag bekommen.

Flag:flag{p4sSw0rD_cr4Ck3d!}
