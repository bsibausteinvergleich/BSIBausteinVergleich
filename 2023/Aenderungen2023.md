# Übersicht der Änderungen des IT-Grundschutz-Kompendiums von Version 2022 zu 2023


Bei der Fortschreibung des Kompendiums Edition 2023 wurde geschlechterneutrale Sprache in das Kompendium eingeführt. Dadurch ergeben sich faktisch in jedem Baustein Änderungen, ohne dass inhaltliche Änderungen in den Anforderungen vorgenommen worden sind.

Aus Gründen der Lesbarkeit wird auf die Wiederholung der Umstellung auf geschlechterneutrale Sprache bei den Änderungsangaben in den Bausteinen verzichtet.


---


## ISMS.1

Keine inhaltlichen Änderungen.


---


## CON

### CON.1

<details>
<summary> Änderungen
</summary>

Der Baustein spricht jetzt an mehreren Stellen von *Informationen* statt von *Daten*.

Anstatt von *Kryptoprodukten* spricht der Baustein nun von *Hard- oder Software mit kryptografischen Funktionen*.

#### Basis-Anforderungen

#### CON.1.A1

__Hinzugefügt:__

Um eine geeignete Schlüssellänge auszuwählen, SOLLTE berücksichtigt werden, wie lange das kryptografische Verfahren eingesetzt werden soll.

Bei einer längeren Einsatzdauer SOLLTEN entsprechend längere Schlüssellängen eingesetzt werden.


#### CON.1.A2

__Entfallen:__

Verwendete Kryptoprodukte SOLLTEN archiviert werden.

__Geändert:__

Langlebige kryptografische Schlüssel MÜSSEN offline, außerhalb der eingesetzten IT-Systeme, aufbewahrt werden.

#### Standard-Anforderungen

#### CON.1.A3 entfallen

Ehemals *Verschlüsselung der Kommunikationsverbindungen*:

*Es SOLLTE geprüft werden, ob mit vertretbarem Aufwand eine Verschlüsselung der Kommunikationsverbindungen möglich und praktikabel ist.*

*Ist dies der Fall, SOLLTEN Kommunikationsverbindungen geeignet verschlüsselt werden.*


#### CON.1.A4 ist jetzt Basis-Anforderung anstatt Standard-Anforderung

__Hinzugefügt:__

In einem geeigneten Schlüsselmanagement für kryptografische Hard oder Software MUSS festgelegt werden, wie Schlüssel und Zertifikate erzeugt, gespeichert, ausgetauscht und wieder gelöscht oder vernichtet werden.

Es MUSS ferner festgelegt werden, wie die Integrität und Authentizität der Schlüssel sichergestellt wird.

In Hard- oder Software mit kryptografischen Funktionen SOLLTEN voreingestellte Schlüssel (ausgenommen öffentliche Zertifikate) ersetzt werden.

Geheime Schlüssel MÜSSEN sicher gespeichert und vor unbefugtem Zugriff geschützt werden.

Grundsätzlich SOLLTE geregelt werden, wie mit abgelaufenen Schlüsseln und damit verbundenen Signaturen verfahren wird.

Falls die Gültigkeit von Schlüsseln oder Zertifikaten zeitlich eingeschränkt wird, dann MUSS durch die Institution sichergestellt werden, dass die zeitlich eingeschränkten Zertifikate oder Schlüssel rechtzeitig erneuert werden.

Eine Vorgehensweise SOLLTE für den Fall festgelegt werden, dass ein privater Schlüssel offengelegt wird.

__Geändert:__


Kryptografische Schlüssel SOLLTEN mit sicher geltenden Verfahren ausgetauscht werden.

Wenn öffentliche Schlüssel von Dritten verwendet werden, MUSS sichergestellt sein, dass die Schlüssel authentisch sind und die Integrität der Schlüsseldaten gewährleistet ist.

Eine Vorgehensweise SOLLTE für den Fall festgelegt werden, dass ein privater Schlüssel offengelegt wird.


#### CON.1.A5

__Hinzugefügt:__

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

#### Anforderungen bei erhöhtem Schutzbedarf

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

__Geändert:__

*Im Kryptokonzept SOLLTE festgelegt werden, wie der IT-Betrieb sicherstellt, dass nicht unautorisiert physisch auf Hardware mit kryptografischen Funktionen zugegriffen werden kann.*


##### Entfallen:

*Hard- und Softwareprodukte, die als Kryptomodule eingesetzt werden, SOLLTEN einen Selbsttest durchführen können.*


#### CON.1.A17

##### Entfallen:

*Getroffene Maßnahmen hinsichtlich der Abstrahlsicherheit SOLLTEN im Kryptokonzept dokumentiert werden.*


#### CON.1.A18

__Geändert:__

*Hardware mit kryptografischen Funktionen (z. B. Hardware-Token für Zwei-Faktor-Authentifizierung) SOLLTE vorrätig sein.*

*Im Kryptokonzept SOLLTE dokumentiert werden, für welche Hardware mit kryptografischen Funktionen Ersatzhardware zur Verfügung steht und wie diese ausgetauscht werden kann.*


#### CON.1.A20 vollständig neu hinzugefügt als Anforderung mit erhöhtem Schutzbedarf

</details>

### CON.2

<details>
<summary> Änderungen
</summary>

#### Basis-Anforderungen

