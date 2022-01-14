---
title: "Tag 9: Linked Data und ein toller Katalog"
date: 2022-01-14
---

Die 9. Vorlesung ist gleichzeitig auch die letzte. Sie beginnt mit einer Wiederholung und **Nachträgen zum Thema Discoverysysteme** und vereinzelten **Praxiseinblicken**. Das letzte Thema war dann schliesslich **«Linked Data»**.

**Um was gings:**
Zu Beginn sind wir mit einem kurzen Marktüberblick zu Discovery-Systemen gestartet, inklusive einigen Präzisierungen. 
Discoverysysteme setzen sich normalerweise aus zwei Aspekten zusammen; es gibt einerseits ein Interface, also das, was schliesslich die Nutzenden sehen, und den Discovery Index. Im Discovery Index sind die Daten, welche im Interface angezeigt werden, hinterlegt. 
Leider wird die Diversität der Discoverysysteme immer schlechter, was wir aber bereits in der 3. Vorlesung heraushören konnte. In der Kurzfassung ist hier zu sagen, dass wahrscheinlich «Folio», von EBSCO in den nächsten Jahren wichtiger werden könnte, da es das Monopol von ExLibris, bzw. Clarivate etwas untergraben könnte. 

Praxiseinblick Literaturarchiv Marbach<br>
Da wir jetzt bereits am Ende des Moduls sind und auch schon letztes Mal alle Puzzlestücke zusammengefügt haben, erhielten wir heute einen kurzen Einblick, wie das schliesslich auch in der Praxis aussehen kann. Als gutes Beispiel wurde da die Neukonzeption des «Katalogs» des Literaturarchivs Marbach gezeigt. 
Dieser Katalog war zuerst eigentlich ein ziemliches «worst practice», ich das so sagen darf. Das Literaturarchiv ist nicht nur Archiv, sondern verzeichnet auch Museumsmaterialien und bibliothekstypische Materialien. Leider wurden diese Museumsobjekte nach Museumsregelwerken verzeichnet und Literatur natürlich nach Bibliotheksstandards. Es hat sich mir da ein bisschen die Frage gestellt, wieso man da nicht auf RDA umgeschwenkt ist, was sich ja dadurch auszeichnen soll, für jegliche Materialien verwendet zu werden. Das Literaturarchiv hatte nicht für alle Materialen einen Gesamteinstieg, sondern Nutzende, schlimmstenfalls überhaupt nicht Katalogaffine, mussten sich zuerst bewusst werden, um was für Material sich das Gesuchte handelt. Es musste somit im schlimmsten Fall im Archivbestand, im Bibliotheksbestand oder im Museumsbestand gesucht werden, was ich mir als absoluten Horror vorstelle. 3 verschiedene Kataloge bedeuten 3x mehr Zeitaufwand in einer Recherche, gleich potenziell 3x mehr Frustpotential. Das musste also dringend geändert werden.
Die Dozenten, welche mit diesem Projekt betraut waren, haben also zuerst einen Prototyp erstellt und konnten dann mithilfe verschiedener Anforderungen und einigen Verbesserungen ein super Produkt erstellen. Das Ganze basiert auf TYPO3, da dies eh schon als CMS in Marbach eingesetzt wurde.
Nun ist eine Suche im Gesamtbestand möglich, was ich eigentlich als Selbstverständlichkeit empfinde. Die einzelnen Bereich (Archiv, Museum und Bibliothek) sind nun auch als Facetten benützbar. 
Ich persönlich empfinde es als unglaubliche Stärke des Systems, dass ein grosses Augenmerk auf den Normdaten liegt. Diese scheinbar sehr sorgfältige und konsistente Erschliessung dieser sorgt für ein sehr positives Nutzererlebnis (was ich so auf die Schnelle erkennen kann). 
<img width="840" alt="katalog eintrag" src="https://user-images.githubusercontent.com/91015615/149552957-0859e564-09f2-426a-ab63-4e96714c3995.PNG">


Die Normdaten werden so schon in der Schnellsuche integriert und angezeigt (siehe Bild oben), falls vorhanden. Die ausgewählte Entität kann dann direkt übernommen werden und man erhält dann wirklich die mit der Entität erschlossenen Treffer! Auch werden Daten aus Wikidata einbezogen (falls vorhanden), was direkt wieder eine Brücke zu unserem Unterricht schlägt (mit der Reconcilation). Oder es werden Weiterleitungen zu anderen Webeinträgen angezeigt.
<img width="848" alt="blobel treffer" src="https://user-images.githubusercontent.com/91015615/149552997-f98eae93-3b8c-4905-ad5d-999c07082a3a.PNG">

Ich bin mega begeistert von diesem Katalog und meine Gedanken bei der Präsentation war «Supergeiler Katalog». Da geht einem das Normenherz auf wenn man sieht, dass man daraus sehr viel rausholen kann.

Linked Data<br>
Schliesslich kamen wir zum letzten Thema und haben uns nochmal ausführlicher mit BIBFRAME und RiC beschäftigt.
BIBFRAME basiert auf FRBR und RDA, was mir natürlich bekannt ist. Es folgt dem «Linked Data» Paradigma. Ich verstehe das so, dass es nicht mehr nur darum geht, einer Liste mit Angaben zu folgen und diese Auszufüllen, sondern dass man die einzelnen Teile auch miteinander verknüpft. Es ist also eine komplett andere Vorgehensweise gegenüber MARC21. Ich stelle mir das so vor:
wenn man 100 Springer Bücher hat (also vom Springer Verlag), dann ist dieser Verlag quasi auch 100x in MARC eingetragen. 
Bei BIBFRAME ist das dann aber nur noch 1x hinterlegt (bei Instance) und man verknüpft es dann mit allen anderen Springer-Titeln. Das ergibt natürlich eine Dateneinsparung. Damit dann aber die Einträge auch einigermassen einheitlich sind, gibt es das Bibframe Vocabulary -> Ontologie (Brücke zum Modul SESY)

 <img width="357" alt="bibframe" src="https://user-images.githubusercontent.com/91015615/149552189-fd47f58c-28c1-4c03-9a96-c8d5b00312ec.PNG">
Das Model Bibframe, man sieht es ist sehr ähnlich wie FRBR, dort gibt es aber noch die Instanz "Expression", mit welchen man beispielsweise Ausgaben von anderen Sprachen oder so darstellen kann.

RiC<br>
RiC ist Records in Context und wird zukünftig eine grosse Rolle in Archiven spielen. Man wird auch hier Entitäten in Kontexte setzen. RiC führt zu einer erheblichen Veränderung in der eher rückständigen Erschliessungspraxis der Archive (was mit Bibframe bei Bibliotheken durch die Einführung von RDA und FRBR weniger der Fall ist. 


**Was habe ich neu gelernt (oder wieder neu entdeckt):** <br>
-	Mit github actions kann man automatische Prozesse ablaufen lassen (z.B: über eine VM)<br>
-	Wikidata zukünftig von grosser Relevanz<br>

**Was habe ich (noch) nicht verstanden:**

