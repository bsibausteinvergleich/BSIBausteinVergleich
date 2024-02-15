# Übersicht der Änderungen des IT-Grundschutz-Kompendiums von Version 2022 zu 2023


Bei der Fortschreibung des Kompendiums Edition 2023 wurde geschlechterneutrale Sprache in das Kompendium eingeführt. Dadurch ergeben sich faktisch in jedem Baustein Änderungen, ohne dass inhaltliche Änderungen in den Anforderungen vorgenommen worden sind.

Aus Gründen der Lesbarkeit wird auf die Wiederholung der Umstellung auf geschlechterneutrale Sprache bei den Änderungsangaben in den Bausteinen verzichtet.


---


## Änderungen ISMS.1

Keine inhaltlichen Änderungen.


---


## Änderungen CON

### Änderungen CON.1

Der Baustein spricht jetzt an mehreren Stellen von *Informationen* statt von *Daten*.

Anstatt von *Kryptoprodukten* spricht der Baustein nun von *Hard- oder Software mit kryptografischen Funktionen*.


#### CON.1.A1:

##### Hinzugefügt:

Um eine geeignete Schlüssellänge auszuwählen, SOLLTE berücksichtigt werden, wie lange das kryptografische Verfahren eingesetzt werden soll.

Bei einer längeren Einsatzdauer SOLLTEN entsprechend längere Schlüssellängen eingesetzt werden.


#### CON.1.A2:

##### Entfernt:

Verwendete Kryptoprodukte SOLLTEN archiviert werden.

##### Geändert:

Langlebige kryptografische Schlüssel MÜSSEN offline, außerhalb der eingesetzten IT-Systeme, aufbewahrt werden.


#### CON.1.A3 entfallen

Ehemals *Verschlüsselung der Kommunikationsverbindungen*:

*Es SOLLTE geprüft werden, ob mit vertretbarem Aufwand eine Verschlüsselung der Kommunikationsverbindungen möglich und praktikabel ist.*

*Ist dies der Fall, SOLLTEN Kommunikationsverbindungen geeignet verschlüsselt werden.*


#### CON.1.A4 ist jetzt Basis-Anforderung anstatt Standard-Anforderung

##### Hinzugefügt:

In einem geeigneten Schlüsselmanagement für kryptografische Hard oder Software MUSS festgelegt werden, wie Schlüssel und Zertifikate erzeugt, gespeichert, ausgetauscht und wieder gelöscht oder vernichtet werden.

Es MUSS ferner festgelegt werden, wie die Integrität und Authentizität der Schlüssel sichergestellt wird.

In Hard- oder Software mit kryptografischen Funktionen SOLLTEN voreingestellte Schlüssel (ausgenommen öffentliche Zertifikate) ersetzt werden.

Geheime Schlüssel MÜSSEN sicher gespeichert und vor unbefugtem Zugriff geschützt werden.

Grundsätzlich SOLLTE geregelt werden, wie mit abgelaufenen Schlüsseln und damit verbundenen Signaturen verfahren wird.

Falls die Gültigkeit von Schlüsseln oder Zertifikaten zeitlich eingeschränkt wird, dann MUSS durch die Institution sichergestellt werden, dass die zeitlich eingeschränkten Zertifikate oder Schlüssel rechtzeitig erneuert werden.

Eine Vorgehensweise SOLLTE für den Fall festgelegt werden, dass ein privater Schlüssel offengelegt wird.

##### Geändert:


Kryptografische Schlüssel SOLLTEN mit sicher geltenden Verfahren ausgetauscht werden.

Wenn öffentliche Schlüssel von Dritten verwendet werden, MUSS sichergestellt sein, dass die Schlüssel authentisch sind und die Integrität der Schlüsseldaten gewährleistet ist.

Eine Vorgehensweise SOLLTE für den Fall festgelegt werden, dass ein privater Schlüssel offengelegt wird.


#### CON.1.A5

##### Hinzugefügt:

Die Vorgehensweisen und eingesetzten Methoden, um nicht mehr benötigte private Schlüssel zu löschen oder zu vernichten, SOLLTEN im Kryptokonzept dokumentiert werden.