#### CON.2.A1

__Geändert:__

Die gesetzlichen Bestimmungen zum Datenschutz (DSGVO, BDSG, die Datenschutzgesetze der Bundesländer und gegebenenfalls einschlägige bereichsspezifische Datenschutzregelungen) MÜSSEN eingehalten werden.

</details>

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

<details>
<summary> Änderungen
</summary>

#### Anforderungen bei erhöhtem Schutzbedarf

#### ORP.1.A17

Die Anforderung wurde neu hinzugefügt.

</details>

### ORP.2

Keine inhaltlichen Änderungen.


### ORP.3

Keine inhaltlichen Änderungen.


### ORP.4

Keine inhaltlichen Änderungen.


### ORP.5

Keine inhaltlichen Änderungen.


---


## OPS

### OPS.1.1.1

Der Baustein wurde neu hinzugefügt.


### OPS.1.1.2

<details>
<summary> Änderungen
</summary>

#### Basis-Anforderungen

#### OPS.1.1.2.A2

Anforderung wurde vollständig verändert, Notfallvorsorge ist aus dieser Anforderung entfallen.


#### OPS.1.1.2.A3 entfallen

Ehemals *Geregelte Einstellung von IT-Administratoren*:

*Wenn Mitarbeiter administrative Aufgaben innerhalb einer IT-Umgebung übernehmen, MÜSSEN sie in ihre Tätigkeit eingewiesen werden, insbesondere in die vorhandene IT-Architektur und die von ihnen zu betreuenden IT-Systeme und Anwendungen.*

*Die in der Institution gültigen und für ihre Tätigkeit relevanten Sicherheitsbestimmungen MÜSSEN den Administratoren bekannt sein.*


#### OPS.1.1.2.A4

Anforderung wurde vollständig verändert.


#### OPS.1.1.2.A5

__Hinzugefügt:__

*Administrative Tätigkeiten MÜSSEN nachweisbar sein. Dafür MUSS mindestens festgehalten werden,*

*• welche Änderung bei einer Tätigkeit durchgeführt wurde,*

*• wer eine Tätigkeit durchgeführt hat und*

*• wann eine Tätigkeit durchgeführt wurde.*


#### OPS.1.1.2.A6

Anforderung wurde vollständig verändert.


#### OPS.1.1.2.A21

Die Standard-Anforderung wurd neu hinzugefügt.


#### OPS.1.1.2.A22

Die Standard-Anforderung wurd neu hinzugefügt.

#### Standard-Anforderungen

#### OPS.1.1.2.A7

Anforderung wurde vollständig verändert.


#### OPS.1.1.2.A8

Anforderung wurde vollständig verändert.


#### OPS.1.1.2.A9 entfallen

Ehemals *Ausreichende Ressourcen für den IT-Betrieb*:

*Es SOLLTEN ausreichende Personal- und Sachressourcen bereitgestellt werden, um die anfallenden administrativen Aufgaben ordnungsgemäß zu bewältigen.*

*Dabei SOLLTE berücksichtigt werden, dass auch für unvorhersehbare Tätigkeiten entsprechende Kapazitäten vorhanden sein müssen.*

*Die Ressourcenplanung SOLLTE in regelmäßigen Zyklen geprüft und den aktuellen Erfordernissen angepasst werden.*


#### OPS.1.1.2.A10 entfallen

Ehemals *Fortbildung und Information*:

*Für die eingesetzten Administratoren SOLLTEN geeignete Fort- und Weiterbildungsmaßnahmen ergriffen werden.*

*Dabei SOLLTEN auch technische Entwicklungen berücksichtigt werden, die noch nicht aktuell sind, aber für die Institution in absehbarer Zeit wichtig werden könnten.*

*Die Fortbildungsmaßnahmen SOLLTEN durch einen Schulungsplan unterstützt werden.*

*Dieser Schulungsplan SOLLTE das gesamte Team berücksichtigen, sodass alle erforderlichen Qualifikationen im Team mehrfach vorhanden sind.*

*Administratoren SOLLTEN sich regelmäßig über die Sicherheit der von ihnen betreuten Anwendungen, IT-Systeme, Dienste und Protokolle informieren, insbesondere über aktuelle Gefährdungen und Sicherheitsmaßnahmen.*


#### OPS.1.1.2.A11

Anforderung wurde vollständig verändert.


#### OPS.1.1.2.A12 entfallen

Ehemals *Regelungen für Wartungs- und Reparaturarbeiten*:

*IT-Systeme SOLLTEN regelmäßig gewartet werden.*

*Es SOLLTE geregelt sein, welche Sicherheitsaspekte bei Wartungs- und Reparaturarbeiten zu beachten sind.*

*Hierüber hinaus SOLLTE festgelegt werden, wer für die Wartung oder Reparatur von Geräten zuständig ist.*

*Durchgeführte Wartungsarbeiten SOLLTEN dokumentiert werden.*


#### OPS.1.1.2.A16

Ehemals Anforderung erhöhten Schutzbedarfs, jetzt Standard-Anforderung.

Inhalt wurde grundlegend verändert.


#### OPS.1.1.2.A20 entfallen

Ehemals *Verwaltung und Inbetriebnahme von Geräten*:

*Es SOLLTE eine Übersicht aller Geräte vorhanden sein, die in der Institution genutzt werden und Einfluss auf die Informationssicherheit haben können.*

