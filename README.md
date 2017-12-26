# MITM-attack-and-defense-
Firstly, we worked on devising the attack in a LAN, using an open-source tool called SSLStrip.
We modified the code of SSLStrip to bypass HSTS, a security protection mechanism, to prove that HSTS is not safe from MITM attacks.
Later, a defense methodology was constructed using JavaScript on the server machine, which checks and ensures that connections are secure using HTTPS.
This code is protected from evesdropping using obfuscation methodology.
