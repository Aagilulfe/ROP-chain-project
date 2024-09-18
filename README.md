# Use after free exploit - CVE-2009-1328 - Mini-StreamRM-MP3 Converter 3.1.2.1

> Ce proof of concept a été créé dans un but purement pédagogique.

Pour créer l'exploit, il suffit de lancer le script python "exploit_alpha.py".

Un fichier .m3u est généré dans le même répertoire.

Lancer l'application Mini-Stream RM-MP3 Converter:
Ouvrir le fichier .m3u     OU     Glisser-déposer le fichier sur l'appli

La calculette devrait se lancer.


Compilation du shellcode:
nasm w32-exec-calc-shellcode.asm -o w32-exec-calc-shellcode.bin


Si nécessaire, un installeur de l'application vulnérable est disponible dans le dossier Application_cible.