*Dazu SOLLTEN neben IT-Systemen und ICS-Komponenten auch Geräte aus dem Bereich „Internet der Dinge“ (engl. „Internet of Things“, IoT) berücksichtigt werden.*

*Vor der ersten Inbetriebnahme der Geräte SOLLTEN geeignete Prüf- und Genehmigungsverfahren vorgeschaltet werden.*

*Die Übersicht SOLLTE stets aktuell gehalten werden und mit der Dokumentation von administrativen Tätigkeiten korrespondieren.*


#### OPS.1.1.2.A23

Standard-Anforderung wurde neu hinzugefügt.


#### OPS.1.1.2.A24

Standard-Anforderung wurde neu hinzugefügt.


#### OPS.1.1.2.A25

Standard-Anforderung wurde neu hinzugefügt.


#### OPS.1.1.2.A26

Standard-Anforderung wurde neu hinzugefügt.


#### OPS.1.1.2.A27

Standard-Anforderung wurde neu hinzugefügt.


#### OPS.1.1.2.A28

Standard-Anforderung wurde neu hinzugefügt.

#### Anforderungen bei erhöhtem Schutzbedarf

#### OPS.1.1.2.A14 entfallen

Ehemals *Sicherheitsüberprüfung von Administratoren*:

*Bei erhöhtem Schutzbedarf SOLLTEN Administratoren einer zusätzlichen Sicherheitsüberprüfung unterzogen werden.*


#### OPS.1.1.2.A15 entfallen

Ehemals *Aufteilung von Administrationstätigkeiten*:

*Es SOLLTEN unterschiedliche Administrationsrollen für Teilaufgaben eingerichtet werden.*

*Bei der Abgrenzung der Aufgaben SOLLTEN die Art der Daten und die vorhandene Systemarchitektur berücksichtigt werden.*


#### OPS.1.1.2.A17

Inhalt wurde grundlegend verändert.


#### OPS.1.1.2.A18

Inhalt wurde grundlegend verändert.


#### OPS.1.1.2.A19

Inhalt wurde grundlegend verändert.


#### OPS.1.1.2.A29

Anforderung mit erhöhtem Schutzbedarf wurde neu hinzugefügt.


#### OPS.1.1.2.A30

Anforderung mit erhöhtem Schutzbedarf wurde neu hinzugefügt.

</details>


### OPS.1.1.3

<details>
<summary> Änderungen
</summary>

#### Basis-Anforderungen

#### OPS.1.1.3.A15

##### Neu:

*Für die Bewertung SOLLTE geprüft werden, ob es zu diesem Patch bekannte Schwachstellen gibt.*

*Falls Hardware- oder Software-Produkte eingesetzt werden sollen, die nicht mehr von den Herstellenden unterstützt werden oder für die kein Support mehr vorhanden ist, MUSS geprüft werden, ob diese dennoch sicher betrieben werden können.*

*Ist dies nicht der Fall, DÜRFEN diese Hardware- oder Software-Produkte NICHT mehr verwendet werden.*


#### OPS.1.1.3.A16 entfallen

Ehemals *Regelmäßige Suche nach Informationen zu Patches und Schwachstellen*:

*Der IT-Betrieb MUSS sich regelmäßig über bekannt gewordene Schwachstellen der Firmware, Betriebssysteme, eingesetzter Anwendungen und Dienste informieren.*

*Die identifizierten Schwachstellen MÜSSEN so schnell wie möglich behoben werden.*

*Solange keine entsprechenden Patches zur Verfügung stehen, MÜSSEN abhängig davon, wie schwerwiegend die Schwachstellen und Bedrohungen sind, andere geeignete Maßnahmen zum Schutz des IT-Systems getroffen werden.*

*Falls dies nicht möglich ist, SOLLTE sichergestellt sein, dass die entsprechende Hardware, relevanten Betriebssysteme, eingesetzten Anwendungen und Dienste nicht weiter verwendet werden.*

</details>

### OPS.1.1.4

Keine inhaltlichen Änderungen.


### OPS.1.1.5

Keine inhaltlichen Änderungen.


### OPS.1.1.6

Keine inhaltlichen Änderungen.


### OPS.1.1.7

Keine inhaltlichen Änderungen.


### OPS.1.2.2

Keine inhaltlichen Änderungen.


### OPS.1.2.4

Keine inhaltlichen Änderungen.


### OPS.1.2.5

<details>
<summary> Änderungen
</summary>

#### Standard-Anforderungen

#### OPS.1.2.5.A19

__Geändert:__

*Die Pflichten und Kompetenzen des externen Wartungspersonals SOLLTEN in den vertraglichen Regelungen festgehalten werden.*

*Sollten Dienstleistende mehrere Kunden und Kundinnen fernwarten, MUSS gewährleistet sein, dass die Netze der Kunden und Kundinnen nicht miteinander verbunden werden.*

#### Anforderungen bei erhöhtem Schutzbedarf

##### OPS.1.2.5.A14

##### Neu:

*Für Fernwartungszugänge SOLLTEN dedizierte Konten verwendet werden.*

</details>

### OPS.1.2.6

Keine inhaltlichen Änderungen.


### OPS.2.1

Der Baustein "*Outsourcing für Kunden*" ist entfallen. An dessen Stelle wurde der Baustein "*OPS.2.3 Nutzung von Outsourcing*" eingeführt.


