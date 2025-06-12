Bei Verwendung von texstudio muss ein eigener Befehler definiert werden, um die Nomenklatur zu erstellen. Dazu folgende Anweisungen befolgen:

1. Reiter 'Options' �ffnen
2. 'configure TeXstudio...' anklicken
3. Reiter 'Build' �ffnen
4. In der Mitte auf 'Add' klicken
5. Namen des Befehls w�hlen, z.B. 'Make Nomenclature'    (siehe HowTo_Make_Nomenclature.png)
6. In das Feld rechts daneben 'makeindex -s nomencl.ist -t %.nlg -o %.nls %.nlo' eingeben
7. Ein neuer Befehl ist jetzt verf�gbar, der �ber 'Tools' -> 'User' -> 'Make Nomenclature' ausf�hrbar ist. Damit wird das .nls- und das .nlo-file 
   erzeugt. Diese werden f�r die Nomenklatur im .tex-file ben�tigt. 
8. Eine �nderung der Nomenklatur wird erst dann �bernommen, wenn der Befehl 'Make Nomenclature' ausgef�hrt wurde.

Neben der .nlo- und .nls-Datei werden durch das Kompilieren der .tex-Datei noch die .aux-, .lof-, .log-, .lot-, .nlg-, .soc-, .synctex.gz-, & die .toc-Datei erstellt.

 

