---
title: "Tag 5: Metadaten und Schnittstellen, Teil 1"
date: 2021-12-05
---

Die 6. Vorlesung hatte das Thema **Metadaten modellieren und Schnittstellen nutzen**, Teil 1. Ziel ist es das Lernziel «Bibliothekarische und archivarische Metadaten (z.B. MARC, MARCXML, MODS, Dublin Core, EAD, BIBFRAME) zu modellieren und diese mit entsprechenden Protokollen / Anwendungen zu übertragen und Crosswalks zwischen unterschiedlichen Metadatenformaten zu programmieren» zu behandeln.

**Um was gings:**<br>
Auch dieses Mal wurde wieder auf die Lerntagebücher Bezug genommen. Es scheint, dass die beiden Dozenten tatsächlich jeweils jetzt schon die Beiträge aufmerksam lesen, denn ein offener Punkt von mir wurde beantwortet. <br>
Mir hatte sich noch nicht so richtig erschlossen, weshalb Bibliotheken so oft zu Discovery-Systemen greifen, obwohl ein Katalog meistens auch eine Benutzeroberfläche für die Kundschaft zur Verfügung stellt. Ein Discovery-System ist scheinbar «nur» eine neuere Variante eines OPAC. Sie orientieren sich stark an Suchmaschinen wie Google (ein Suchschlitz) und haben ein moderneres Interface, als viele OPACs. Zudem sollen sie nutzerfreundlicher sein. Über diesen Punkt lässt sich aber sehr stark und intensiv streiten 😉

Austauschprotokolle für Metadaten (OAI-PMH, SRU)<br>
Die Protokolle spielen beim Austausch von Daten eine grosse Rolle. SRU, Z39.50 und OAI-PMH sind im Bibliotheksbereich verbreitet und zumindest SRU und Z39.50 sind mir in der täglichen Arbeit mit Aleph immer wieder begegnet. Jetzt macht das damals angewandte auch Sinn; hat man nach Fremddaten gesucht, sind diese Schnittstellen zum Thema geworden! Die Daten des IDS beispielsweise wurden via SRU stetig in WorldCat aktualisiert. Auch der KVK ist ein gutes Beispiel; es wird dort etwas gesucht und im Hintergrund werden die Daten in den einzelnen Katalogen über Z39.50 abgerufen. Dieselbe Rolle wie SRU/Z39.50 erfüllt aber auch die OAI-PMH, nur ist diese Schnittstelle besser geeignet für mehrere Daten auf einmal.<br>
Die Z39.50 ist recht veraltet und hat einige Nachteile; so ist beispielsweise eine Spezialsoftware nötig, wobei die SRU einfach im Browser anzeigbar ist. Z39.50 wird aber noch von einigen benützt, weswegen diese noch nicht «abgeschafft» wurde. Ganz nach dem Motto «man hat das immer schon so gemacht». Man kennts.<br>
Um die über OAI-PMH angebotenen Daten abzugreifen, braucht es einen Harvester (und die Endpoints müssen zur Verfügung stehen). Unser Harvester VuFindHarvest installieren wir wieder selber. 

XSLT Crosswalk (Konvertierung von einem Metadatenformat in ein anderes)<br>
Da es ja verschiedene Metadatenformate gibt, muss es irgendwie möglich sein, diese untereinander anzugleichen. Als Crosswalk bezeichnet man, wenn die Interoperabilität zwischen verschiedenen Metadatenforamten erleichtert wird. Sie dienen als Grundlage für das Sammeln von Metadaten und den Austausch von Datensätzen (Sprichword Harvesting) [^1]. Der “Crosswalk” beinhaltet also Regeln, wie Elemente einander zugeordnet werden (= Mapping). Trotz Crosswalks sind aber die Mappings nicht immer verlustfrei. 

![marcedit](https://user-images.githubusercontent.com/91015615/144753980-ee2eaae4-6fcd-4d92-b144-63ac9c08c33a.JPG)
MarcEdit kann mit XSLT verwendet werden, und kann fürs Mapping(??) benutzt werden. Es ist eine Software zur Bearbeitung von Metadaten (Erstellung und Bearbeitung).

**Was habe ich neu gelernt (oder wieder neu entdeckt):**
-	Die Funktionsweise von SRU/Z39.50 konnte mir klarer gemacht werden
-	Da Archivvesspace immer mit der Kommandozeile gestartet werden muss, ist es gut, wenn man den Befehl irgendwo speichert (da man das immer wieder braucht); archivesspace/archivesspace.sh
-	VuFind ist ein Discoverysystem und der Harvester wird mit dem Terminal bedient (hat kein anders Interface) 

**Was habe ich (noch) nicht verstanden:**
- Ist marcedit fürs Mapping ?


[^1]: <https://guides.lib.utexas.edu/metadata-basics/crosswalks>, abgerufen 5.12.21