### OPS.2.2

Keine inhaltlichen Änderungen.


### OPS.2.3

Der Baustein "*Nutzung von Outsourcing*" wurde neu hinzugefügt anstelle des Bausteins "*OPS.2.1 Outsourcing für Kunden*".


### OPS.3.1

Der Baustein "Outsourcing für Dienstleister" ist entfallen. An dessen Stelle wurde der Baustein "OPS.3.2 Anbieten von Outsourcing" eingeführt.


### OPS.3.2

Der Baustein "*Anbieten von Outsourcing*" wurde neu hinzugefügt anstelle des Bausteins "*OPS.3.1 Outsourcing für Dienstleister*".


---

## DER

### DER.1

Keine inhaltlichen Änderungen.


### DER.2.1

Keine inhaltlichen Änderungen.


### DER.2.2

Keine inhaltlichen Änderungen.


### DER.2.3

Keine inhaltlichen Änderungen.


### DER.3.1

Keine inhaltlichen Änderungen.


### DER.3.2

Keine inhaltlichen Änderungen.


### DER.4

Keine inhaltlichen Änderungen.


---


## APP

### APP.1.1

Keine inhaltlichen Änderungen


### APP.1.2

<details>
<summary> Änderungen
</summary>

#### Basis-Anforderungen

#### APP.1.2.A13

##### Neu:

*Die Institution MUSS entscheiden, ob die verwendeten Browser DNS-over-HTTPS (DoH) verwenden sollen.*

*Die Browser MÜSSEN entsprechend dieser Entscheidung konfiguriert werden.*

*Falls ein interner DNS-Resolver verwendet wird, MUSS dieser auch vom Browser verwendet werden.*


##### Entfallen:

*Die Institution MUSS prüfen, ob die verwendeten Browser DNS-over-HTTPS (DoH) einsetzen.*

*Es MUSS festgelegt werden, ob die Funktion verwendet werden soll.*

*Falls die Institution DNS-Server als Resolver verwendet, die über nicht vertrauenswürdige Netze angesprochen werden, SOLLTE DoH verwendet werden.*

*Falls DoH verwendet wird, MUSS die Institution einen vertrauenswürdigen DoH-Server festlegen.*

#### Standard-Anforderungen

#### APP.1.2.A7

##### Neu:

*Wird die Funktion dennoch genutzt, SOLLTEN die Benutzenden diese Daten löschen können.*

</details>

### APP.1.4

Keine inhaltlichen Änderungen.


### APP.1.5

Keine inhaltlichen Änderungen.


### APP.2.1

<details>
<summary> Änderungen
</summary>

#### Basis-Anforderungen

#### APP.2.1.A2

__Geändert:__

*Zudem MUSS ein Konzept für eine Struktur aus Objektklassen und Attributtypen entwickelt werden, dass den Ansprüchen der vorgesehenen Nutzungsarten genügt.*

*Bei der Planung eines Verzeichnisdienstes, der personenbezogene Daten beinhaltet, MÜSSEN Personalvertretung und Datenschutzbeauftragte beteiligt werden.*

*Generell SOLLTE die geplante Verzeichnisdienststruktur vollständig dokumentiert und die Dokumentation bei Änderungen fortgeschrieben werden.*

*Maßnahmen SOLLTEN geplant und umgesetzt werden, die es unterbinden, aus dem Verzeichnisdienst unbefugt Daten sammeln zu können.*


#### APP.2.1.A5

##### Entfallen:

*Vor den Konfigurationsänderungen SOLLTEN von allen betroffenen Dateien und Verzeichnissen Datensicherungen angefertigt werden.*


#### APP.2.1.A6

##### Entfallen:

*Die Arbeitsplätze von Verzeichnisdienstadministratoren MÜSSEN ausreichend gesichert sein.*

##### Neu:

*Sofern der Verzeichnisdienst zur Verwaltung von Anmeldedaten verwendet wird, MÜSSEN dedizierte Clients bei der Fernwartung eingesetzt werden.*


#### APP.2.1.17

Die Basis-Anforderung wurde neu hinzugefügt.

#### Standard-Anforderungen

#### APP.2.1.A7 ist entfallen

Ehemals *Erstellung eines Sicherheitskonzepts für den Einsatz von Verzeichnisdiensten*:

*Durch das Sicherheitskonzept für Verzeichnisdienste SOLLTEN sämtliche sicherheitsbezogenen Themenbereiche eines Verzeichnisdienstes geregelt werden.*

*Die daraus entwickelten Sicherheitsrichtlinien SOLLTEN schriftlich festgehalten und den Benutzern des Verzeichnisdienstes mitgeteilt werden.*


#### APP.2.1.A8

__Geändert:__

*Sofern eine Partitionierung geplant ist, SOLLTE sich diese an den Schutzzielen des Verzeichnisdienstes orientieren und diese geeignet unterstützen.*

*Eine Partitionierung SOLLTE so geplant werden, dass sie die Schadensauswirkungen bei Sicherheitsvorfällen begrenzt, die unabhängige Administration verschiedener Partitionen ermöglicht und organisatorischen bzw. Sicherheitsgrenzen folgt.*

##### Entfallen:

