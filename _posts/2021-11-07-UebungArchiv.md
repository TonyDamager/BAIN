---
title: "Übung 1: Import und Export Archivesspace (Archivsysteme)"
date: 2021-11-07
---

In der Aufgabe ging es darum, den dateibasierten Import und Export von Archivesspace in diversen Formaten (EAD, MARCXML, CSV) zu testen. In den folgenden zwei Übungen werden wir EAD-Beispieldaten in ArchivesSpace importieren und anschließend in MARCXML exportieren.

**Import**<br>
Leider hatte ich bereits beim ersten Punkt Mühe – ich fand die gesuchte Datei zwar, allerdings war ich schlicht und ergreifend zu blöd, das zu downloaden… 
nach ein paar Mal rumpröblen habe ich es dann aber (hoffentlich) doch noch geschafft.  

![uebung2](https://user-images.githubusercontent.com/91015615/140655893-eac87792-290b-4ed4-9a5a-313b8b4bc948.JPG)


![uebung3](https://user-images.githubusercontent.com/91015615/140655917-e7dda4e4-177f-4e7c-b3d4-53a6e3b75dec.JPG)


![uebung1](https://user-images.githubusercontent.com/91015615/140655941-f749fc5d-b426-44ec-8178-b849262301d5.JPG)


Schliesslich lud ich das File hoch und hoffte sehr, dass der Import auch so geschieht, wie ich mir das vorstelle, und tatsächlich: der Job konnte gestartet werden und während er ausgeführt wurde, fühlte ich mich wie Hackerman!

 ![uebung4](https://user-images.githubusercontent.com/91015615/140655980-628415fc-dce0-4bac-9f83-54afabb614e2.JPG)


Nachdem der Job beendet war, habe ich im Public Interface gecheckt, ob der Import auch richtig funktioniert hatte, und siehe da – ich habe eine neue Aufnahme in meinem Archivsystem. ![uebung5](https://user-images.githubusercontent.com/91015615/140656262-24e51533-4337-452d-8672-ba74abad5927.JPG)<br>
Die HTML-Anzeige unterschied sich natürlich ganz klar zur Anzeige in Archivesspace, das XML wurde entsprechend auch für Menschen «lesbar» gemacht.

**Export**<br>
Als zweite Aufgabe mussten wir die erst grad importierten Daten wieder Exportieren und als MARCXML speichern. Ich fand es etwas schwer, die Exportfunktion zu finden, mithilfe des Tipps der Dozenten klappte aber auch das:

![uebung6](https://user-images.githubusercontent.com/91015615/140655997-8f60bd55-4942-4529-904b-4711ed309d6a.JPG)
 

Auf den ersten Blick scheint der Export aber recht gut geklappt zu haben, es ist mit unserem Wissensstand aber etwas schwer, festzustellen, ob der Export absolut verlustfrei geklappt hat. Allerdings ist klar, dass – vereinfacht gesagt – die Archivaufnahme nun in eine Bibliotheksaufnahme verwandelt wurde. Einige Beispiele: das Feld «titleproper» in EAD wurde korrekt in 245 (MARC) überführt, ebenfalls der Urheber (in EAD «origination» zum MARC Feld 110).<br>
Diese Übung war sehr spannend und hat mir gezeigt, wie wichtig Standards und deren Zusammenspiel ist. Der Vergleich EAD zu MARC hat einen schönen Vergleich dargestellt.

![dumb](https://user-images.githubusercontent.com/91015615/140656005-b50876d9-7985-4110-b972-fa3bccb9eabf.JPG)


**Lösung, genannt von Dozenten**
Die Ansicht in ArchivesSpace enthältmehr Informationen als das exportierte MARCXML. In MARC21 sind nicht für alle archivspezifischen Angaben Felder vorgesehen, so dass einige Angaben nicht übernommen werden können (siehe Mapping-Regeln von ArchivesSpace).

