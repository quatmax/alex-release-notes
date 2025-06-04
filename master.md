---
title: master
has_children: false
nav_order: 2
wiki: https://alex-wiki.bitfactory.at/index.php/
s3: https://s3.amazonaws.com/releases.bitfactory.at.
github: https://github.com/bitfactory-software/alex/
issue: https://github.com/bitfactory-software/alex/issues
merge: <b class="d-inline-block p-2 mr-1 v-align-middle bg-grey-lt-300">Merge</b>
---

[64 bit]({{page.s3}}{{page.title}}/ALEX64.zip){: .btn .mr-2 }
[32 bit]({{page.s3}}{{page.title}}/ALEX32.zip){: .btn .mr-2 }

### [2025.06]({{page.github}}milestone/32) Irgendeine Beschreibung
___

2025.6.0.0 **04.06.2025**
>fix: [#2197]({{page.issues}}/11558) "Hauptseite" funktioniert nicht mehr


### [2019.04]({{page.github}}milestone/32) Regression Tests für Exports, Planer Cockpit
___

2019.4.0.3 **14.02.2019**
>fix: [#2197]({{page.github}}issues/2197) Upgrade auf VC 15.9.7: mögliche Abstürze durch alte Compilerversion 

2019.4.0.2 **08.02.2019**
>fix: [#2174]({{page.github}}issues/2174) Nach wechsel im Reiter, Dienst einer anderen PE kann eingetragen werden (Poolzuteilung) 

2019.4.0.1 **05.02.2019**
>fix: [#2166]({{page.github}}issues/2166) Absturz 32bit Version beim durchrechnen 

2019.4.0.0 **04.02.2019**
> Release

2019.3.99.15 **04.02.2019**
> fix: [#2152]({{page.github}}issues/2152) Personal Cockpit App, Initiale Daten können veraltet sein 

2019.3.99.14 **29.01.2019**
> neu: [#1906]({{page.github}}issues/1906)[#1907]({{page.github}}issues/1907) Schaltfläche "..." für Windows Stempeluhr zum öffnen der Bildschirmtastatur 

2019.3.99.13 **28.01.2019** {{page.merge}} 2019.2.0.7

2019.3.99.12 **25.01.2019**
> fix: [#2132]({{page.github}}issues/2132) Memory Leak in Computation!

2019.3.99.11 **22.01.2019** {{page.merge}} 2019.2.0.6

2019.3.99.10 **21.01.2019** {{page.merge}} 2019.2.0.5

2019.3.99.9 **18.01.2019**
> fix: [#2111]({{page.github}}issues/2111) Cockpit App, Wenn Abwesenheit gestempelt --> wird das Kommt/Geht vertauscht (v0.0.35)

2019.3.99.8 **15.01.2019** {{page.merge}} 2019.2.0.4

2019.3.99.7 **11.01.2019**
> neu: [#2075]({{page.github}}issues/2075) WebAssembly Offline-fähige Stempeluhr ausliefern
>> Stempeluhr Offline-fähig(Stempeln wenn ALEX Server gestoppt) solange Seite offen bleibt, Seite neu laden oder Browser neu öffnen wird auch diese Stempeluhr vermutlich nicht überleben
>> Erreichbar über Link(z.B.: CRM): https://alex.bitfactory.at:43000/wasm/Recorder/App.html

2019.3.99.6 **10.01.2019**
> neu: [#2089]({{page.github}}issues/2089) bfx_RecomputeLog: beim Einchecken gehen Ordner "...AbsencesExportRef" u. "...WageAccountingExportRef" verloren

2019.3.99.5 **07.01.2019** {{page.merge}} 2019.2.0.3

2019.3.99.4 **07.01.2019**
> neu: [#1987]({{page.github}}issues/1987) - Unterstützung für neueste Personal Cockpit App Version

2019.3.99.3 **03.01.2019** {{page.merge}} 2019.2.0.2

2019.3.99.2 **03.01.2019**
> fix: [#2067]({{page.github}}issues/2067) Planer Cockpit: Es werden nicht alle Anträge aus GV aus Vergangenheit angezeigt
> fix: [#2063]({{page.github}}issues/2063) Planer Cockpit: Unbekannter Fehler bei Stornoantrag

2019.3.99.1 **03.01.2019** {{page.merge}} 2019.2.0.1

2019.3.99.0 **02.01.2019**
> wird stabilisiert

2019.3.90.29 **29.12.2018**
> fix: [#2046]({{page.github}}issues/2046) "Fehlermarkierung: Planungscode ersetzen" funktioniert nicht

2019.3.90.28 **29.12.2018**
> fix: [#2025]({{page.github}}issues/2025) Änderung von WZM - genehmigter Urlaub bleibt mit "altem" Dienst stehen

2019.3.90.27 **28.12.2018**
> fix für Bfx.Alex.Model.TestAbsencesExport auf linux

2019.3.90.26 **20.12.2018**
> fix: [#2052]({{page.github}}issues/2052) Bfx.Run.ReferenceDBs - RegDB's nutzten Prozessor nicht mehr anständig aus

2019.3.90.25 **17.12.2018**
> fix: [#2043]({{page.github}}issues/2043) Personalstand in Echtzeit: farbliche Hervorhebung von Anwesenheit

2019.3.90.24 **17.12.2018**
> fix: [#1948]({{page.github}}issues/1948) Planer Cockpit: Personalstand in Echtzeit

2019.3.90.23 **16.12.2018**
> fix: [GCC compile-error]({{page.github}}commit/2e204f780cee804bfceeb7062e1f10f7cacebf37)

2019.3.90.22 **16.12.2018**
> fix: [GCC compile-error]({{page.github}}commit/746184014d0a36bfff05d53ebaadff80b9346194)

2019.3.90.21 **14.12.2018**
> neue Option im [Config]({{page.wiki}}ALEX-Config-File) `"logging" : { "manualTimeStampProcessor" : "true" }`

2019.3.90.20 **14.12.2018** {{page.merge}} 2019.1.99.12

2019.3.90.19 **13.12.2018**
> fix: [#2037]({{page.github}}issues/2037) "Testfall kopieren": unbekannter Fehler bei untermonatigem Ein-/Austritt
> fix: [#2040]({{page.github}}issues/2040) remove unused code "ForeachOutputElem"

2019.3.90.18 **13.12.2018**
> fix: [#2034]({{page.github}}issues/2034) source\.vs Ordner sollte nicht unter Sourcecodeverwaltung sein
> fix: [#2032]({{page.github}}issues/2032) Http Server muss Url decodieren
> fix: [#1735]({{page.github}}issues/1735) Anlage von Abschlussbuchungen: Anzeig nicht vollständig, sieht aus als ob nichts hinterlegt wäre

2019.3.90.17 **13.12.2018** {{page.merge}} 2019.1.99.11

2019.3.90.16 **12.12.2018**
> fix [#2014]({{page.github}}issues/2014) ..ExportRef != ...ExportTest auf Linux

2019.3.90.15 **12.12.2018** {{page.merge}} 2019.1.99.9

2019.3.90.14 **11.12.2018** {{page.merge}} 2019.1.99.7

2019.3.90.13 **11.12.2018**
> fix: [#1687]({{page.github}}issues/1687) Referenzfall duplizieren mit alles (Personal, einzeln oder multiselect)
> fix: [#1688]({{page.github}}issues/1688) Referenz-Plan duplizieren

2019.3.90.12 **10.12.2018**
> fix: [#2016]({{page.github}}issues/2016) ÖAMTC Wien: "Wochenfehler markieren mit" auf Vertrag benötigt

2019.3.90.11 **10.12.2018**
> fix: [#2015]({{page.github}}issues/2015) Planer Cockpit: Genehmigung direkt im Cockpit -> Anträge bleiben stehen
> fix: [#2008]({{page.github}}issues/2008) Planer Cockpit: sehe alle Planungseinheiten und nicht nur die, die ich unter Monatsplansuche sehe

2019.3.90.10 **10.12.2018**
> fix zu: [#2009]({{page.github}}issues/2009) Planer Cockpit: Sehe keine offenen Anträge von "nicht erzeugten" Monaten

2019.3.90.9 **10.12.2018** {{page.merge}} 2019.1.99.6

2019.3.90.8 **10.12.2018**
> neu: [#1854]({{page.github}}issues/1854) "Bildschirmeinstellungen" : "Di., Do. u. Samstag mit gleicher Hintergrundfarbe?"

2019.3.90.7 **07.12.2018**
> fix: [#2010]({{page.github}}issues/2010) Planer Cockpit geöffnet -> Eintragen im Dienstplan sehr langsam
> fix: [#2009]({{page.github}}issues/2009) Planer Cockpit: Sehe keine offenen Anträge von "nicht erzeugten" Monaten 

2019.3.90.6 **07.12.2018** {{page.merge}} 2019.1.99.4

2019.3.90.5 **05.12.2018**
> fix: [#1854]({{page.github}}issues/1854) Erweiterungen der "Timeline-Darstellung"

2019.3.90.4 **05.12.2018**
> fix: [#1944]({{page.github}}issues/1944) PlanerCockpit: Bessere Sichtbarkeit der einzelnen Module
> fix: [#1945]({{page.github}}issues/1945) PlanerCockpit-Module: Azg + Zeiterfassung gehen in "Statusübersicht" auf

2019.3.90.3 **05.12.2018**
> fix: [#1829]({{page.github}}issues/1829) Regression Tests für Exports (Lohnarten/Abwesenheiten) 

2019.3.90.2 **04.12.2018** {{page.merge}} 2019.1.99.2

2019.3.90.1 **04.12.2018** {{page.merge}} 2019.1.99.1

2019.3.90.0 **03.12.2018**
> Init