*Um die Replikationen zeitgerecht ausführen zu können, SOLLTE eine ausreichende Bandbreite sichergestellt werden.*


#### APP.2.1.A11

##### Entfallen:

*Sollen anonymen Benutzern auf einzelne Teilbereiche des Verzeichnisbaums weitergehende Zugriffe eingeräumt werden, so SOLLTE ein gesondertes Benutzerkonto, ein sogenannter Proxy-User, für den anonymen Zugriff eingerichtet werden.*

*Die Zugriffsrechte für diesen Proxy-User SOLLTEN hinreichend restriktiv vergeben werden.*

*Sie SOLLTEN zudem wieder komplett entzogen werden, wenn der Account nicht mehr gebraucht wird.*

*Damit nicht versehentlich schutzbedürftige Informationen herausgegeben werden, SOLLTE die Suchfunktion des Verzeichnisdienstes dem Einsatzzweck angemessen eingeschränkt werden.*


#### APP.2.1.A12

##### Neu:

*Insbesondere Änderungen innerhalb des Verzeichnisdienstes sowie Konfigurationsänderungen des Verzeichnisdienstes SOLLTEN vorrangig protokolliert werden.*


#### APP.2.1.A13

##### Entfallen:

*Der Kommunikationsendpunkt des Verzeichnisdienst-Servers SOLLTE aus dem Internet nicht erreichbar sein.*

*Im Falle einer serviceorientierten Architektur (SOA) SOLLTEN zum Schutz von Service-Einträgen in einer Service-Registry sämtliche Anfragen an die Registratur daraufhin überprüft werden, ob der Benutzer gültig ist.*

__Geändert:__

*Werden vertrauliche Informationen übertragen, SOLLTE die gesamte Kommunikation mit dem Verzeichnisdienst über ein sicheres Protokoll entsprechend der Technischen Richtlinie TR-02102 des BSI (z. B. TLS) verschlüsselt werden.*


#### APP.2.1.A14

##### Entfallen:

*Die Zugriffsrechte für Verzeichnisdienst-Objekte bei Systemen, die von Vorgängerversionen aktualisiert bzw. von anderen Verzeichnissystemen übernommen wurden, SOLLTEN aktualisiert werden.*

##### Neu:

*In dem Migrationskonzept SOLLTE berücksichtigt werden, ob das Berechtigungsmanagement von altem und neuem Verzeichnisdienst analog funktioniert oder ob neue Berechtigungsstrukturen erforderlich sind.*

*Bei der Migration SOLLTE berücksichtigt werden, dass IT-Systeme, die auf den Verzeichnisdienst zugreifen, gegebenenfalls lokale Caches vorhalten oder aus anderen Gründen dort eine Aktualisierung der migrierten Verzeichnisdienstinhalte initiiert werden muss.*


__Geändert:__

*Die Schema-Änderungen, die am Verzeichnisdienst vorgenommen wurden, SOLLTEN vor der Migration analysiert und dokumentiert werden.*


#### APP.2.1.A18

Die Standard-Anforderung wurde neu hinzugefügt.


#### APP.2.1.A19

Die Standard-Anforderung wurde neu hinzugefügt.

#### Anforderungen bei erhöhtem Schutzbedarf

#### APP.2.1.A20

Die Anforderung erhöhten Schutzbedarfs wurde neu hinzugefügt.


#### APP.2.1.A21

Die Anforderung erhöhten Schutzbedarfs wurde neu hinzugefügt.

</details>

### APP.2.2

<details>
<summary> Änderungen
</summary>

#### Basis-Anforderungen

#### APP.2.2.A1

##### Entfallen:

*Die geplante Active-Directory-Struktur einschließlich etwaiger Schema-Änderungen SOLLTE nachvollziehbar dokumentiert sein.*


__Geändert:__

*Es MUSS eine Funktionsebene für die Domäne(n) und die Gesamtstruktur von mindestens Windows Server 2016 gewählt werden.*

*Ein bedarfsgerechtes Berechtigungskonzept für die Domäne(n) und die Gesamtstruktur MUSS entworfen werden.*


##### Neu:

*Dabei MUSS berücksichtigt werden, dass zwischen den einzelnen Domänen einer Gesamtstruktur produktbedingt keine Sicherheitsgrenzen bestehen und daher keine sichere Begrenzung der administrativen Bereiche innerhalb einer Gesamtstruktur möglich ist.*


#### APP.2.2.A2

Die Anforderung ist ohne Angabe entfallen, wird im 2023er-Kompendium nicht mehr erwähnt, auch nicht der Wegfall.


#### APP.2.2.A5

Die Anforderung wurde grundlegend überarbeitet und handelt nun von der "*Absicherung des Domänencontrollers*".


#### APP.2.2.A6

Die Anforderung wurde grundlegend überarbeitet und handelt nun von der "*Sicheren Konfiguration von Vertrauensbeziehungen*".


#### APP.2.2.A7

Die Anforderung wurde inhaltlich vollständig überarbeitet.


#### APP.2.2.A16

Die Basis-Anforderung wurde neu hinzugefügt.


#### APP.2.2.A17

Die Basis-Anforderung wurde neu hinzugefügt.


#### APP.2.2.A18

Die Basis-Anforderung wurde neu hinzugefügt.

#### Standard-Anforderungen

#### APP.2.2.A8

##### Entfallen:

