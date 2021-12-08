---
title: "Tag 6: Metadaten und Schnittstellen - Messy Data in Bibliotheken??!"
date: 2021-12-08
---


Die 7. Vorlesung hatte das Thema **Metadaten modellieren und Schnittstellen nutzen, Teil 2**. Es war ein sehr praktischer Teil, in welchem viel in **OpenRefine** getestet und gepröbelt wurde. OpenRefine ist ein Tool der Metadatentransformation.

**Um was gings:**
An der heutigen Vorlesung stand wieder das Thema Metadaten modellieren im Vordergrund. Dass Tabellendaten ergänzt und bearbeitet werden, ist scheinbar in Bibliotheken oder Archiven sehr üblich. Wer diese Transformationen übernimmt, hat sich mir aber gerade noch nicht erschlossen (siehe dazu meine Frage zum Schluss). <br>
Gerade im Bibliotheksbereich gibt es sehr wohl auch «messy Data» (wie auch der Claim von Open Refine sagt), auch wenn man das als Bibliothekarin natürlich nicht gerne hört. OpenRefine ist ganz gut geeignet für Einsteiger, welche keine Programmiersprachen beherrschen. Es ist auch ein gutes Tool für Datenanalyse (detaillierter als Excel) und ist Open Source.<br>

Der Zweck von OpenRefine ist auf deren eigenen Website wie folgt beschrieben:
>«OpenRefine (previously Google Refine) is a powerful tool for working with messy data: cleaning it; transforming it from one format into another; and extending it with web services and external data.»


Es ermöglicht, eigene Daten mit externen abzugleichen und Daten aus diesen externen Datenbanken zu übernehmen. Das Tool wird lokal installiert und dann via Browser darauf zugegriffen.<br>
Vorallem Tabellendaten (bspw. csv) werden von OpenRefine unterstützt, aber auch Austauschformate. Marcedit kann helfen, dass MARCdaten besser verarbeitet werden können, was für die Bibliotheksarbeit natürlich essentiell ist.

Für was eignet sich OpenRefine:<br>
-	Exploration von Datenlieferungen
- Vereinheitlichung und Bereinigung (zur Datenqualität in der Praxis siehe Präsentation von Peter Király “Validating 126 million MARC records”) -> Daten sind also nicht so «sauber» wie Bibliothekare immer meinen
-	Abgleich mit Normdaten (“Reconciliation”) in Wikidata, GND und VIAF
-	Für lokalen Einsatz ausgelegt (Installation auf Webservern und Automatisierung möglich, aber nur mit Zusatzsoftware)

 
Praktisches Arbeiten mit OpenRefine<br>
Um mit OpenRefine zu arbeiten, mussten wir das Tool wieder installieren. Da bereits die vorherigen Aufgaben in der Shell sehr gut funktioniert haben, bin ich mega motiviert und es macht sogar fast Spass, in der Shell zu arbeiten. Die Dozierenden haben also schon mindestens ein Ziel für mich erreicht; den Schaden aus ARIS wieder etwas gerade zu biegen.<br>
Die Arbeit mit dem Tool ist ein bisschen wie Excel, allerdings viel krasser; man kann filtern und sortieren, Daten können «gemergt» und verändert werden, Daten werden vereinigt mit anderen Daten (reconcile). Das passiert beispielsweise, wenn man aus Wikidata Informationen zieht und zu einem Zeitschriftentitel hinzugefügt (anhand der ISSN)-> sehr beliebte Funktion von Openrefine.

Nach einer Theorie-Session hat das praktische Arbeiten in OpenRefine angefangen. Hier ein paar Eindrücke:
![openrefine1](https://user-images.githubusercontent.com/91015615/145261922-99a8158b-7463-4e63-95ab-28bc98ee9ab8.JPG "Einsicht in die Filter in OpenRefine: Man sieht hier sehr gut, dass die Daten unsauber sind. Sprachen wurden teilweise abgekürzt oder ausgeschrieben. Diese können aber ziemlich einfach für alle Werte in "Language" angepasst werden.")

![openrefinekolummne erstellen nur spalte0](https://user-images.githubusercontent.com/91015615/145263296-676cc2c2-c7ae-4506-8ab9-8b6f60637348.JPG "bei OpenRefine kommen potenzielle Coding-Skills zum Tragen. Das , veranlasst, dass ab der ersten (0ten) Tabelle mit einem Komma gesplitettet wird.")

![reconcileopenrefine](https://user-images.githubusercontent.com/91015615/145263838-8ba8c976-da38-4184-a083-74237876d399.JPG "Der Reconcile-Vorgang. Man versucht hier, mit dem Anwählen von ISSN, dass man die Spalte "Journal" mit Wikidata ergänzt. Die Daten werden anhand passender ISSN gematcht." )

![openrefine nach reconcile](https://user-images.githubusercontent.com/91015615/145264200-a3a4ac60-0da9-4000-9adb-7bba05a1b715.JPG "Ergebnis vom Reconcile. Daten aus Wikidata wurden ergänzt.")



**Was habe ich neu gelernt (oder wieder neu entdeckt):**
-	Das Tool und deren Funktionen ist mir völlig neu und war sehr spannend. Die Arbeit damit aber nicht immer sehr intuitiv, da die Vorgänge nicht immer bekannt waren

**Was habe ich (noch) nicht verstanden**
-	Wer in einer Bibliothek übernimmt diesen Job? Geschieht das vorallem, wenn man eBook-Pakete einspielt?
