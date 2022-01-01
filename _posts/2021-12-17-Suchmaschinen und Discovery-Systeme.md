---
title: "Tag 8: Am Ende wird alles eins."
date: 2021-12-17
---

Die 8. Vorlesung hatte das Thema **Suchmaschinen und Discovery-Systeme**. Wir hatten das zweitletzte Mal Unterricht und es wurde noch **das Thema «Metadaten modellieren und Schnittstellen nutzen» beendet**. Danach lag der Schwerpunkt auf dem Herzstück des Moduls; das **Zusammenführen von Metadaten in ein Discoverysystem**. Achtung; der Beitrag ist lang.

**Um was gings:**
Das Thema «Metadaten modellieren» wurde dieses Mal abgeschlossen. Wir haben gelernt, dass es schon Alternativen zu OpenRefine gibt, dass aber OpenRefine einzigartig durch die grafische Oberfläche sei. Mit dieser ist die Transformation gegenüber anderen Tools besser nachvollziehbar. Catmandu und Metafucture sind Alternativen zu OpenRefine. Man sollte sich bei der Auswahl eines Programmes nicht immer nur an die Evaluationen halten, sondern eine gute Auswahl hängt auch immer vom eigenen Vorwissen ab. Manchmal hat man beispielsweise schon gute Erfahrung mit einer Software gemacht, dann lohnt es sich nicht, ein neues Programm zu testen, nur weil es in einem Vergleich besser abschneidet. Zudem muss man sich im Klaren sein, für welche Funktionen man eine Software benötigt. Nach diesen Spezifikationen gings los mit dem Thema «Suchmaschinen und Discovery Systeme».

Solr <br>
Solr ist mir völlig unbekannt. Die «open-source enterprise-search platform, written in Java» wird beispielsweise auch bei Netflix (bei der Suche) verwendet, besteht also nicht nur im Bibliothekskontext. Solr ist die führende Open Source Installation für Discovery-Systeme und man kann es ein bisschen wie der Motor eines Onlinekatalogs anschauen. VuFind ist in dieser Metapher dann der schnittige Sportwagen, welchen man als Autoenthusiast sehen und bewundern kann. Solr, bzw. der Motor bringt das Ganze aber zum Laufen. Eine Alternative zu Solr wäre beispielsweise «elasticsearch». Diese ist stärker in visueller Darstellung. 
Solr selbst ist ausgestattet mit einer eigenen Suchoberfläche, diese ist aber nicht für Nutzende als Rechercheoberfläche geeignet. Sie wird nur für interne Recherchen verwendet (beispielsweise von den Admins).<br>