*Dabei SOLLTEN alle relevanten Gruppenrichtlinienparameter berücksichtigt werden.*


__Geändert:__

*Der „Sichere Kanal“ SOLLTE so konfiguriert sein, dass alle übertragenen Daten immer verschlüsselt und signiert werden.*


#### APP.2.2.A9

Die Anforderung wurde inhaltlich vollständig überarbeitet.


#### APP.2.2.A10 entfallen


#### APP.2.2.A11 entfallen


#### APP.2.2.A12

Die Anforderung wurde inhaltlic vollständig überarbeitet.

#### Anforderungen bei erhöhtem Schutzbedarf

#### APP.2.2.A14 entfallen


#### APP.2.2.A15

Die Anforderung wurde inhaltlic vollständig überarbeitet.


#### APP.2.2.A19

Die Anforderung für erhöhten Schutzbedarf wurde neu hinzugefügt.


#### APP.2.2.A20

Die Anforderung für erhöhten Schutzbedarf wurde neu hinzugefügt.


#### APP.2.2.A21

Die Anforderung für erhöhten Schutzbedarf wurde neu hinzugefügt.


#### APP.2.2.A22

Die Anforderung für erhöhten Schutzbedarf wurde neu hinzugefügt.


#### APP.2.2.A23

Die Anforderung für erhöhten Schutzbedarf wurde neu hinzugefügt.

</details>

### APP.2.3

<details>
<summary> Änderungen
</summary>

#### Standard-Anforderungen

#### APP.2.3.A9

__Geändert:__

*Bei einer Partitionierung oder Replikation von OpenLDAP SOLLTE die Aufteilung geeignet für die Sicherheitsziele ausgewählt werden.*

#### APP.2.3.A10

##### Neu:

*Beim Update auf neue Releases SOLLTE geprüft werden, ob die verwendeten Overlays und Backends in der neuen Version weiterhin zur Verfügung stehen.*

*Ist dies nicht der Fall, SOLLTEN geeignete Migrationspfade ausgewählt werden.*

#### APP.2.3.A11

##### Entfallen:

*Der slapd-Server SOLLTE auf ein Laufzeitverzeichnis eingeschränkt werden.*

*Hierfür SOLLTE dieses Verzeichnis alle Konfigurationsdateien und Datenbanken beinhalten.*


##### Neu:

*Die Laufzeitumgebung des slapd-Servers SOLLTE, möglichst mit Mitteln des Betriebssystems, auf die minimal benötigten Dateien, Verzeichnisse und vom Betriebssystem bereitgestellten Funktionen eingeschränkt werden.*

*Werden hierfür Containerisierungstechniken eingesetzt, SOLLTEN diese unter Berücksichtigung von SYS.1.6 Containerisierung genutzt werden.*

*Wird der slapd-Server als exklusiver Dienst auf einem dedizierten Server betrieben, SOLLTE dieser ausreichend gehärtet sein.*

</details>

### APP.3.1

Keine inhaltlichen Änderungen.


### APP.3.2

Keine inhaltlichen Änderungen.


### APP.3.3

Keine inhaltlichen Änderungen.


### APP.3.4

<details>
<summary> Änderungen
</summary>

#### Standard-Anforderungen

#### APP.3.4.A6

##### Entfallen:

*Dabei SOLLTE Winbind Domänen-Benutzernamen in eindeutige Unix-Benutzernamen umsetzen.*

</details>

### APP.3.6

Keine inhaltlichen Änderungen.


### APP.4.2

Keine inhaltlichen Änderungen.


### APP.4.3

Keine inhaltlichen Änderungen.


### APP.4.4

Keine inhaltlichen Änderungen.


### APP.4.6

Keine inhaltlichen Änderungen.


### APP.5.2

Keine inhaltlihcen Änderungen.


### APP.5.3

<details>
<summary> Änderungen
</summary>

#### Basis-Anforderungen

#### APP.5.3.A1

__Geändert:__

*Bevor Dateianhänge aus E-Mails geöffnet werden, MÜSSEN sie auf Schadsoftware überprüft werden.*

*Die Dateianhänge MÜSSEN auf dem Client oder auf dem E-Mail-Server überprüft werden.*


#### APP.5.3.A2

##### Neu:

*Der Empfang von E-Mails über unverschlüsselte Verbindungen SOLLTE deaktiviert werden.*

*Der IT-Betrieb SOLLTE den E-Mail-Versand durch unsichere Netze über unverschlüsselte Verbindungen deaktivieren.*

*Der IT-Betrieb MUSS den E-Mail-Server so konfigurieren, dass E-Mail-Clients nur über eine sichere Transportverschlüsselung auf Postfächer zugreifen können, wenn dies über nicht vertrauenswürdige Netze passiert.*


__Geändert:__

*Für den E-Mail-Empfang über nicht vertrauenswürdige Netze MÜSSEN E-Mail-Server eine sichere Transportverschlüsselung anbieten.*

#### Standard-Anforderungen

#### APP.5.3.A6

##### Entfallen:

*• wie sich die Kommunikation absichern lässt,*


#### APP.5.3.A9

##### Entfallen:

*Wird SPF verwendet, SOLLTE eindeutig vorgegeben werden, wie mit E-Mails verfahren werden soll.*

##### Neu:

*Wird SPF verwendet, SOLLTEN alle sendeberechtigten E-Mail-Server für eine Domain im SPF-Eintrag angegeben werden.*

