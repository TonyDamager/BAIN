---
title: "Übung 2: OAI-PMH Schnittstelle (Repositorien)"
date: 2021-11-29
---

Die folgende Aufgabe musste erledigt werden: 
![übungschnittstelleRepository](https://user-images.githubusercontent.com/91015615/143931016-e7e094b0-522d-41d1-84f7-05b3526750a1.JPG)


Aufgrund der zeitverzögerten Ansicht der Daten habe ich die Übung erst einen Tag nach dem Erstellen der Collection erledigt. Ich habe aber meine Collection ohne Probleme in der OAI-PMH-Schnittstelle gefunden:

![übersicht](https://user-images.githubusercontent.com/91015615/143931068-d2989f37-4cdc-422e-a767-4ddc9d1169b5.JPG)

In Metadata werden die Daten im Format Dublin Core angezeigt. Um später dann mit diesen Metadaten weiterzuarbeiten, wurden sie auf der VM gespeichert.

![metadaten](https://user-images.githubusercontent.com/91015615/143931097-2ba44a62-65a7-4339-872a-47909c910739.JPG)

Doch was ist überhaupt eine OAI-PMH-Schnittstelle?
Die Abkürzung steht für “Open Archives Initiative - Protocol for Metadata Harvesting” und ist dazu da, mit einfachen Anfragen per HTTP-GET oder -POST eine HTTP-Antwort von einem Datenlieferanten abzufragen. Dazu braucht es einen Datenlieferant (data provider) und einem Dienstanbieter (service provider), der die Daten beziehen kann. Die Antwort der GET oder POST Anfragen werden in eine XML-Struktur eingebettet OAI hat das Ziel, offene Schnittstellen zum Austausch von Metadaten zu machen [^1]. Kurz gesagt ist die Schnittstelle da, um Metadaten einzusammeln und weiter zu verarbeiten.


[^1]: <https://www.dnb.de/DE/Professionell/Metadatendienste/Datenbezug/OAI/oai_node.html>, abgerufen 29.11.2021