#### CON.1.A6 entfallen

Ehemals *Bedarfserhebung für kryptografische Verfahren und Produkte*:

*Es SOLLTE festgelegt werden, für welche Geschäftsprozesse oder Fachverfahren kryptografische Verfahren eingesetzt werden sollen.*

*Danach SOLLTEN die Anwendungen, IT-Systeme und Kommunikationsverbindungen identifiziert werden, die notwendig sind, um die Aufgaben zu erfüllen.*

*Diese SOLLTEN durch den IT-Betrieb geeignet kryptografisch abgesichert werden.*


#### CON.1.A7 entfallen

Ehemals *Erstellung einer Sicherheitsrichtlinie für den Einsatz kryptografischer Verfahren und Produkte*:


*Ausgehend von der allgemeinen Sicherheitsrichtlinie der Institution SOLLTE eine spezifische Richtlinie für den Einsatz von Kryptoprodukten erstellt werden.*

*In der Sicherheitsrichtlinie SOLLTE geregelt werden, wer für den sicheren Betrieb der kryptografischen Produkte zuständig ist.*

*Für die benutzten Kryptoprodukte SOLLTE es Vertretungsregelungen geben.*

*Auch SOLLTEN notwendige Schulungs- und Sensibilisierungsmaßnahmen für Benutzer sowie Verhaltensregeln und Meldewege bei Problemen oder Sicherheitsvorfällen festgelegt werden.*

*Weiter SOLLTE die Richtlinie definieren, wie sichergestellt wird, dass Kryptomodule sicher konfiguriert, korrekt eingesetzt und regelmäßig gewartet werden.*

*Die Richtlinie SOLLTE allen relevanten Mitarbeitern bekannt und grundlegend für ihre Arbeit sein.*

*Wird die Richtlinie verändert oder wird von ihr abgewichen, SOLLTE dies mit dem ISB abgestimmt und dokumentiert werden.*

*Es SOLLTE regelmäßig überprüft werden, ob die Richtlinie noch korrekt umgesetzt wird.*

*Die Ergebnisse SOLLTEN sinnvoll dokumentiert werden.*


#### CON.1.A8 entfallen

Ehemals *Erhebung der Einflussfaktoren für kryptografische Verfahren und Produkte*:


*Bevor entschieden werden kann, welche kryptografischen Verfahren und Produkte bei erhöhtem Schutzbedarf eingesetzt werden, SOLLTEN unter anderem folgende Einflussfaktoren ermittelt werden:*

*• Sicherheitsaspekte (siehe CON.1.A6 Bedarfserhebung für kryptografische Verfahren und Produkte),*

*• technische Aspekte,*

*• personelle und organisatorische Aspekte,*

*• wirtschaftliche Aspekte,*

*• Lebensdauer von kryptografischen Verfahren und der eingesetzten Schlüssellängen,*

*• Zulassung von kryptografischen Produkten sowie*

*• gesetzliche Rahmenbedingungen.*


#### CON.1.A9 ist jetzt Standard-Anforderung anstatt Anforderung mit erhöhtem Schutzbedarf

##### Umbenannt in:

Festlegung von Kriterien für die Auswahl von Hard- oder Software mit kryptografischen Funktionen

War vorher: *Auswahl eines geeigneten kryptografischen Produkts*

Inhalt grundlegend verändert, auf eine Auflistung wird verzichtet, beinhaltet auch Inhalte aus der nun entfallenen A8.


#### CON.1.A10 ist jetzt Standard-Anforderung anstatt Anforderung mit erhöhtem Schutzbedarf

Inhalt grundlegend verändert, auf eine Auflistung wird verzichtet.


#### CON.1.A15 ist jetzt Standard-Anforderung anstatt Anforderung mit erhöhtem Schutzbedarf

Inhalt grundlegend verändert, auf eine Auflistung wird verzichtet.


#### CON.1.A19 vollständig neu hinzugefügt als Standard-Anforderung