*Der SPF-Eintrag SOLLTE den „-all“ Parameter enthalten.*

*DMARC-Einträge SOLLTEN vorgeben, dass E-Mails im Fehlerfall abgewiesen werden.*

</details>

### APP.5.4

Der Baustein wurde neu hinzugefügt.


### APP.6

Keine inhaltlichen Änderungen.


### APP.7

Keine inhaltlichen Änderungen.


--

## IND

### IND.1

Keine inhaltlichen Änderungen.


### IND.2.1

Keine inhaltlichen Änderungen.


### IND.2.2

Keine inhaltlichen Änderungen.


### IND.2.3

Keine inhaltlichen Änderungen.


### IND.2.4

Keine inhaltlichen Änderungen.


### IND.2.7

Keine inhaltlichen Änderungen.


### IND.3.2

<details>
<summary> Änderungen
</summary>

#### Basis-Anforderungen

#### IND.3.2.A1

##### Neu:

*• spezifische gesetzliche Vorgaben, z. B. Schutz von Personen,*


#### IND.3.2.A4

##### Neu:

*Im industriellen Umfeld MUSS sichergestellt werden, dass Personen an oder in Anlagen und Maschinen weder direkt noch indirekt durch eine aktive Fernwartung gefährdet werden können.*

</details>


---

## SYS

### SYS.1.1

<details>
<summary> Änderungen
</summary>

#### Basis-Anforderungen

#### SYS.1.1.A1

__Geändert:__

*Physische Server MÜSSEN an Orten betrieben werden, zu denen nur berechtigte Personen Zutritt haben.*

*Physische Server MÜSSEN daher in Rechenzentren, Serverräumen oder abschließbaren Serverschränken aufgestellt beziehungsweise eingebaut werden (siehe hierzu die entsprechenden Bausteine der Schicht INF Infrastruktur).*


##### Neu:

*Bei virtualisierten Servern MUSS der Zugriff auf die Ressourcen der Instanz und deren Konfiguration ebenfalls auf die berechtigten Personen begrenzt werden.*

*Server DÜRFEN NICHT zur Erledigung von Aufgaben und Tätigkeiten verwendet werden, die grundsätzlich auf einem Client-System aus- und durchgeführt werden können.*

*Insbesondere DÜRFEN vorhandene Anwendungen, wie Webbrowser, auf dem Server NICHT für das Abrufen von Informationen aus dem Internet oder das Herunterladen von Software, Treibern und Updates verwendet werden.*


#### SYS.1.1.A6

__Geändert:__

*Alle nicht benötigten Serverrollen, Features und Funktionen, sonstige Software und Dienste MÜSSEN deaktiviert oder deinstalliert werden, vor allem Netzdienste.*


##### Neu:

*Die Empfehlungen des Betriebssystemherstellers SOLLTEN hierbei als Orientierung berücksichtigt werden.*


#### Standard-Anforderungen

#### SYS.1.1.A16

Grundlegend geändert, Inhalt nahezu vollständig neu.


#### SYS.1.1.A39

Anforderung neu als Standard-Anforderung hinzugekommen.

</details>

### SYS.1.2.3

Der Baustein wurde neu hinzugefügt.


### SYS.1.3

Keine inhaltlichen Änderungen.


### SYS.1.5

Keine inhaltlichen Änderungen.


### SYS.1.6

<details>
<summary> Änderungen
</summary>

#### Basis-Anforderungen

#### SYS.1.6.A6

##### Neu:

*Die Quelle MUSS diesen Umgang mit Sicherheitsproblemen zusichern und einhalten.*

</details>

### SYS.1.7

Keine inhaltlichen Änderungen.


### SYS.1.8

Keine inhaltlichen Änderungen.


### SYS.1.9

Der Baustein wurde neu hinzugefügt.


### SYS.2.1

<details>
<summary> Änderungen
</summary>

#### Standard-Anforderungen

#### SYS.2.1.A11

##### Neu (aus entfallener Anforderung SYS.2.1.A14 übernommen):

*Auf Betriebssysteme, die über ein Rolling-Release-Modell aktualisiert werden, SOLLTE verzichtet werden.*


#### SYS.2.1.A14 ist entfallen.

Ehemals *Updates und Patches für Firmware, Betriebssystem und Anwendungen*.

*Auf Betriebssysteme, die über ein Rolling-Release-Modell aktualisiert werden, SOLLTE verzichtet werden.*

*Es SOLLTEN NUR Anwendungsprogramme ausgewählt und installiert werden, für die Support angeboten wird.*

*Betriebssysteme, Anwendungsprogramme und Firmware, für die keine regelmäßigen Sicherheitsupdates angeboten werden, DÜRFEN NICHT eingesetzt werden.*

</details>

### SYS.2.2.3

<details>
<summary> Änderungen
</summary>

Jetzt für alle Windows Client Betriebssysteme gültig, nicht mehr nur Windows 10.

#### Basis-Anforderungen

#### SYS.2.2.3.A4

__Geändert:__

*Um die Übertragung von Diagnose- und Nutzungsdaten an Microsoft stark zu reduzieren, MUSS das Telemetrie-Level 0 (Security) in der Enterprise-Edition von Windows konfiguriert werden.*

