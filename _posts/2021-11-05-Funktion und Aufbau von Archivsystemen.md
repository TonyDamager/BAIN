---
title: "Tag 4: (Nicht so) Neues aus der Bibliothekswelt und meine erste Archiverschliessung"
date: 2021-11-05
---

Die 4. Vorlesung wurde ein **Gastreferat über ALMA** abgehalten. Nach diesem Input folgte ein Slot über den **ArchivStandard ISAD (G)** und als Letzts wurde auf **Archivesspace** weitergearbeitet, welches bis heute installiert werden musste. 

**Um was gings:**
Als Gastreferentinnen waren Selina Hodel und Charlotte Frauchiger aus dem Team dabei. Das Team eRessourcen ist für die Umsetzung von SLSP an der FHNW zuständig. Dies war für mich insofern überraschend, da bei uns an der ZHB Luzern die IT für die Umsetzung zuständig ist. Der Input war für mich leider nicht sehr bereichernd, da ich täglich mit Alma arbeite. Spannend fand ich allerdings, wie die Konfigurationsoberfläche aussieht, diese wird an meiner Institution ausschliesslich vom Systembibliothekar bearbeitet. 

Alma wurde in der Schweiz im Zuge eines schweizweiten Projektes eingeführt und ist im Winter 2020 live gegangen. Die Swiss Library Service Platform ist als AG aufgebaut und vereint 475 Bibliotheken. SLSP hat die «alten» Bibliotheksverbünde wie Nebis, IDS oder IDS Basel/Bern abgelöst und vereinigt nun die Medien der Verbundsbibliotheken im Katalog «swisscovery» der Firma Primo. 
Alma ist cloudbasiert, genauso wie Koha. Ex Libris ist Anbieter von Alma. Die cloudbasierte Technologie ermöglicht es Ex Libris, Anpassungen direkt selber und vergleichsweise unkompliziert bei den Bibliotheken einzuspielen -> weil cloudbasiert.
Ein grosser Vorteil von Alma gegenüber früherer Systeme ist folgender: 
![alma](https://user-images.githubusercontent.com/91015615/140651625-859d8f44-ffc5-4174-96b6-17072a389eb6.JPG)


Das URM (Unified Resource Management System) vereint alle benötigten Prozesse zur Verwaltung von Ressourcen oder zum Betrieb der Bibliothek in einem System. Dies war früher anders, so musste das Bibliothekssystem noch mit anderen Systemen arbeiten, beispielsweise wurde SFX noch als Link Resolver benutzt, teilweise noch ein separates System zum Drucken von Signaturen oder zur Darstellung von eRessourcen im Katalog. Alma ermöglicht die Vereinigung in einem System.



Auch der Aufbau von Alma ist mir nicht neu, dieses Bild verdeutlicht die ganze Struktur sehr gut:
![almaIZ](https://user-images.githubusercontent.com/91015615/140651639-c5e8c988-9c04-45f5-a851-d6e6226a0b59.JPG)


Die Communityzone, CZ, ist die grösste und allumfassendste Zone. Hier werden eRessourcen wie eBook Pakete oder Normdaten eingespielt. Jede Alma Nutzende Bibliothek hat darauf Zugriff und ist hier integriert.<br>
Die NZ ist vergleichbar mit dem früheren Katalog swisslib. SLSP als Ganzes gilt in diesem Schema als ein einziger grosser Verbund. Hier wird alles bearbeitet, was für die teilnehmenden Bibliotheken gleichermassen relevant ist, so werden beispielsweise Konsortiallizenzen freigeschaltet, oder auch Open Access Daten eingespielt.<br>
In der IZ finden Prozesse statt, welche nur für die jeweilige Institution relevant ist. Hier werden die erworbenen eRessourcen für den eigenen Verbund/Institution aktiviert, Mitarbeiterrollen, Öffnungszeiten und Etats werden für die teilnehmenden Bibliotheken angepasst. In der IZ ist also das machbar, was wir in der letzten Vorlesung in Koha machen konnten.
Nach dem Theorieteil über SLSP folgte eine Live Demo in Alma und eine strategische Spielerei mit folgenden Resultaten:
![strategie1](https://user-images.githubusercontent.com/91015615/140651855-2cf1eae8-e0c7-4744-ac69-ca5d1ef3edd0.JPG)
![strategie2](https://user-images.githubusercontent.com/91015615/140651851-0ad1ca3a-c17e-434b-954d-fa0f2de10e26.JPG)
![strategie3](https://user-images.githubusercontent.com/91015615/140651852-277f6dc8-f261-4631-ae6c-7992c3ea9f98.JPG)
![strategie4](https://user-images.githubusercontent.com/91015615/140651854-20994ca9-2601-4271-87bb-eb454b778098.JPG)


Weiter ging es mit Archivsystemen.

ISAD (G)<br>
Wie auch im Bibliothekswesen haben sich im Bereich Archiv die Datenstrukturen an bisherigen Handhabungen orientiert; die Archivsysteme orientierten sich an physischen Findmitteln. ISAD (G), mit folgenden Pflichtfeldern, ist das entsprechende Regelwerk dazu.
 ![pflichtfelder](https://user-images.githubusercontent.com/91015615/140651664-ba925496-6ad3-48d9-83ad-4697f950491d.JPG)


Das entsprechende Datenformat im Archivwesen ist die EAD (Encoded Archival Description). 
Leider hat auch ISAD (G) Grenzen, so sind wegen der eindimensionaler Erschliessung Kontexte nötig, um einzelne Datensätze zu verstehen. Ausserdem ist der Standard aufgrund der Entstehung in den 90er etwas hängengeblieben und enthält keine Vorgaben zur Digitalisierung oder zur digitalen Langzeitarchivierung.
Nach dem Exkurs über ISAD (G) wurden einige Konfigurationen in Archivesspace getätigt und wir sollten versuchen, einen eigenen Datensatz zu erstellen. Die Aufgabe lautete wie folgt: 
 ![aufgabenstellungarchiv](https://user-images.githubusercontent.com/91015615/140651837-3f06f216-08be-4779-961c-2e28c832c473.JPG)


Die Übung hat (trotz langer Wartezeit) gut funktioniert:
 ![aufgabearchiv](https://user-images.githubusercontent.com/91015615/140651730-690587e7-f7b5-4fc0-a3e9-432f48a4d9f7.JPG)


**Was habe ich neu gelernt (oder wieder neu entdeckt):**
-	CDI =  den Begriff habe ich sicher auch schon gehört, aber da bei uns nicht relevant etwas verdrängt. Die CDI ist eine zentrale Datenbank mit 3 Milliarden Datensätzen, kann aktiviert werden um zusätzliche Treffer zu finden (welche aber nicht in der IZ vorhanden sin) -> vorallem für eBooks oder Zitationen hilfreich. Short: eine grosse Sammlung an diversen Ressourcen, auch wenn die betreffende Bibliothek keinen Zugang besitzt, man hat als Nutzer «immerhin» die Referenz darauf (Quelle: https://www.youtube.com/watch?v=Y8vOFgG8lo0, abgerufen am 6.11.)
-	Grundsatz bei archivarischer Erschliessung: Provenienzprinzip (um den Entstehungszusammenhang abzubilden).
-	Aktuell ist der neue Standard “Records in Contexts” (RIC) in Entwicklung. Dieser berücksichtigt die Linked-Data-Prinzipien

**Was habe ich (noch) nicht verstanden:**
---


