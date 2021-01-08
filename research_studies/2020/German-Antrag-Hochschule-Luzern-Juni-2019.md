# Antrag zur Ausschreibung einer studentischen Projektarbeit
_Wirtschaftsprojekt/Bachelorarbeit_

## Titel des Projektes
Untersuchung eines vollständig dezentralen, nicht-diskriminierenden und Privatsphäre-schützenden Handelsnetzwerk für digitale Werte (“Krypto-Anlagen”).

## Ausgangslage und Problemstellung

### Ausgangslage
Das Projekt ist ein Forschungsprojekt. Basierend auf der untenstehenden Annahme wird eine These in Form eines Software Prototypen durch den Auftraggeber zur Verfügung gestellt. Per Ende Mai 2019 existierte kein öffentlich verfügbares System, welches die untenstehende Annahme bzw. These abbildet. Dieser Software Prototyp ist darum Neuland. 
Aus der These, d.h. dem Software Prototypen, entstehen Hypothesen, welche zu falsifizieren sind.

### Annahme
Ein vollständig dezentrales und nicht-diskriminierendes Handelsnetzwerk und -system für digitale Werte (“Krypto-Anlagen”) mit einer Privatsphäre-schützenden Architektur ist vorteilhaft für alle Netzwerkteilnehmer. 

### These
Dies sind die Eigenschaften des Software Prototypen:
* alle Daten und Prozesse sind vollständig dezentralisiert
* nicht-diskriminierend, dazu gehören insbesondere die Eigenschaften Freier Software sowie tiefstmögliche Installations- und Betriebskosten
* ein hinreichend Privatsphäre-schützendes Netzwerk erlaubt den Handel (Tausch, d.h. Kauf und Verkauf) von Blockchain-basierten digitalen Werten (“Krypto-Anlagen”)
* die digitalen Werte sind vor unautorisierter Nutzung geschützt (Stichworte: Diebstahl, “double spending”)
* die Installation kann für jeden aktiven Teilnehmer im Netzwerk vorteilhaft sein

Der Software Prototyp stellt somit die These dar und wird vom Auftraggeber auf einer Linux Plattform zur Verfügung gestellt. Es ist möglich, dass der Prototyp Programmierfehler und Funktionsmängel aufweist. In der ersten Phase des Projektes muss festgelegt werden, wie mit Fehlern und Mängeln umgegangen wird.

### Technologien des Prototypen
Der  Software Prototyp basiert auf folgenden Technologien:
* I2P Netzwerk oder, als untergeordnete Alternative, Tor
* mehreren, fundamental unterschiedlichen Blockchain-Implementationen; mit einer mittleren Wahrscheinlichkeit sind dies Bitcoin, Monero, Ethereum und Ripple und damit vermutlich sechs handelbare Krypto-Anlage-Paare
* zahlreichen quelloffenen Entwicklungen von unterschiedlichen Autoren

Alle Komponenten des Prototypen müssen quelloffen sein und auf den einschlägigen Plattformen im Internet (z.B. “gitlab” oder “github”) veröffentlicht werden. 

### Architektur des Prototypen
Der Prototyp der Software besteht aus drei Kern-Funktionalitäten innerhalb eines Knotens des Netzwerkes: 
* einer Funktion für das Handeln mit Krypto-Anlagen (“Handelsfunktion”)
* einer Funktion zur Vermittlung von 2..n Handelsfunktionen zwecks Abwicklung von 1..n Transaktionen (“Abwicklungsfunktion”)
* einer Funktion zwecks Sicherstellung der Korrektheit der Abwicklungsfunktion (“Regulator-Funktion”). 