*Wenn diese Einstellung nicht wirksam umgesetzt wird oder bei anderen Windows-Edition umgesetzt werden kann, dann MUSS durch geeignete Maßnahmen, etwa auf Netzebene, sichergestellt werden, dass die Daten nicht an den Hersteller übertragen werden.*

#### Standard-Anforderungen

#### SYS.2.2.3.A19

__Geändert:__

*Die eingesetzten kryptografischen Protokolle und Algorithmen SOLLTEN sicher sein und den internen Vorgaben der Institution entsprechen.*

#### Anforderungen bei erhöhtem Schutzbedarf

#### SYS.2.2.3.A26

Die Anforderung wurde neu hinzugefügt.

</details>

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

<details>
<summary> Änderungen
</summary>

#### Basis-Anforderungen

#### SYS.4.3.A1

##### Entfallen:

*Um eingebettete Systeme reibungslos zu betreiben, MÜSSEN Zuständige ernannt werden.*

##### Neu:

*Alle eingebetteten Systeme inklusive Schnittstellen MÜSSEN erfasst werden.*


#### Standard-Anforderungen

#### SYS.4.3.A11

##### Neu:

*Ist dies nicht möglich, SOLLTE das System vernichtet werden.*

</details>

### SYS.4.4

Keine inhaltlichen Änderungen.


### SYS.4.5

<details>
<summary> Änderungen
</summary>

#### Basis-Anforderungen

#### SYS.4.5.A2

##### Neu:

*Die Institution MUSS festlegen, wie Wechseldatenträger behandelt werden sollen, die nach einem Verlust wiedergefunden wurden.*

*Wiedergefundene Wechseldatenträger DÜRFEN NICHT ohne vorherige Überprüfung auf Manipulation und Schadsoftware verwendet werden.*


#### Standard-Anforderungen

#### SYS.4.5.A4

##### Entfallen:

*ob und wie private Datenträger genutzt werden dürfen,*


##### Neu:

*ob Wechseldatenträger an fremde IT-Systeme angeschlossen werden dürfen und was dabei zu beachten ist,*

*Die Institution SOLLTE die Verwendung von privaten Wechseldatenträgern untersagen.*


#### SYS.4.5.A17 Neue Standard-Anforderung

*Falls Wechseldatenträger verwendet werden, um Daten für lange Zeiträume zu speichern, SOLLTE die Institution sicherstellen, dass die verwendeten Wechseldatenträger geeignet sind, um die Integrität und Verfügbarkeit der Daten während des gesamten Nutzungszeitraums sicherzustellen.*

*Die Integrität der Daten SOLLTE regelmäßig überprüft werden.*

</details>

---


## NET


### NET.1.1

Keine inhaltlichen Änderungen.


### NET.1.2

Keine inhaltlichen Änderungen.


### NET.2.1

Keine inhaltlichen Änderungen.


### NET.2.2

Keine inhaltlichen Änderungen.


### NET.3.1

Keine inhaltlichen Änderungen.


### NET.3.2

Keine inhaltlichen Änderungen.


### NET.3.3

Keine inhaltlichen Änderungen.


### NET.3.4 Network Access Control (NAC)

Der Baustein wurde neu hinzugefügt.


### NET.4.1

Keine inhaltlichen Änderungen.


### NET.4.2

Keine inhaltlichen Änderungen.


### NET.4.3

Keine inhaltlichen Änderungen.


---


## INF

### INF.1

<details>
<summary> Änderungen
</summary>

#### INF.1.A1

##### Entfallen (verschoben zu INF.1.A9):

*Es MUSS ein IT-bezogenes Brandschutzkonzept erstellt und umgesetzt werden.*


#### INF.1.A9

##### Neu:

*Es MUSS ein IT-bezogenes Brandschutzkonzept erstellt und umgesetzt werden.*

</details>

### INF.2

Keine inhaltlichen Änderungen.


### INF.5

Keine inhaltlichen Änderungen.


### INF.6

Keine inhaltlichen Änderungen.


### INF.7

Keine inhaltlichen Änderungen.


### INF.8

Keine inhaltlichen Änderungen.


### INF.9

Keine inhaltlichen Änderungen.


### INF.10

<details>
<summary> Änderungen
</summary>

#### INF.10.A10 ist entfallen (verschoben zu ORP.1.A17)

Ehemals *Mitführverbot von Mobiltelefonen*:

*Mobiltelefone SOLLTEN NICHT zu vertraulichen Besprechungen und Gesprächen mitgeführt werden.*

*Falls erforderlich, SOLLTE dies durch Mobilfunk-Detektoren überprüft werden.*

</details>

### INF.11

Keine inhaltlichen Änderungen.


### INF.12

Keine inhaltlichen Änderungen.


### INF.13

Keine inhaltlichen Änderungen.


### INF.14

Keine inhaltlichen Änderungen.

---


Quellen:


[BSI IT Grundschutz Kompendium Edition 2022](https://www.bsi.bund.de/SharedDocs/Downloads/DE/BSI/Grundschutz/Kompendium/IT_Grundschutz_Kompendium_Edition2022.pdf)


[BSI IT Grundschutz Kompendium Edition 2023](https://www.bsi.bund.de/SharedDocs/Downloads/DE/BSI/Grundschutz/Kompendium/IT_Grundschutz_Kompendium_Edition2023.pdf)