#### CON.1.A11

Inhalt grundlegend verändert, auf eine Auflistung wird verzichtet.


#### CON.1.A12 entfallen

Ehemals *Sichere Rollenteilung beim Einsatz von Kryptomodulen*:

*Bei der Konfiguration eines Kryptomoduls SOLLTEN Benutzerrollen festgelegt werden.*

*Es SOLLTE mit Zugriffskontroll- und Authentisierungsmechanismen verifiziert werden, ob ein Mitarbeiter den gewünschten Dienst auch tatsächlich benutzen darf.*

*Das Kryptomodul SOLLTE so konfiguriert sein, dass bei jedem Rollenwechsel oder bei Inaktivität nach einer bestimmten Zeitdauer die Authentisierungsinformationen erneut eingegeben werden müssen.*


#### CON.1.A13 entfallen

Ehemals *Anforderungen an die Betriebssystem-Sicherheit beim Einsatz von Kryptomodulen*:


*Das Zusammenwirken von Betriebssystem und Kryptomodulen SOLLTE gewährleisten, dass*

*• die installierten Kryptomodule nicht unbemerkt abgeschaltet oder umgangen werden können,*

*• die angewendeten oder gespeicherten Schlüssel nicht kompromittiert werden können,*

*• die zu schützenden Daten nur mit Wissen und unter Kontrolle des Benutzers auch unverschlüsselt auf Datenträgern abgespeichert werden bzw. das informationsverarbeitende System verlassen können sowie*

*• Manipulationsversuche am Kryptomodul erkannt werden.*


#### CON.1.A14 entfallen

Ehemals *Schulung von Benutzern und Administratoren*:

*Es SOLLTE Schulungen geben, in denen Benutzern und Administratoren der Umgang mit den für sie relevanten Kryptomodulen vermittelt wird.*

*Den Benutzern SOLLTE genau erläutert werden, was die spezifischen Sicherheitseinstellungen von Kryptomodulen bedeuten und warum sie wichtig sind.*

*Außerdem SOLLTEN sie auf die Gefahrenhingewiesen werden, die drohen, wenn diese Sicherheitseinstellungen aus Bequemlichkeit umgangen oder deaktiviert werden.*

*Die Schulungsinhalte SOLLTEN immer den jeweiligen Einsatzszenarien entsprechend angepasst werden.*

*Die Administratoren SOLLTEN zudem gezielt dazu geschult werden, wie die Kryptomodule zu administrieren sind.*

*Auch SOLLTEN sie einen Überblick über kryptografische Grundbegriffe erhalten.*


#### CON.1.A16

##### Geändert:

*Im Kryptokonzept SOLLTE festgelegt werden, wie der IT-Betrieb sicherstellt, dass nicht unautorisiert physisch auf Hardware mit kryptografischen Funktionen zugegriffen werden kann.*


##### Entfallen:

*Hard- und Softwareprodukte, die als Kryptomodule eingesetzt werden, SOLLTEN einen Selbsttest durchführen können.*


#### CON.1.A17

##### Entfallen:

*Getroffene Maßnahmen hinsichtlich der Abstrahlsicherheit SOLLTEN im Kryptokonzept dokumentiert werden.*


#### CON.1.A18

##### Geändert:

*Hardware mit kryptografischen Funktionen (z. B. Hardware-Token für Zwei-Faktor-Authentifizierung) SOLLTE vorrätig sein.*

*Im Kryptokonzept SOLLTE dokumentiert werden, für welche Hardware mit kryptografischen Funktionen Ersatzhardware zur Verfügung steht und wie diese ausgetauscht werden kann.*


#### CON.1.A20 vollständig neu hinzugefügt als Anforderung mit erhöhtem Schutzbedarf


### CON.2

#### CON.2.A1

##### Geändert:

Die gesetzlichen Bestimmungen zum Datenschutz (DSGVO, BDSG, die Datenschutzgesetze der Bundesländer und gegebenenfalls einschlägige bereichsspezifische Datenschutzregelungen) MÜSSEN eingehalten werden.


### CON.3

