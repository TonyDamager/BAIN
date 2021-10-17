---
title: "Tag 3: Funktion und Aufbau von Bibliothekssystemen - mein eigenes Bibliothekssystem!"
date: 2021-10-17
---

Die dritte Vorlesung war vor allem von **«Funktion und Aufbau von Bibliothekssystemen»** geprägt. Leider haben wir uns hauptsächlich mit der **KOHA-Installation** befasst, welche bei einigen Klassen»gspändli» nicht richtig geklappt hat. Wir erhielten einen kurzen **Marktüberblick**.

**Um was gings:**
Die Dozenten haben die Unterrichtsstunde wieder mit einigen Klarstellungen und Ergänzungen zu den Lerntagebüchern gestartet. Es wurde vor allem nochmal auf den Unterschied von Regelwerken und Formaten eingegangen. Bei Regelwerken handelt es sich um theoretische Grundlagen, bei Formaten wiederum um die Codierung solcher. 
Bei der letzten Vorlesung erhielten wir die Hausaufgabe, Koha fertig auf der VDI zu installieren. Da ich im Unterricht schon sehr weit kam, konnte ich den Rest noch vor der 3. Vorlesung erledigen. Somit hatte ich nun mein erstes Bibliothekssystem selber installiert! Diese Erfahrung fühlt sich schon ziemlich cool an, da ich so Einblick ins Tun von Systembibliothekaren erhalten konnte. Wie viele andere hatte ich zuerst auch das Problem, dass ich Koha nicht starten konnte und die Fehlermeldung «internal server error» erhielt. Nach Installation ging es drum, das System für die eigene fiktive Bibliothek zu konfigurieren. Mit dem selbstredenden Tutorial bei Kapitel 2 und 3 konnten wir uns näher mit der Koha-Administration auseinandersetzen. Diesen Teil fand ich recht spannend, da es für mich sehr Alltagsnah war. 
Basisparameter wie Adresse, unterschiedliche Medientypen, Benutzertypen konnten sehr einfach erstellt werden. Ich habe bei diesen Parametern ein bisschen auf die eigene Erfahrung von meiner Ausbildung in einer öffentlichen Bibliothek zurückgegriffen. 
![bildBenutzer](https://user-images.githubusercontent.com/91015615/137634895-9beab067-f3ed-4ce5-929d-ba24f78d572f.JPG)

 
Bei den Codes und den Kategorien hatte ich etwas Mühe, jeden Bibliotheksnutzenden zu kategorisieren. Es ist schwer, die Kategorien passend zu erstellen, damit jeder und jede potentielle Nutzende einen passenden Benutzertyp erhält. 
Nach der Einrichtung der Grundeinstellung konnte Koha benutzt werden. Der Erste Titel wurde erfasst, wozu ich auch wieder meine bibliothekarischen Vorkenntnisse ideal einsetzen konnte. Durch das Einstellen des Parameters «AmazonCoverImages» und «OPACAmazonCoverImages» auf «Zeige» wird nun sogar auch der Buchtitel des katalogisierten Buches angezeigt.
 ![bildBuch](https://user-images.githubusercontent.com/91015615/137634913-5055cea0-c186-4f23-9e26-de7b283e1e37.JPG)


Auch das Erstellen eines Benutzers und die Ausleihe & Rückgabe des Titels hat reibungslos geklappt. 

Datenimport & Serveranbindung<br>
Mit einer Anleitung konnten wir den Z39.50/SRU-Server anbinden. Bei der Fremddatenübernahme in Aleph hatte ich bereits einige Male in Kontakt damit, habe aber nie nachgeforscht, was es damit auf sich hat. Laut BvB handelt es sich bei Z39.50 um «ein international standardisiertes Netzwerkprotokoll für die Recherche von Daten aus bibliografischen Datenbanken» [^1]. Mit SRU (Search/Retrieve via URL) hat man die Möglichkeit, Datenbanken im Internet abzufragen -> es handelt sich eine Art um einen Nachfolger von Z39.50. Die Abfrage geschieht mittels einem Protokoll, welches die gezielte Suche und die Übernahme der entsprechenden Treffer in die eigene Umgebung ermöglicht. Z39.50 wurde von der Library of Congress entwickelt.

Marktüberblick Bibliothekssysteme<br>
Das Thema «Marktüberblick Bibliothekssysteme» wurde leider nur noch kurz angeschnitten. Mich hätte ein umfassender Vergleich sehr interessiert, um später im Berufsleben besser berücksichtigen zu können, was für ein Bibliothekssystem essentiell ist und wie die ganze Marktsituation aussieht. Obwohl mir sehr wohl bewusst war, dass der Informationsmarkt immer mehr von grossen Firmen aufgekauft wird, war mir das Ausmass nicht bewusst. Alma und Primo, welche zu ExLibris gehörten, wurden von von Proquest gekauft. Proquest gilt als Datenbankanbieter als starker Konkurrent zur Firma EBSCO. Proquest und somit auch ExLibris wurde dann von Clarivate aufgekauft. Clarivate steht vorallem mit der Literatur- und Zitationsdatenbank Web of Science in Verbindung und auch der Medienkonzern Thomson und Reuters ist Teil von Clarivate [^2]. Durch diesen eher kritischen Zusammenschluss kommen mehrere Aspekte zusammen, welche zu einer enormen Marktkonzentration auf einige wenige Firmen führen. Das Statement von ExLibris dazu ist<br>
> «By bringing together these two customer-focused businesses with a purpose to accelerate innovation at their core, we will create a world-leading software and information provider for research-focused organizations to fuel scientific discovery and innovation into the future».<br>
Es bleibt also sehr spannend zu beobachten und man hofft, dass diese grosse Firma Clarifate den Zugang zur freien Information nicht gefährdet.

Empfehlung:<br>
Laut Dozenten ist das integrierte Bibliothekssystem «Folio» empfehlenswert, welches mittlerweile auch eine starke Marktmacht hat. Folio ist, wie Koha, OpenSource und wurde von EBSCO gegründet, quasi als Gegenbewegung zum Proquest. Die Produktivversion wurde aber erst 2020 veröffentlicht, weswegen sich noch in der [Statistik](https://americanlibrariesmagazine.org/wp-content/uploads/2021/04/Library-Systems-Report-2021-Tables-and-Charts.xlsx) noch keine grosse Verkaufszahlen verzeichnet.

**Was habe ich neu gelernt:**
-	Es wurde schon bei der letzten Vorlesung genannt, aber heute erneut genannt; BIBFRAME wird in Zukunft MARC ersetzen. Zudem ist BIBFRAME ein Datenformat, aber weil es nicht ganz trennscharf ist zu einem Regelwerk, spricht man hier eher von einem Datenmodell
-	Mit «Q» kommt man wieder aus der Konsole raus
-	Enorm grosse Marktkonzentration im Bereich «Bibliothekssystem», «Datenbankanbieter» und freie Informationen.

**Was habe ich (noch) nicht verstanden:**
Das Thema Schnittstellen und deren Funktion ist mir noch etwas schleierhaft. Ich gehe aber davon aus, das diesbezüglich noch genauere Inputs folgen.

[^1]: <https://www.bib-bvb.de/web/b3kat/z39.50>, abgerufen 17.10.21
[^2]: <https://exlibrisgroup.com/press-release/clarivate-to-acquire-proquest/> und <https://www.buchreport.de/news/paukenschlag-clarivate-uebernimmt-proquest/>, abgerufen 17.10.21
