# Pr2 B2 Semesterspiel Uno

**Was hat unser Team in Pr 2 bei DOP dieses Semester gemacht?**

Wir haben uns im Sinne unserer Studienleistung mit der Programmierung eines Uno Spiels als Team beschäftigt.
Zusätzlich mussten wir in Eigenleistung Lehrvideos zum gegebenen Vorlesungsthemen selbst drehen.

**Wer gehörte zu unserem Team?**

Wir waren David Silva Goncalves, Tristan Gräble, Johannes Kramberg und Katharina Korst


## Semesterspiel UNO
Die Programmierung des Uno Spiels wurden in folgende drei Teile aufgeteilt:


**Teil 1:**

Der erste Teil bestand aus dem groben Konzept der verschiedenen Klassen, in die wir nach und nach die Spiellogik implementierten. 
Dieses beinhaltete das Testgetriebene entwickeln unter der Benutzung von JUnits und die Verwendung des eigenen Exception Handlings. 
Auch war es sehr wichtig alles detailliert mit Java Docs zu dokumentieren.
Im Laufe der Zeit hatten wir nicht nur ein grobes Konzept des Regeln, sondern es kamen Spieler hinzu durch die unser Projekt langsam spielbar wurde.

Hier ist ein Beispiel unseres aktuellen Package-Explores, welcher seit Beginn die gleiche Struktur aufweist, bis auf die Ki- und Gui-Komponenten, die erst im weiteren Verlauf des Semesters dazu kamen.

