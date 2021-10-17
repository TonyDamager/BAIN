---
title: "Tag 2: Langsam wirds bibliothekarisch"
date: 2021-10-07
---

Die zweite Vorlesung war vor allem von **weiterführenden Informationen zu Git und den Lerntagebüchern geprägt**, zusätzlich wurde mit dem Thema **«Funktion und Aufbau von Bibliothekssystemen»** begonnen. 

**Um was gings:**
Da das Thema Git bei der letzten Vorlesung ziemlich kurz kam (oder ich verpasst habe, weil ich den Zug auf Chur nehmen musste), habe ich in dieser Vorlesung versucht richtig aufzupassen. <br>
Git ist ein Versionsverwaltungssystem, welches von Linus Torvalds – welcher auch Linux erschaffen hat – entwickelt wurde [^1]. Die Befehle für Git werden normalerweise auf dem Terminal ausgeführt [^2]. Das Programm läuft dezentral und kann von den Anwendern direkt lokal installiert werden. Es ist deswegen mittlerweile weit verbreitet. Weiter nennt die Website «howtogeek» folgende Vorteile von Git: «It stores file changes more efficiently and ensures file integrity better» [^3]. Das klingt nach einem super System, mit welchem kollaborativ und relativ einfach in (Programmier)-Projekten gearbeitet werden kann.<br>
Github hingegen ist eine Webseite, in welcher solche Projekte abgespeichert werden können und die Codes auch als Open Source zugänglich gemacht werden können. Dasselbe mit Gitlab, dieses ist in der «Community Edition» selber auch Open Source. Ich ziehe also für mich den Schluss, dass Github/Gitlab etc. eine Art Gefäss für Projekte, welche Git beinhalten ist.<br> 
Nach dieser Theorie hatten wir dann selber die Aufgabe, Git zu installieren und einen Link in Felix Lohmeiers Repositorium zu ergänzen. Diese Änderung sollten wir dann mithilfe von Git erledigen und mitverfolgen. Diese Aufgabe konnte ich dank dem 1-1 Tutorial gut lösen.<br>
Beim Thema «Funktion und Aufbau von Bibliothekssystemen», Teil 1 haben wir das Bibliotheksformat MARC21 kurz unter die Lupe genommen. Es ist ein weit verbreiteter «Standard». Standard in Klammer, da MARC21 wegen unterschiedlicher Katalogisierungsregeln und auch der Möglichkeit, eigene Felder zu belegen, nicht in jeder Institution gleich behandelt wird. Quasi im gleichen Atemzug haben die Dozenten noch Dublin Core erwähnt. Ursprünglich war Dublin Core dazu da, dass Autoren von Webressourcen ihre Ressourcen beschreiben können, so, dass sie von stichwortbasierten Suchmaschinen gefunden werden. 
Ziel der beiden Formate ist es also, dass Daten standardisiert werden und sie dienen dem besseren Auffinden von Daten, seien dies Bibliotheksmedien -> MARC oder von Webressourcen -> DC.<br>
Nach dem Dozenteninput hat die ganze Klasse die beiden Formate anhand von zwei Beispielen verglichen. Ich habe für mich persönlich eine kleine Tabelle erstellt:
![bainMARCDC](https://user-images.githubusercontent.com/91015615/136242716-0012d6aa-74a8-4af8-b479-4c9c7f88d72a.jpg)


Koha<br>
Koha ist ein Open Source Bibliothekssystem mit Gemeinschaftscharakter. Die Gesellschaft ist sehr ideell geprägt und beschreibt sich selber so «Koha is a fully featured, scalable library management system. Development is sponsored by libraries of varying types and sizes, volunteers, and support companies worldwide» [^4]. Um im Modul «BAIN» Einblicke in Bibliothekssysteme zu erhalten, wird Koha auf die VDI geladen. Auch dies geschieht wieder per Shell und konnte ich ohne Unterbruch bewerkstelligen. Ich bin gewissermassen bisschen stolz, dass ich ohne die Hilfe der Dozenten diesen Schritt geschafft habe. Aufgrund technischer (oder Anwender-)Probleme hat das nämlich nicht jeder geschnallt :P


**Was habe ich neu gelernt:**
-	GitHub vs. GitLab (schlechte Unternehmenskultur in Gitlab!), viele darum noch bei bei GitHub. Aber beide zur Veröffentlichung von Opensource, Gitlab ist selber auch Opensource
-	Die Shell ist völlig auf Effizienz ausgelegt. Muss man mit der Maschine interagieren, ist meistens das «Yes» schon per Default eingestellt. Erhalte ich also die Aufforderung [Y /n], wird mit dem Bedienen der Entertaste automatisch Y ausgewählt.


**Was habe ich (noch) nicht verstanden:**
Der Sinn und Zweck von Git in diesem Kurs hat sich mir noch nicht so erörtert. Es ist mir klar, dass es beim Coden hilft, den Überblick über Versionen und Änderungen zu behalten. Wie wir aber dann schlussendlich wirklich damit arbeiten, ist mir noch unklar.<br>
Die Befehle in der Shell werden noch nicht so selbstverständlich aus den Ärmeln gezogen. Immerhin ergibt mittlerweile «sudo» (switch user and do) Sinn, auch «cd» (change directory) geht leicht von der Hand. Mit der Übung kommt das langsam gut…


[^1]: <https://youtu.be/V_IDzTNA_ns>, abgerufen 3.10.21
[^2]: <https://youtu.be/xXWNh2q9l4U> , abgerufen 3.10.21
[^3]: <https://www.howtogeek.com/180167/htg-explains-what-is-github-and-what-do-geeks-use-it-for/> abgerufen 5.10.21
[^4]: <https://koha-community.org/> abgerufen 5.10.21