Keine inhaltlichen Änderungen.


### CON.6

Keine inhaltlichen Änderungen.


### CON.7

Keine inhaltlichen Änderungen.


### CON.8

Keine inhaltlichen Änderungen.


### CON.9

Keine inhaltlichen Änderungen.


### CON.10

Keine inhaltlichen Änderungen.


### CON.11.1 wurde neu hinzugefügt.

---


## ORP

### ORP.1

#### ORP.1.A17

Die Anforderung wurde neu hinzugefügt.


### ORP.2

Keine inhaltlichen Änderungen.


### ORP.3

Keine inhaltlichen Änderungen.


### ORP.4

Keine inhaltlichen Änderungen.


### ORP.5

Keine inhaltlichen Änderungen.


---

## SYS

### SYS.1.1

#### SYS.1.1.A1

##### Geändert:

*Physische Server MÜSSEN an Orten betrieben werden, zu denen nur berechtigte Personen Zutritt haben.*

*Physische Server MÜSSEN daher in Rechenzentren, Serverräumen oder abschließbaren Serverschränken aufgestellt beziehungsweise eingebaut werden (siehe hierzu die entsprechenden Bausteine der Schicht INF Infrastruktur).*


##### Neu:

*Bei virtualisierten Servern MUSS der Zugriff auf die Ressourcen der Instanz und deren Konfiguration ebenfalls auf die berechtigten Personen begrenzt werden.*

*Server DÜRFEN NICHT zur Erledigung von Aufgaben und Tätigkeiten verwendet werden, die grundsätzlich auf einem Client-System aus- und durchgeführt werden können.*

*Insbesondere DÜRFEN vorhandene Anwendungen, wie Webbrowser, auf dem Server NICHT für das Abrufen von Informationen aus dem Internet oder das Herunterladen von Software, Treibern und Updates verwendet werden.*


#### SYS.1.1.A6

##### Geändert:

*Alle nicht benötigten Serverrollen, Features und Funktionen, sonstige Software und Dienste MÜSSEN deaktiviert oder deinstalliert werden, vor allem Netzdienste.*


##### Neu:

*Die Empfehlungen des Betriebssystemherstellers SOLLTEN hierbei als Orientierung berücksichtigt werden.*


#### SYS.1.1.A16

Grundlegend geändert, Inhalt nahezu vollständig neu.


#### SYS.1.1.A39

Anforderung neu als Standard-Anforderung hinzugekommen.


### SYS.1.2.3

Der Baustein wurde neu hinzugefügt.


### SYS.1.3

Keine inhaltlichen Änderungen.


### SYS.1.5

Keine inhaltlichen Änderungen.


### SYS.1.6

#### SYS.1.6.A6

##### Neu:

*Die Quelle MUSS diesen Umgang mit Sicherheitsproblemen zusichern und einhalten.*


### SYS.1.7

Keine inhaltlichen Änderungen.


### SYS.1.8

Keine inhaltlichen Änderungen.


### SYS.1.9

Der Baustein wurde neu hinzugefügt.


### SYS.2.1

#### SYS.2.1.A11

##### Neu (aus entfallener Anforderung SYS.2.1.A14 übernommen):

*Auf Betriebssysteme, die über ein Rolling-Release-Modell aktualisiert werden, SOLLTE verzichtet werden.*


#### SYS.2.1.A14 ist entfallen.

Ehemals *Updates und Patches für Firmware, Betriebssystem und Anwendungen*.

*Auf Betriebssysteme, die über ein Rolling-Release-Modell aktualisiert werden, SOLLTE verzichtet werden.*

*Es SOLLTEN NUR Anwendungsprogramme ausgewählt und installiert werden, für die Support angeboten wird.*

*Betriebssysteme, Anwendungsprogramme und Firmware, für die keine regelmäßigen Sicherheitsupdates angeboten werden, DÜRFEN NICHT eingesetzt werden.*


### SYS.2.2.3

Jetzt für alle Windows Client Betriebssysteme gültig, nicht mehr nur Windows 10.

#### SYS.2.2.3.A4

