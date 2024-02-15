# Übersicht der Änderungen des IT-Grundschutz-Kompendiums von Version 2022 zu 2023


Bei der Fortschreibung des Kompendiums Edition 2023 wurde geschlechterneutrale Sprache in das Kompendium eingeführt. Dadurch ergeben sich faktisch in jedem Baustein Änderungen, ohne dass inhaltliche Änderungen in den Anforderungen vorgenommen worden sind.

Aus Gründen der Lesbarkeit wird auf die Wiederholung der Umstellung auf geschlechterneutrale Sprache bei den Änderungsangaben in den Bausteinen verzichtet.


---


## Änderungen ISMS.1

Im ISMS-Baustein befinden sich keine inhaltlichen Änderungen.



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

Im Kryptokonzept SOLLTE festgelegt werden, wie der IT-Betrieb sicherstellt, dass nicht unautorisiert physisch auf Hardware mit kryptografischen Funktionen zugegriffen werden kann.


##### Entfallen:

Hard- und Softwareprodukte, die als Kryptomodule eingesetzt werden, SOLLTEN einen Selbsttest durchführen können.


#### CON.1.A17

##### Entfallen:

Getroffene Maßnahmen hinsichtlich der Abstrahlsicherheit SOLLTEN im Kryptokonzept dokumentiert werden.


#### CON.1.A18

##### Geändert:

Hardware mit kryptografischen Funktionen (z. B. Hardware-Token für Zwei-Faktor-Authentifizierung) SOLLTE vorrätig sein.

Im Kryptokonzept SOLLTE dokumentiert werden, für welche Hardware mit kryptografischen Funktionen Ersatzhardware zur Verfügung steht und wie diese ausgetauscht werden kann.


#### CON.1.A20 vollständig neu hinzugefügt als Anforderung mit erhöhtem Schutzbedarf



Quellen:


[BSI IT Grundschutz Kompendium Edition 2022](https://www.bsi.bund.de/SharedDocs/Downloads/DE/BSI/Grundschutz/Kompendium/IT_Grundschutz_Kompendium_Edition2022.pdf)


[BSI IT Grundschutz Kompendium Edition 2023](https://www.bsi.bund.de/SharedDocs/Downloads/DE/BSI/Grundschutz/Kompendium/IT_Grundschutz_Kompendium_Edition2023.pdf)



