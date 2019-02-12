---
title: stabilize
has_children: false
nav_order: 3
---

[64 bit](https://s3.amazonaws.com/releases.bitfactory.at.{{page.title}}/ALEX64.zip){: .btn .mr-2 }

### [2019.06](https://github.com/bitfactory-software/alex/milestone/36) Personal Cockpit (Stempeln beim Login, Login Performance), Genehmigergruppe
___

2019.5.99.3 **08.02.2019** ***MERGE*** 2019.4.0.2

2019.5.99.2 **05.02.2019** ***MERGE*** 2019.4.0.1

2019.5.99.1 **04.02.2019**
> fix: [#2164](https://github.com/bitfactory-software/alex/issues/2164) Genehmigungsverfahren - "Unbekannter Fehler" beim genehmigen

2019.5.99.0 **04.02.2019**
> Stabilisieren

2019.5.90.25 **04.02.2019** ***MERGE*** 2019.3.99.15
> fix: "Unbekannten Fehler" + Absturz behoben beim bearbeiten vom TCX/XML vor dem Login

2019.5.90.24 **31.01.2019**
> fix Autotests

2019.5.90.23 **31.01.2019**
> fix [#213](https://github.com/bitfactory-software/alex/issues/213) Backup erstellen händisch anfordern
>> neben Configfile ein File hinlegen das "**mustBackup**" heißt, dann wird eine aktuelle Sicherung gemacht.
> fix [#512](https://github.com/bitfactory-software/alex/issues/512) command "Fadenkreuz" im Web ausblenden
> fix [#628](https://github.com/bitfactory-software/alex/issues/628) Absturz Monatsplan öffnen / benachbarte Wochen / bestimmte Besetzungsansicht

2019.5.90.22 **29.01.2019**
> fix [#2109](https://github.com/bitfactory-software/alex/issues/2109) Darstellung bei mehreren Stundenweisen Planungscodes am Tag

2019.5.90.21 **29.01.2019** ***MERGE*** 2019.3.99.14

2019.5.90.20 **28.01.2019** ***MERGE*** 2019.3.99.13

2019.5.90.19 **28.01.2019**
> fix [#2126](https://github.com/bitfactory-software/alex/issues/2126) Protokoll für "steuernde" Objekte einschalten

2019.5.90.18 **25.01.2019** ***MERGE*** 2019.3.99.12

2019.5.90.17 **25.01.2019**
> fix: [#1953](https://github.com/bitfactory-software/alex/issues/1953) Workaround - Kalender/Besetzungsansicht Dienst mit Hintergrunddienst wird nur gezählt wenn Hintergrunddienst nicht auch bei einem anderem Dienst eingetragen ist
> neu: [#2121](https://github.com/bitfactory-software/alex/issues/2121) Eigenschaft importieren - Import von Benutzer-Passwörtern

2019.5.90.16 **24.01.2019**
> fix: [#1431](https://github.com/bitfactory-software/alex/issues/1431) fromUTF8 Konvertierung, üÜöÖ wurden zu '?' in Linux
> fix: [#2105](https://github.com/bitfactory-software/alex/issues/2105) TestUTF8File, test( "ansi1252.txt", ... ) aktiviert für Linux
> fix: Einige weitere Probleme mit CP1252 Kodierung in Linux behoben

2019.5.90.15 **21.01.2019** ***MERGE*** 2019.3.99.11
> keine Änderung durch MERGE - bugfix war bereits durch 2019.5.90.14 enthalten

2019.5.90.14 **21.01.2019** ***MERGE*** 2019.3.99.9+10
> MERGE + bugfix "undo unintended changes, #2106 [fc7a11c](https://github.com/bitfactory-software/alex/commit/fc7a11c35a072bea60506b21911f992a59f8578d)

2019.5.90.13 **17.01.2019**
> bugfix: [#1952](https://github.com/bitfactory-software/alex/issues/1952) (für Doppler)
>> Hintergrund-Dienste müssen bei Berechnung von Konto "Soll laut Wochentag" bzw. "Soll laut Wochentag am Feiertag" ignoriert werden

2019.5.90.12 **15.01.2019** ***MERGE*** 2019.3.99.8

2019.5.90.11 **15.01.2019**
> fix: nochmal [#1934](https://github.com/bitfactory-software/alex/issues/1934) 7Up: AZG Woche im Schnitt: Schwerer Fehler wenn Austritt am 1. Tag des DRZ

2019.5.90.10 **11.01.2019** ***MERGE*** 2019.3.99.7

2019.5.90.9 **11.01.2019**
> fix: [#1934](https://github.com/bitfactory-software/alex/issues/1934) 7Up: AZG Woche im Schnitt: Schwerer Fehler wenn Austritt am 1. Tag des DRZ
> fix: [#1905](https://github.com/bitfactory-software/alex/issues/1905) 7Up: AZG-Prüfung (17Wo/48Std) Anzeige

2019.5.90.8 **10.01.2019** ***MERGE*** 2019.3.99.6

2019.5.90.7 **10.01.2019**
> neu: [#1828](https://github.com/bitfactory-software/alex/issues/1828) Wer darf wen genehmigen? (neuer Versuch)
> neu: [#2092](https://github.com/bitfactory-software/alex/issues/2092) Genehmigergruppe: Als Basis für Dia-genehmigungsverfahren

2019.5.90.6 **08.01.2019**
> fix: 7Up "Soll laut Wochentag" berücksichtigt jetzt auch Rahmenplan
> neu: [#1952](https://github.com/bitfactory-software/alex/issues/1952) neues Konto "Soll laut Wochentag am Feiertag"

2019.5.90.5 **07.01.2019** ***MERGE*** 2019.3.99.5

2019.5.90.4 **07.01.2019** ***MERGE*** 2019.3.99.4

2019.5.90.3 **03.01.2019** ***MERGE*** 2019.3.99.3

2019.5.90.2 **03.01.2019**
> fix: [#2019](https://github.com/bitfactory-software/alex/issues/2019) ÖAMTC Wien: Tagesüberstunden + Feiertag passen noch nicht

2019.5.90.1 **03.01.2018** ***MERGE*** 2019.3.99.1

2019.5.90.0 **02.01.2019**
> Init