Solr = Suchindex und <br>
SQL = Datenbank<br>

 ![solrsql](https://user-images.githubusercontent.com/91015615/147853376-c3583aa9-fdf8-4fcf-acf9-378b5b267447.png)
 
Solr ist ziemlich flach aufgebaut, was es schneller und besser durchsuchbar macht. Flach bedeutet, dass die Daten eine Art Liste von Feldern mit dazugehörigen Werten darstellen. Bei SQL kann man Daten dafür möglichst effizient ablegen (arbeitet mit Verknüpfungen -> relationale Datenbank)<br>
Solr ist «intelligenter» (durch lexikalische Suche) -> kann in Anfragen auch interpretieren, Verben können auf Grundform zurückgeführt werden, während bei SQL alles wortwörtlich sein muss. SQL vergleicht einfach die Werte der Anfrage mit den hinterlegten Werten. Solr kann da Werte auch interpretieren.
Nach diesem sehr theoretischen und technischen Input haben wir Solr mal genauer angeschaut und haben ins Dashboard gewechselt.
<img width="533" alt="solradminisbn" src="https://user-images.githubusercontent.com/91015615/147853413-a6bfd320-87eb-40ee-96c8-b9363483ba63.PNG">

Hier sind lauter technische Angaben ersichtlich (Version, Startdatum). Solr arbeitet mit Core-Indizes, in welchen man Konfigurationen für einzelne Felder sieht (Biblio ->> was für Parameter hat man z.B. für ISBN erstellt). Auch findet man in diesem Dashboard die Suchfunktion in Solr. Dazu haben wir eine Übung gemacht;

<br>
Es galt, die Suchergebnisse in Solr, der Shell und VuFind zu vergleichen. Wir haben folgende Unterschiede entdecken können:<br>
 •	Gleich viele Treffer<br> 
 •	VuFind hat klassische OPAC-Ansicht, Solr Metadaten-Ansicht (Vermutung JSON?)<br>
 •	Bei Vufind muss für Detailangaben noch auf das entsprechende Exemplar geklickt werden, bei Solr sind diese bereits angezeigt -> FuFind «filtert» schon unwichtige Angaben für Nutzende weg<br>
 •	Verlinkungen sind im VuFind mit Hyperlink direkt anklickbar, im Solr ist nur Link hinterlegt, kann aber nicht angeklickt werden<br>
 •	Im Terminal werden die gleichen Treffer angezeigt wie im Solr Admin, aber schlecht leserlich<br>

Wichtig erscheint mir, dass man im Terminal (im Unterschied zu VuFind) herauslesen kann, wie die Felder geratet werden. Das war sehr spannend, hier einen Einblick in das Thema Rating zu erhalten!<br>
 <img width="455" alt="ranking_solr" src="https://user-images.githubusercontent.com/91015615/147853399-6fa29ff5-d937-4ff6-abb4-e9dca26ef0d7.PNG">


VuFind<br>
VuFind ist quasi die Oberfläche für die Interaktion mit den Anwendern. Eine Alternative zu VuFind ist beispielsweise Primo, welches mir natürlich sehr gut bekannt ist und ich durch mein neues Amt in der AG swisscovery auch näher kennenlernen werde. VuFind ist weit verbreitet und die Organisation «Open Library Foundation» fördert und finanziert es. Einige Beispiele für VuFind Systeme ist der Katalog der UB Leipzig oder Swisscollections.

Nun haben wir zu vielen Systemen unterschiedlichste Informationen erhalten und konnten bereits viel anwenden. Nun galt es aber, all die einzelnen Aspekte zusammenzuführen und das Herzstück dieses Moduls zu schaffen; ein Discoverysystem mit unterschiedlichsten Daten aus unterschiedlichsten Programmen zu schaffen! Mein eigener Katalog.

Ziel ist jetzt; dass die Daten welche in Koha, Dspace, Archivesspace und Openrefine als MARC-Daten geholt wurden, zu importieren und quasi alles «Gelernte» des Semesters in VuFind zu packen.
Es müssen nun zuerst die Testdaten in VuFind wieder gelöscht werden und dann die «richtigen», während des Semesters angesammelten Daten importiert werden. 
Da ich während der Vorlesung unterwegs war, habe ich nicht auf meine eigenen Daten zurückgegriffen, sondern die Beispieldaten verwendet. Das ganze Prozedere hat einwandfrei geklappt und ich habe meine eigenes Discoverysystem! 
<img width="519" alt="importinVUfindgeklappt" src="https://user-images.githubusercontent.com/91015615/147853387-9b5897f2-d667-49a6-a49b-da491cc306cc.PNG">

Somit sind wir dann auch schon am Ende des Schaubilds aus der ersten Einheit angekommen 😊

Was haben wir nun alles gemacht:<br>
Koha und Archivesspace selber installiert und für Dspace haben wir eine Demo verwendet<br>
-> dort haben wir dann via OAI-PMH Schnittstelle und mit dem Harvester Daten rausgezogen <br>
-> mit MARCedit wurden dann die verschiedenen Formate aus den verschiedenen Systemen vereinheitlicht<br>
-> all die Daten haben wir dann mit einem Import-Script von VuFind in Solr, beziehungsweise VuFind geladen<br>

![bild1](https://user-images.githubusercontent.com/91015615/147853497-dac2592d-df78-4a34-af01-2b309a82def1.png)

Das Ganze war also eigentlich überhaupt keine Hexerei! Sehr geholfen haben jeweils die Tutorials der beiden Dozenten und das Bereitstellen der Shell-Befehle. Danke dafür.


**Was habe ich neu gelernt (oder wieder neu entdeckt):**
-	Reconcilation -> Datenanreicherung ist wichtigste Funktion von OpenRefine
-	XML ist im Bibliothekskontext noch sehr oft in Benutzung, wenn man aber im weiteren Webkontext denkt, dann ist JSON DAS Austauschformat
-	Bei Primo ist auch Solr im Hintergrund

**Was habe ich (noch) nicht verstanden**