##### Geändert:

*Um die Übertragung von Diagnose- und Nutzungsdaten an Microsoft stark zu reduzieren, MUSS das Telemetrie-Level 0 (Security) in der Enterprise-Edition von Windows konfiguriert werden.*

*Wenn diese Einstellung nicht wirksam umgesetzt wird oder bei anderen Windows-Edition umgesetzt werden kann, dann MUSS durch geeignete Maßnahmen, etwa auf Netzebene, sichergestellt werden, dass die Daten nicht an den Hersteller übertragen werden.*


#### SYS.2.2.3.A19

##### Geändert:

*Die eingesetzten kryptografischen Protokolle und Algorithmen SOLLTEN sicher sein und den internen Vorgaben der Institution entsprechen.*


#### SYS.2.2.3.A26

Die Anforderung wurde neu hinzugefügt.


### SYS.2.3

Keine inhaltlichen Änderungen.


### SYS.2.4

Keine inhaltlichen Änderungen.


### SYS.2.5

Der Baustein wurde neu hinzugefügt.


### SYS.2.6

Der Baustein wurde neu hinzugefügt.


### SYS.3.1

Keine inhaltlichen Änderungen.


### SYS.3.2.1

Keine inhaltlichen Änderungen.


### SYS.3.2.2

Keine inhaltlichen Änderungen.


### SYS.3.2.3

Keine inhaltlichen Änderungen.


### SYS.3.2.4

Keine inhaltlichen Änderungen.


### SYS.3.3

Keine inhaltlichen Änderungen.


### SYS.4.1

Keine inhaltlichen Änderungen.


### SYS.4.3

#### SYS.4.3.A1

##### Entfallen:

*Um eingebettete Systeme reibungslos zu betreiben, MÜSSEN Zuständige ernannt werden.*

##### Neu:

*Alle eingebetteten Systeme inklusive Schnittstellen MÜSSEN erfasst werden.*


#### SYS.4.3.A11

##### Neu:

*Ist dies nicht möglich, SOLLTE das System vernichtet werden.*


### SYS.4.4

Keine inhaltlichen Änderungen.


### SYS.4.5

#### SYS.4.5.A2

##### Neu:

*Die Institution MUSS festlegen, wie Wechseldatenträger behandelt werden sollen, die nach einem Verlust wiedergefunden wurden.*

*Wiedergefundene Wechseldatenträger DÜRFEN NICHT ohne vorherige Überprüfung auf Manipulation und Schadsoftware verwendet werden.*


#### SYS.4.5.A4

##### Entfallen:

*ob und wie private Datenträger genutzt werden dürfen,*


##### Neu:

*ob Wechseldatenträger an fremde IT-Systeme angeschlossen werden dürfen und was dabei zu beachten ist,*

*Die Institution SOLLTE die Verwendung von privaten Wechseldatenträgern untersagen.*


#### SYS.4.5.A17 Neue Standard-Anforderung

*Falls Wechseldatenträger verwendet werden, um Daten für lange Zeiträume zu speichern, SOLLTE die Institution sicherstellen, dass die verwendeten Wechseldatenträger geeignet sind, um die Integrität und Verfügbarkeit der Daten während des gesamten Nutzungszeitraums sicherzustellen.*

*Die Integrität der Daten SOLLTE regelmäßig überprüft werden.*


---


## NET

Bei allen NET-Bausteinen finden sich keinerlei inhaltliche Änderungen.


### NET.3.4 Network Access Control (NAC)

Der Baustein wurde neu hinzugefügt.


---


Quellen:


[BSI IT Grundschutz Kompendium Edition 2022](https://www.bsi.bund.de/SharedDocs/Downloads/DE/BSI/Grundschutz/Kompendium/IT_Grundschutz_Kompendium_Edition2022.pdf)


[BSI IT Grundschutz Kompendium Edition 2023](https://www.bsi.bund.de/SharedDocs/Downloads/DE/BSI/Grundschutz/Kompendium/IT_Grundschutz_Kompendium_Edition2023.pdf)