Jeder Netzwerkteilnehmer, d.h. ein Knoten, kann ein beliebiges Set von Funktionen bereitstellen.
Die Netzwerkteilnehmer können soweit anonym bleiben wie dies die unterliegende Anwendungsschicht (z.B. “I2P”) erlaubt. Jede einzelne Nachricht im Netzwerk muss zustandslos sein. Je nach Funktionsbündel des Netzwerkteilnehmers fallen Gebührenaufwände und/oder -erträge an.
Der Handel mit Krypto-Anlagen kann sowohl in Echtzeit wie auch Auktionsbasiert stattfinden.

### Hypothesen
Dies sind Vorschläge von Hypothesen, welche im Rahmen des Projektes mit geeigneten Methoden zu falsifizieren wären:
1. mit einer steigenden Zahl von Netzwerkknoten reduziert sich die Ausfallwahrscheinlichkeit des gesamten Netzwerkes
2. eine steigende Zahl von Netzwerkknoten führt zu einer steigenden Transaktions-Kapazität des gesamten Netzwerkes
3. eine steigende Zahl von Netzwerkknoten erhöht die Resistenz gegen Brüche der Privatsphäre der Teilnehmer im Netzwerk
4. eine unautorisierte Nutzung von digitalen Werten (z.B. Diebstahl) ist nicht möglich: weder durch Veränderungen des Source-Codes, noch durch Veränderungen der Netzwerkstruktur oder des -verkehrs.

Der Auftraggeber ist offen für weitere oder andere Hypothesen.

### Zusammenarbeit
Die Kopanyo AG, namentlich Carolyn Bächler-Schenk und Konrad Bächler, arbeiten während der gesamten Projektdauer zu 100% mit. Sie sind verantwortlich für alle Aspekte des Software Prototypen und insbesondere für Veränderungsvorschläge. Die Veränderungen am Software Prototypen finden in einer Versions-kontrollierten Umgebung (“git”) statt, damit die Hypothesen korrekt gegen spezifische Versionen getestet werden können.
Arbeitsort ist entweder Baar (in den modernen Büroräumlichkeiten der Kopanyo AG an der Schochenmühlestrasse 4) oder wahlweise in den Räumlichkeiten der HSLU. Die Räumlichkeiten müssen ein konzentriertes, stilles Arbeiten in moderner Umgebung erlauben.

### Verwandte Projekte und Abgrenzung
Seit einigen Jahren werden “verteilte Anwendungen” intensiv auf verschiedenen Ebenen diskutiert. Ob dies nun eine verteilte Börse für Krypto-Anlagen (z.B. “bisq”) oder ein verteiltes soziales Netzwerk (z.B. “solid”) darstellt.
In diesem Kontext rücken dann oft auch rechtliche Fragestellungen ins Zentrum, unter anderem die Fragestellung nach der Rechtmässigkeit einer spezifischen Technologie. In diesem Projekt spielen rechtliche Fragestellungen jedoch keine Rolle. 
Alle bestehenden Projekte, welche in irgendeiner Form eine zentrale Stelle aufweisen (eine zentrale ökonomische Einheit, eine Form von zentraler Regulation oder ein zentraler technischer Standard), können per Definition nicht mit diesem Projekt verwandt sein.

## Ziel der Arbeit und erwartete Resultate
Versuche zur Falsifikation der Hypothesen sind das Ziel der Arbeit.
Als Resultat wird ein Dokument erwartet, welches die folgenden Themenkreise vertieft behandelt:
1. Beschreibung der Ausgangslage und Voraussetzungen sowie der unterschiedlichen Versuchsanordnungen
2. Durchführung der Versuchsreihen und deren Resultate
3. Konklusion

## Gewünschte Methoden, Vorgehen
Dieses Projekt hat einen wissenschaftlichen Charakter. Im Vordergrund steht ein empirisches Vorgehen. Die gemeinsam definierten Hypothesen werden getestet um diese zu falsifizieren.

