# PracticaEmpaquetar

## M5-UF1-Ra2-Empaquetar_aplicacions_Java_TOTS ##

**1 CREAR APLICACIONS AMB JAR**

_1. Crea un JAR amb una aplicació que ens mostri ```“Hola món!”```, explica clarament com i quines instruccions has fet anar per crear-lo._

![foto1](/fotos/foto1.png)
>Crearem un arxiu amb extensió java.

_2. Executa el JAR, i mostra el seu resultat._

![foto2](/fotos/foto2.png)
>El resultat final de la pràctica es té que sembla amb això.

**2 INCLOURE JAR'S A LA MEVA APLICACIÓ**

_1. Descarrega't el JAR **DAWUtils.jar**, l'API d'aquest JAR i l'exemple **ProvaUtils.java**._

![foto3](/fotos/foto3.png)
>Aquest arxiu serà el que executa i fa que es reflecteixi les acciono estipulades pel codi.

_2. Crea el teu propi package i actualitza el fitxer **ProvaUtils.java** de forma que estigui dins d'aquest._

![foto8](/fotos/foto8.png)
>El resultat té que sembla'n al que es veu a la fotografia.

_3. Intenta executar ProvaUtils. Cal fer-ho de tres formes diferents:_

  _1. Fes ús de l'opció ```-classpath```_

>Al moment de fer la compilació del codi li posa la ruta amb de quina classe volem que s'apliqui i on es troba aquestes ```java -classpath "/ruta/directorio" Hello```.

  _2. Posa el JAR en el teu ```CLASSPATH```_

>Al moment de fer la compilació del codi li posa la ruta amb de quina classe volem que s'apliqui i on es troba aquestes.

  _3. Inclou el JAR dins el teu **MANIFEST.MF**_

>En crear un arxiu on deixes estipulats simplement sol te que el llegeix a l'hora de capil·lar.

```Manifest-Version: 1.0```

```Created-By: 1.5.0_06 (BEA Systems, Inc.)```

```Main-Class: pepelu.HolaPepelu```

```Class-Path: UtilitatsMeves.jar UtilitatsNoMeves.jar```

_4. Quina de les tres opcions anteriors trobes millor?_

>De les 3 maneres que es pot fer és més recomanada com la més utilitzada és la de l'arxiu "MANIFEST.MF" pel motiu amb un sol lloc tens estipulat on estan les coses i simplificada la comanda.

_5. Detalla tot comentant el codi que fa en general el programa i en concret cada línia, el programa **ProvaUtils.java** ._

>Tot el comenta anteriorment.
