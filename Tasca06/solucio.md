# Accés remot. Escriptori remot (RDP)

## Connexió remota de Linux a Windows

Primer farem dues màquines virtuals, una Zorin OS i una altra amb Windows 11, amb dos adaptadors cada una, el primer amb NAT i l’altre amb només amfitrió.

A la màquina windows activarem l’accés a l'escriptori remot:

![cap1](/Tasca06/img/cap1.png)

Un cop activat entrarem a la tercera opció, la d’usuaris d’escriptori remot, i aqui assignarem i li donarem permisos als usuaris amb els que podem fer la connexió. Llavors aquí afegirem el nom que tenim en la màquina del Windows i en la del Zorin.

![cap2](/Tasca06/img/cap2.png)

Un cop tinguem l’usuari agregat, desde la màquina Zorin entrarem a l'aplicació Remmina, que és una aplicació que normalment ve per defecte en els Sistemes Operatius de Linux i és com una mena d’accés remot pero de Linux.

![cap3](/Tasca06/img/cap3.png)

Aquí ens donarà informació sobre un certificat, al qual li donarem a que si, ja que si no no podrem fer la connexió.

![cap4](/Tasca06/img/cap4.png)

Un cop li donem a si, en la pantalla que ens surt, haurem de posar l’usuari i la contrasenya de el nostre usuari de Windows.

![cap5](/Tasca06/img/cap5.png)

Un cop haguem posat lo anterior ja se'ns farà la connexió directa a Windows i podrem tenir el control del client.

![cap6](/Tasca06/img/cap6.png)

## Connexió remota de Windows a Linux

Ara farem el mateix però de manera contraria, ens conectarem de Windows a Zorin.

El primer que farem serà entrar a configuració i activar el control remot:

![cap7](/Tasca06/img/cap7.png)

Un cop tenim les opcions activades anirem al windows i entrarem a connexió d’escriptori remot, que posarem el nom d’usuari que tenim a la de Zorin:

![cap8](/Tasca06/img/cap8.png)

Una vegada li donem a connectar, ens demana un usuari i contrasenya, que posarem el de zorin:

![cap9](/Tasca06/img/cap9.png)

Aquí ens surt com una alerta, però que en el nostre cas li donarem a que si:

![cap10](/Tasca06/img/cap10.png)

I un cop fet això ja estarem connectats a la màquina de Zorin.

![cap11](/Tasca06/img/cap11.png)

## Conclusió

La realització d’aquesta activitat m’ha permès comprendre de manera pràctica el funcionament de les connexions d’escriptori remot entre sistemes operatius diferents, així com els requisits de configuració específics per a Windows i Linux. Considero que ha estat una tasca útil, ja que no només he après a habilitar i gestionar aquestes connexions, sinó també a identificar possibles problemes de xarxa i a assegurar una comunicació correcta entre màquines.

Personalment, opino que aquesta experiència és molt valuosa perquè reflecteix situacions reals d’entorns professionals, on sovint cal administrar equips remotament i combinar diferents plataformes. Haver pogut provar el procés pas a pas m’ha ajudat a entendre millor la importància de la configuració adequada, la seguretat i la verificació contínua del sistema. En general, considero que l’activitat ha estat enriquidora i m’ha aportat coneixements pràctics que podré aplicar en futurs projectes tècnics.