## Kreativität, Varianten, Innovation
Die empirischen Tests der Hypothesen stehen in einer Wechselwirkung mit der Weiterentwicklung des Software Prototypen.
Im Rahmen der These des Projektes sind alle Ideen und Varianten willkommen. Inwiefern spezifische empirische Vorgehensweisen (z.B. offensive Netzwerk-Tests) in diesem Projekt ethisch akzeptabel sind, wird in einem kurzen “Manifest”/“Code of Conduct” zu Beginn gemeinsam festgelegt. 

### Kein Tagesgeschäft
Da das Projekt ein wissenschaftliches Forschungsprojekt ist, hat es nichts mit dem Tagesgeschäft zu tun.

### Innovation in Reinform
Gemäss Wissensstand der Projektauftraggeber existiert per Mai 2019 kein “vollständig dezentrales und nicht-diskriminierendes Handelssystem für digitale Werte mit einer hinreichend Privatsphäre-schützenden Architektur”. Es ist Neuland.

## Schlagwörter
verteiltes System, dezentrales Netzwerk, Blockchain, digitale Werte, Krypto-Anlagen, Kryptographie, Handelssystem, Börse, I2P, Privatsphäre, Anonymität
Wirtschaftsprojekt oder Bachelorarbeit
Für die Auftraggeberin ist beides möglich.

## Projektart und Schwerpunkte
Es ist ein “Innovationsprojekt/Forschungsprojekt” mit den Schwerpunkten “Security/Privacy” sowie “Software-Erstellung”.
Auftraggeberin

### Unternehmen
Kopanyo AG, Carolyn Bächler-Schenk, CEO, Schochenmühlestrasse 4, CH-6340 Baar, https://www.kopanyo.com

Zwischen der Kopanyo AG und HSLU besteht kein Kontakt für diese spezifische Projektidee.

### Über die Autoren dieser Projektidee
Die Autoren dieser Projektidee sind Konrad Bächler und Carolyn Bächler-Schenk. Sie verfügen über jahrelange Erfahrung als Unternehmer, Softwareentwickler und Innovatoren.

#### Carolyn Bächler-Schenk
https://www.linkedin.com/in/carolyn-baechler-schenk

#### Konrad Bächler
* lic. oec. publ. Uni Zürich, abgeschlossen 12.1997 mit cum laude. Liz-Arbeit: Fixed Income Instruments with Embedded Options.
* Stationen: Schweizer Börse, Hugin/ThomsonReuters, Gründer und Unternehmer ab 2003: Entwickler/Architekt von https://marCo.ch, erfolgreicher Unternehmensverkauf der Tensid AG (rund 16 Mitarbeiter) im 2015.
* Gewinner Innovationspreis Kanton Zug, 2011: https://www.luzernerzeitung.ch/zentralschweiz/zug/zuger-innvationspreis-2011-geht-an-tensid-ld.38155
* Software-Entwickler seit >30 Jahren (Sprachen: Assembler, C/C++, Pascal, PHP, JS, SQL, HTML/CSS; OS: Linux). Expertenstatus im Bereich Softwarearchitektur/Microservices/API, modernes PHP (OO), zugehörige Test-Frameworks, persistente Datenspeicherung mit ORMs und Linux. Entwickler eigener sehr fortgeschrittener Backend-Frameworks und eines eigenen ORM für den Einsatz im Bereich hochfrequenter Datenverarbeitung (Forschungsprojekt: verteilte Kryptobörse).
* Einige öffentliche Referate u.a. an der Verleihung Jungunternehmerpreis 2012 in Zug zum Thema "Datenmissbrauch durch Cloud-Dienste", 2016 zum Thema TOR/I2P/Darknet in Zug im Rahmen des Technologieforums Zug oder 2017 zum Thema "Support Vector Models (Machine Learning)" ebenfalls für das Technologieforum Zug
* Aktuelle Tätigkeitsgebiete Forschungsprojekte in der Firma "Kopanyo AG" (https://kopanyo.com): Hochfrequente Datenverarbeitung in Kombination mit "distributed computing"/"peer-to-peer", Anonymisierung, Monero (Kryptowährung)