![Package Explorer](https://user-images.githubusercontent.com/72968168/123871821-7e92aa80-d934-11eb-8ca2-76fca07132ad.jpg)


Hier ein Beispiel unserer Spiel-CLI:

![Spiel-CLI](https://user-images.githubusercontent.com/72968168/123871826-82263180-d934-11eb-8da4-07d0edab8933.jpg)



**Teil 2:**

In diesem Abschnitt wurde ein großer Fokus auf das Implementieren von KI´s, dem Speichern und der Verwendung von Interfaces gesetzt.
Deshalb setzte sich ein Teil unseres Teams daran die Spiellogik nun auch für zwei verschiedene KI´s umzusetzen. 
Einmal eine offensive KI und eine defensive KI.

![KI](https://user-images.githubusercontent.com/72968168/123871832-85212200-d934-11eb-9883-0343ff721000.jpg)


Der andere Teil des Teams beschäftigte sich während dessen mit dem Laden und Speichern
im CSV und Serialisierten Format beschäftigte.
Somit nahm das ganzes schon sehr stark Gestalt an und konnte nun sogar gespeichert werden.

![speichern](https://user-images.githubusercontent.com/72968168/123871842-86eae580-d934-11eb-932c-9300d32a64b4.jpg)



**Teil 3:**

Im letzten Abschnitt durften wir nun das ganze in ein Graphical User Interface einbetten. Zudem kamen auch Themen des Multi Threading der KI hinzu. 
Also bekamen unsere KI´s beim Instanziiren noch jeweils einen eigenen Thread und konnten nun unabhängig vom Main Thread existieren.
Des weiteren brauchten wir noch die Möglichkeit jeden Spielzug nachzuvollziehen. Deshalb bekam unser Programm noch einen selbst erstellten Logger hinzu.

Hier ein Beispiel unseres Hauptmenüs:
![Uno-Hauptmenue GUI](https://user-images.githubusercontent.com/72968168/123870003-04f9bd00-d932-11eb-97c9-b0a6f705d1d6.jpg)



## Individuelle Leistung - Lehrvideos

Jeder von uns musste insgesammt vier Videos zu einem zugeteilten Inhalt drehen. Der Inhalt war immer Teil des Vorlesungsstoffs, den wir aufgriefen und diesen 
zusätzlich noch mit eigenen Beispielen untermalten. Dabei war es sehr wichtig "nichts nachzuplappern".
Somit musste man in Eigenleistung beweisen, den Vorlesungsstoff außerhalb des Semesterspiels zu beherrschen.



**David Silva Goncales**


**1.Video Objekt-Eigenschaften-Getter-Setter-Konstruktoren**

![Screenshot Video 1](https://user-images.githubusercontent.com/74213338/123827645-170f3780-d901-11eb-9c52-e472ee2a8ab7.JPG)

Dieses Video dreht sich stark um die Grundlagen der Objektorientierten Programmierung. Zuerst wird gezeigt wie Objekte mit Ihren Eigenschaften und Attributen angelegt werden können, sowie die Rolle des Konstruktors dabei. 
Des Weiteren werden die Getter und Setter Hilfsmethoden anhand des Quellcodes erklärt.

**2.Video Versionsverwaltung-zentral-verteilt-GIT. Die typischen GIT-Funktionen sind dabei ausgehend von einem leeren Eclipse-Projekt live im Video zu zeigen.**

![Screenshot Video 2](https://user-images.githubusercontent.com/74213338/123827658-1a0a2800-d901-11eb-8555-48ab11ef85da.JPG)

Das zweite Video handelt von Versionsverwaltungssystemen, insbesondere um Git. Es zeigt welche Funktion es bietet, um als Team am Quellcode zu arbeiten.
In diesem Video wurde auch ein Merge Konflikt gelöst. Dieses Video finden Sie auch auf dem Youtube Kanal von Herrn Prof. Frank Dopatka  [Versionsverwaltungssysteme und GIT mit Java in Eclipse](https://www.youtube.com/watch?v=DZAdtgJMw6g&ab_channel=FrankDopatka).


**3.Video Steuerelemente und Ereignisse in Swing**

![Screenshot Video 3](https://user-images.githubusercontent.com/74213338/123827673-1d9daf00-d901-11eb-8abc-acc3b0598d82.JPG)

Im dritten Video habe ich die wichtigsten Steuerelemente der Swing-Gui vorgestellt und die Behandlung von Ereignissen dargestellt, bezogen auf das klick Event. 
Mein Beispiel in diesem Video war eine abstrakte Darstellung einer Pizza Bestellung. 


**4.Video Collections: Comparator, Iterator, Map, Properties, Wildcards**

![Screenshot Video 4](https://user-images.githubusercontent.com/74213338/123989230-fe6a5480-d9c8-11eb-9c4a-a7a8850cf1cb.JPG)


In Video 4 habe ich anhand einer TreeMap die Funktionen des Compareable interface gezeigt, sowie die Funktionen eines Iterators.
Dies wurde durch ein Beispiel der Europa-Meisterschaft realsiert. Abgesondert davon bin ich auf die Wildcars und Properties
eingegangen und welche Funktion diese 2 Konzepte bieten. 



**Tristan Gräble**


**1.Video Anweisungen-Datentypen-Operatoren-Konstanten sowie UML-Aktivitätsdiagramm-Verzweigungen-if-else-switch**

![Screenshot-Video-1a](https://user-images.githubusercontent.com/72968168/123862822-1db1a500-d929-11eb-8235-0f948134b3f4.jpg)

In Video 1 habe ich Primitive Datentypen und Referenztypen vorgestellt und verglichen. Zusätzlich habe ich arithmetische-, Bit- und Vergleichs Operatoren anhand Beispielen gezeigt. Desweiteren bin ich auf das Konvertieren von Datentypen im automatischen, sowie im manuellen Type-Cast eingegangen. Der zweite Teil des Videos handelte von den Grundlagen der UML mit Beispiel eines Aktivitätsdiagramm mit Verzweigungen. Auf diese Verzweigungen bin ich daraufhin gesondert in Java eingegangen, sodass ich anhand Beispielen if, else und switch zeigen konnte.


**2.Video Exception-Handling-Strukturierung**

![Screenshot-Video-1b](https://user-images.githubusercontent.com/72968168/123865505-45eed300-d92c-11eb-8119-ebc735cf2588.jpg)

Im zweiten Video habe ich mich mit Exception-Handling und der Strukturierung größere Software Projekte befasst. Hierzu habe ich zunächst Exception selbst erklärt und dessen Vererbungshierarchie gezeigt. Im weiteren Verlauf des Videos habe ich anhand eines des Altersnachweises Try und Catch von Exceptions gezeigt. Daraufhin habe ich Java-Konstrukte zur Strukturierung von Objekten erläutert.


**3.Video Definition von Interfaces, deren Implementierung und Verwendung**

![Screenshot-Video-AB2](https://user-images.githubusercontent.com/72968168/123866353-3e7bf980-d92d-11eb-82b7-5b1b4ae938bc.jpg)

In Video drei bin ich auf Interfaces in Java eingegangen. Dazu habe ich anhand eines Modells erst das Prinzip eines Interfaces erklärt. Anschließend mit einem Beispiel einer DrachenKlasse und eines DrachenInterfaces dies in Eclipse gezeigt.


**4.Video funktionale Programmierung: Paradigmen, Funktional, Lambda, Closure**

![Screenshot-Video-AB3](https://user-images.githubusercontent.com/72968168/123867003-12ad4380-d92e-11eb-9db9-203b15004d07.jpg)

In meinem letzten Video habe ich Programmier Paradigmen erklärt und bin vor allem auf die Funktionale Programmierung eingegangen. Im zweiten Teil des Videos zeige ich Schlüsselwörter der Funktionalen Programmierung, wie Function, UnaryOperator, Consumer und Supplier. Daraufhin stellte ich ein Beispiel von Lambda vor und dessen Code-Reduzierung, sowie ein Beispiel zu Closure.



**Johannes Kramberg**


**1: Wiederholung: Objekt, Eigenschaften, Getter, Setter, Konstruktoren in Java**

![iExpo1](https://user-images.githubusercontent.com/72856593/123963933-38306080-d9b3-11eb-8c63-959f884af12e.png)

In diesem Video habe ich Objekte im Zusammenhang mit deren Eigenschaften gezeigt. Dies habe ich am Beispiel eines Menschen genauer erläutert.
Da jeder Mensch einen Vor- & Nachnamen besitzt konnte ich diese dem Menschenobjekt zuweisen & diese im Konstruktor, also der Geburt eines Menschen setzen.
Um das Thema abschließend zu beenden, bin ich noch auf Konstruktor-Vererbungshierarchien eingegangen und habe gezeigt wie man mit Hilfe von Getter()-Methoden auf die Eigenschaften des Objektes von außen zugreift und diesen mit Hilfe von Setter()-Methoden neue Werte zuweisen kann.


**2: fortgeschrittene Programmierung: Komplexität, O-Notation, P und NP**

![iExpo2](https://user-images.githubusercontent.com/72856593/123964144-7168d080-d9b3-11eb-8b5c-b24378055c3b.png)

Bei diesem zweiten Video habe ich mich mit dem Thema Komplexität hauptsächlich theoretisch beschäftigt. Dabei bin ich zuerst auf die Komplexitättheorie eingegangen, worum sich diese handelt und wozu man diese benötigt.
Damit die Komplexität anhand der sogenannten O-Notation vorgestellt. Dafür verwendete ich eine Veranschaulichung mit einem Graphen um den Unterschied zwischen P(in polynomialzeit lösbare Probleme) und NP(nichtdeterministisch in polynomialzeit lösbare Probleme) hervorzubringen. Hierzu habe ich die e-Funktion in Vergleich mit einer quadratischen Funktion gesetzt.
Desweiteren bin ich noch auf Laufzeitunterschiede eingegangen und habe zum Schluss noch den Dijkstra-Algorithmus(P) und das TravellingSalesmanProblem(NP) verglichen, da diese relativ ähnlich zueinander sind, jedoch verschiedene Komplexitätsklassen annehmen. Hierbei habe ich den Dijkstra-Algorithmus auch ausführlich vorgestellt.


**3: fortgeschrittene Programmierung: Innere Klassen**

![iExpo3](https://user-images.githubusercontent.com/72856593/123964301-91988f80-d9b3-11eb-96c0-2ffdf5cb38df.png)

Das 3. Video war im Vergleich zu den vorherigen ein etwas kürzeres Video. Dort habe ich die 4 verschiedenen Typen von inneren Klassen vorgestellt. 
Ich habe angefangen mit statischen inneren Klassen, bin dann weiter zu Mitglieds-/Elementklassen. Weiter ging es dann mit lokalen inneren Klassen und zum Schluss bin ich noch auf anonyme innere Klassen eingegangen.
Diese verschiedenen Arten habe ich dann versucht, vereinfacht mit Beispielen darzustellen.


**4: Datenstrukturen und Collections: Graphen, Dijkstra, Färbung**

![iExpo4](https://user-images.githubusercontent.com/72856593/123964389-a412c900-d9b3-11eb-993b-2521d3994992.png)

In diesem letzten Video habe ich die Theorie hinter Graphen angesprochen und anschließend gezeigt wie man solche in Quellcode darstellt. Im Anschluss habe ich dann den bereits geschriebenen Code verwendet um davon weitere Klassen abzuleiten und damit den Dijkstra-Algorithmus zu coden. Dessen Funktionsweise habe ich parallel dazu auch noch beschrieben.
Zum Abschluss bin ich dann noch auf die Theorie der Graphenfärbung eingegangen und diese anhand eines praktischen Beispiels abgebildet.



**Katharina Korst**

**1. Video Schleifen-for-each-do-while-Arrays sowie Funktion-Methode-Rekursion-fehlerhafte-Daten**

![Video_1](https://user-images.githubusercontent.com/72854140/123826884-7587e600-d900-11eb-857b-9d767160caf8.jpg)
   
In diesem Video bin ich zunächst auf die Funktionsweise der zwei Sortieralgorithmen Bubblesort und Quicksort 
anhand einer bildlichen Darstellung eingegangen. Im weiteren Verlauf habe ich beide in Eclipse programmiert 
und nebenbei die Funktionsweise erklärt.
Um das ganze besser nachvollziebar zu machen verwendete ich unsortierte Listen und wendete beide
Algorithmen darauf an.

 
**2. Video Bubblesort und Quicksort sind dabei jeweils ausgehend von einem leeren Eclipse-Projekt live im Video zu entwickeln**

![Video_1b](https://user-images.githubusercontent.com/72854140/123826921-7caef400-d900-11eb-8d44-f2b8069afef8.jpg)

In diesem Video bin ich zunächst auf die Funktionsweise der zwei Sortieralgorithmen Bubblesort und Quicksort 
anhand einer bildlichen Darstellung eingegangen. Im weiteren Verlauf habe ich beide in Eclipse programmiert 
und nebenbei die Funktionsweise erklärt.
Um das ganze besser nachvollziebar zu machen verwendete ich unsortierte Listen und wendete beide
Algorithmen darauf an.


**3. Eingabe, Ausgabe, Ströme und Dateien**

![Video_2](https://user-images.githubusercontent.com/72854140/123826947-820c3e80-d900-11eb-980c-039b292cbc04.jpg)

Im dritten Video lag mein Schwerpunkt auf der Speicherung im CSV und Serialisierten Format. Dabei bin
ich zunächst auf die Grobe Funktionsweise der Input und Output Streams eingegangen.
Im zweiten Schritt habe ich dann jeweils eine Klasse zur Speicherung und Ladung für Dateien
im CSV- und Serialisiertem-Format implementiert. Über dies konnte man den gesammten Stand
eines Projektes Speichern und später wieder im gleichen Zustand laden.


**4. Datenstrukturen: Binärbaum, Tree, Trie**

![Video_3](https://user-images.githubusercontent.com/72854140/123826976-88021f80-d900-11eb-8da6-5ca5b25bf6c5.jpg)

Im letzen Video Block bekam ich das Thema der Trees und Tries. 
Auch hier bin ich zunächst auf die Funktionsweise und Datenstruktur beider eingegangen, um dann
im Nachgang einen Trie zu programmieren.
Auch habe ich diesen anhand eines groben Beispiels angewendet, wodurch das ganze besser verständlich
gemacht werden sollte.


