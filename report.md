# Report dels programes
### Per Èric Fuentes

## Exercici 1:

Aquí podem veure com la compilació del programa funciona correctament, i mostra el text tal com demana l'enunciat.
Hem assignat variables amb els valors d'entrada i els hem mostrat a consola.

![exercici 1](/img/ex1.png)

## Exercici 2:

Aquí es veu la compilació del programa, on mostra l'adreça, que són variables agrupades en un WriteLine.

![exercici 2](/img/ex2.png)

## Exercici 3:

Aquí surt la compilació del programa, on es pot veure que a l'output apareix un text juntament amb la variable. Diferents tipus, com **string**, **double** i **bool**. (Utilitzo double en comptes de float perquè és més còmode per mi, i encara no fem programes on la memòria sigui tan necessària.)
Per a mostrar el bool en text, utilitzo ```(variable: "si és true" : "si és false")```.

![exercici 3](/img/ex3.png)

## Exercici 4:

Aquí es veu la compilació del programa, que converteix els euros en pessetes. El que fem és agafar un valor amb decimal d'euros (per als cèntims) (llegim l'entrada i la convertim en double), i ho multipliquem perquè sigui en pessetes.
Dins del WriteLine utilitzo ```{pessetes:F0}``` perquè sigui sense decimals arrodonit.

![exercici 4](/img/ex4.png)

## Exercici 5:

En aquesta captura es visualitza la compilació del programa, on es veu que demana el nom i l'any de naixement. El que he fet és que amb un ReadLine, llegim els valors, l'any el passem a int, i després a l'output del WriteLine hem restat l'any actual amb l'any de l'input.

![exercici 5](/img/ex5.png)

## Exercici 6:

En aquest programa el que fem és una simple multiplicació. Demanem una entrada del número d'un costat d'un quadrat, i a partir d'això multipliquem per 4 per aconseguir el resultat. Es pot veure el resultat a la captura.

![exercici 6](/img/ex6.png)

## Exercici 7:

En aquest programa tenim ja diferents notes afegides a variables, i el que fem és agafar les tres, sumar-les i dividir-les pel número que hi ha. Després ja diem quina és la mitjana de les tres. (No arrodoneixo la mitjana.)

![exercici 7](/img/ex7.png)

## Exercici 8:

En aquest programa el que farem serà agafar un valor int de l'usuari. Primer dividirem l'entrada per 60, per saber les hores. Mentre que després utilitzarem el mòdul (%) de 60 per saber els minuts (és el residu).
Aquí es pot veure el resultat: 62 minuts són 1 hora i 2 minuts.

![exercici 8](/img/ex8.png)

## Exercici 9:

A la comanda es pot veure el resultat del programa, converteix metres en peus. Aquest programa és una simple multiplicació (per 3.28084). I ho mostra en consola.

![exercici 9](/img/ex9.png)

## Exercici 10:

Aquest programa és encara més bàsic que els altres. Podem veure com demana dues entrades i aquestes es junten sense espais, formant una "contrasenya". A la captura està l'execució.

![exercici 10](/img/ex10.png)

## Exercici 11:

En aquesta captura es pot veure com ingressem dues entrades string i el programa ens retorna una adreça de correu electrònic. Aquesta adreça és generada ja que ajunta les dues variables amb un @ enmig.

![exercici 11](/img/ex11.png)

## Exercici 12:

En aquesta captura podem veure el resultat de l'exercici 12, en el qual el que hem fet ha sigut agafar dos números de l'usuari i fer diferents operacions, com la suma, resta, multiplicació i divisió. Ho he fet tot en un mateix WriteLine separant per ```\n```.

![exercici 12](/img/ex12.png)

## Exercici 13:

Aquest programa ja ha començat a ser una mica més difícil. El que fem és un Insert a l'string que ens ha passat l'usuari, insert a posició 2 i 5 (ja que com hem afegit un, en comptes de 4 és 5). I ho mostrem en terminal.

![exercici 13](/img/ex13.png)

## Exercici 14:

Aquest exercici l'he fet amb un valor fix, no un nom que l'usuari afegeixi.
El que fa el codi és que primer detecta el caràcter en posició 0 de la variable, després el que fa és veure el caràcter del length / 2 - 1 per saber el del mig, i per últim el mateix però sense dividir per 2, per saber l'últim. Fem el - 1 ja que [] comença per 0, mentre que el Length comença per 1.

![exercici 14](/img/ex14.png)

## Exercici 15:

Aquest programa també l'he fet amb valors fixos. El que fa és seleccionar el primer caràcter del nom / cognom, i fa un ToUpper, després amb Substring afegeix el que falta a partir de la segona posició, perquè la primera sigui majúscula i les altres minúscules.

![exercici 15](/img/ex15.png)

## Exercici 16:

En aquest programa el que fem és calcular la mitjana d'un tema per percentatge. És un petit càlcul per assignar pes als valors entrats per l'usuari, i després el resultat es mostra.

![exercici 16](/img/ex16.png)

## Exercici 17:

Aquest programa, com es pot veure, separa els decimals del número enter. Això ho he aconseguit truncant el valor i restant-lo, quedant-me només amb el número "meravellós" (també l'he arrodonit a 2 decimals).

![exercici 17](/img/ex17.png)

## Exercici 18:

Aquest programa també ha utilitzat mòdul (%), ja que el que he fet és que en ingressar una hora i les hores a incrementar, es sumessin i amb mòdul de 24, poder saber quines són les restants.

![exercici 18](/img/ex18.png)

## Exercici 19:

Aquest programa és molt fàcil. Com podem veure, imprimeix en consola la longitud en caràcters d'una paraula. Per fer això només hem de fer un Length i imprimir-ho.

![exercici 19](/img/ex19.png)

## Exercici 20:

En aquesta captura es pot veure el resultat de l'últim exercici. Consisteix en invertir un número de 3 xifres. Jo el que he fet és mantenir-lo com a string i posar la posició 0 com la 2, i la 2 com la 0, i un cop fet, convertir-ho a int i imprimir.

![exercici 20](/img/ex20.png)