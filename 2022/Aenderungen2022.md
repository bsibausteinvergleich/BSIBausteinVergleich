# Übersicht der Änderungen des IT-Grundschutz-Kompendiums von Version 2021 zu 2022

Übergreifend wurden Formulierungen angepasst, die keinen Einfluss auf Bedeutung und Inhalt haben. Es wurden beispielsweise Sätze getrennt oder Formulierungen angepasst, die den Sprachfluss anpassen oder Gliederungen vereinheitlichen.

___


## ISMS

Keine inhaltlichen Änderungen.


---


## ORP

Keine inhaltlichen Änderungen.


---


## CON

### CON.1

Keine inhaltlichen Änderungen.


### CON.2

Keine inhaltlichen Änderungen.


### CON.3

<details>
<summary> Änderungen
</summary>

#### Basis-Anforderungen

#### CON.3.A1

__Geändert:__

Dazu MÜSSEN die Fachverantwortlichen für die Anwendungen ihre Anforderungen an die Datensicherung definieren.

Der IT-Betrieb MUSS mindestens die nachfolgenden Rahmenbedingungen mit den Fachverantwortlichen abstimmen:

• zu sichernde Daten,

• Vertraulichkeitsanforderungen,

• Integritätsbedarf,

• rechtliche Anforderungen,

• Anforderungen an das Löschen und Vernichten der Daten sowie

• Zuständigkeiten für die Datensicherung.

Die Einflussfaktoren MÜSSEN nachvollziehbar und auf geeignete Weise festgehalten werden.


#### CON.3.A2

__Geändert:__

CON.3.A2 Festlegung der Verfahrensweisen für die Datensicherung [Fachverantwortliche, IT-Betrieb] (B)

Der IT-Betrieb MUSS Verfahren festlegen, wie die Daten gesichert werden.

Dies MUSS wiederum auf Basis der erhobenen Einflussfaktoren und in Abstimmung mit den jeweiligen Fachverantwortlichen geschehen.


__Hinzugefügt:__

Datensicherungen MÜSSEN immer auf separaten Speichermedien für die Datensicherung gespeichert werden.

Besonders schützenswerte Speichermedien für die Datensicherung SOLLTEN nur während der Datensicherung und Datenwiederherstellung mit dem Netz der Institution oder dem Ursprungssystem verbunden werden.

In virtuellen Umgebungen sowie für Storage-Systeme SOLLTE geprüft werden, ob das IT-System ergänzend durch Snapshot-Mechanismen gesichert werden kann, um hierdurch mehrere schnell wiederherstellbare Zwischenversionen zwischen den vollständigen Datensicherungen zu erstellen.


#### CON.3.A4

__Geändert:__

CON.3.A4 Erstellung von Datensicherungsplänen [IT-Betrieb] (B)

Der IT-Betrieb MUSS Datensicherungspläne je IT-System oder Gruppe von IT-Systemen auf Basis der festgelegten Verfahrensweise für die Datensicherung erstellen.

Diese MÜSSEN festlegen, welche Anforderungen für die Datensicherung mindestens einzuhalten sind.

Die Datensicherungpläne MÜSSEN mindestens eine kurze Beschreibung dazu enthalten:


__Hinzugefügt:__

• in welcher Reihenfolge IT-System und Anwendungen wiederhergestellt werden,

• wie lange Datensicherungen aufbewahrt werden,

• wie die Datensicherungen vor unbefugtem Zugriff und Überschreiben gesichert werden,


#### CON.3.A5

__Geändert:__

CON.3.A5 Regelmäßige Datensicherung [IT-Betrieb, Mitarbeiter] (B)

Regelmäßige Datensicherungen MÜSSEN gemäß den Datensicherungsplänen erstellt werden.

Alle Mitarbeiter MÜSSEN über die Regelungen zur Datensicherung informiert sein.

Auch MÜSSEN sie darüber informiert werden, welche Aufgaben sie bei der Erstellung von Datensicherungen haben.


#### CON.3.A12 

ist jetzt Basis-Anforderung anstatt Standard-Anforderung

__Geändert:__

CON.3.A12 Sichere Aufbewahrung der Speichermedien für die Datensicherungen [IT-Betrieb] (B)

Die Speichermedien für die Datensicherung MÜSSEN räumlich getrennt von den gesicherten IT-Systemen aufbewahrt werden.

Sie SOLLTEN in einem anderen Brandabschnitt aufbewahrt werden.

Der Aufbewahrungsort SOLLTE so klimatisiert sein, dass die Datenträger entsprechend der zeitlichen Vorgaben des Datensicherungskonzepts aufbewahrt werden können.

</details>

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

---



## OPS

### OPS.1.1.2

Keine inhaltlichen Änderungen.


### OPS.1.1.3

Keine inhaltlichen Änderungen.


### OPS.1.1.4

Keine inhaltlichen Änderungen.


### OPS.1.1.5

<details> 
<summary> Änderungen
</summary>

#### Standard-Anforderungen

#### OPS.1.1.5.A6

__Geändert:__

Alle gesammelten sicherheitsrelevanten Protokollierungsdaten SOLLTEN an einer zentralen Stelle gespeichert werden.

</details>

### OPS.1.1.6.

<details> 
<summary> Änderungen
</summary>

#### Basis-Anforderungen

#### OPS.1.1.6.A11

__Geändert:__

OPS.1.1.6.A11 Verwendung von anonymisierten oder pseudonymisierten Testdaten [Datenschutzbeauftragter,Tester] (B)

Wenn Produktivdaten für Software-Tests verwendet werden, die schützenswerte Informationen enthalten, dann MÜSSEN diese Testdaten angemessen geschützt werden.

Enthalten diese Daten personenbezogene Informationen, dann MÜSSEN diese Daten mindestens pseudonymisiert werden.


__Hinzugefügt:__

Falls möglich, SOLLTEN die Testdaten mit Personenbezug vollständig anonymisiert werden.

#### Standard-Anforderungen

#### OPS.1.1.6.A6

__Geändert:__

Die Software-Tester SOLLTEN über die durchzuführenden Testarten und die zu testenden Bereiche einer Software vom Fachverantwortlichen informiert werden.

#### OPS.1.1.6.A7

__Geändert:__

Wird Individualsoftware auf Quellcode-Ebene überprüft, dann SOLLTEN die Tester über ausreichendes Fachwissen über die zu testenden Programmiersprache und die Entwicklungsumgebung verfügen.

Der Quellcode SOLLTE NICHT ausschließlich von Testern überprüft werden, die auch an der Erstellung des Quellcodes beteiligt waren.

</details>

### NEU: OPS.1.1.7

Der Baustein wurde neu hinzugefügt.

### OPS.1.2.2

Keine inhaltlichen Änderungen.


### OPS.1.2.4

Keine inhaltlichen Änderungen.


### OPS.1.2.5

<details> 
<summary> Änderungen
</summary>

#### Basis-Anforderungen

#### OPS.1.2.5.A2

__Geändert:__

Wird per Fernwartung auf Desktop-Umgebungen von Clients zugegriffen, MUSS der Benutzer des IT-Systems diesem Zugriff explizit zustimmen.

#### Standard-Anforderungen

#### OPS.1.2.5.A24

__Geändert:__

Die Fernwartungsfunktionen SOLLTEN nur aus einem getrennten Managementnetz erreichbar sein.


#### OPS.1.2.5.A25

__Geändert:__

OPS.1.2.5.A25 Entkopplung der Kommunikation bei der Fernwartung (S)

Direkte Fernwartungszugriffe eines Administrators von einem Fernwartungs-Client außerhalb der Managementnetze auf ein IT-System SOLLTEN vermieden werden.

Der Zugriff auf Sprungserver SOLLTE nur von vertrauenswürdigen IT-Systemen aus möglich sein.

#### Anforderungen bei erhöhtem Schutzbedarf

#### OPS.1.2.5.A14

__Hinzugefügt:__

Die Netzkommunikation der Administrationssysteme SOLLTE so eingeschränkt werden, dass nur Verbindungen zu IT-Systemen möglich sind, die administriert werden sollen.

</details>

### NEU: OPS.1.2.6

Der Baustein wurde neu hinzugefügt.


### OPS.2.1

Keine inhaltlichen Änderungen.


### OPS.2.2

Keine inhaltlichen Änderungen.


### OPS.3.1

Keine inhaltlichen Änderungen.

---


## DER

Keine inhaltlichen Änderungen

---


## APP

### APP.1.1

Keine Inhaltlichen Änderungen


### APP.1.2

Keine Inhaltlichen Änderungen


### APP.1.4

Keine Inhaltlichen Änderungen


### APP.2.1

Keine Inhaltlichen Änderungen


### APP.2.2

Keine Inhaltlichen Änderungen


### APP.2.3

Keine Inhaltlichen Änderungen


### APP.3.1

<details> 
<summary> Änderungen
</summary>

#### Basis-Anforderungen

#### APP.3.1.A1

__Geändert:__

APP.3.1.A1 Authentisierung (B)

Der IT-Betrieb MUSS Webanwendungen und Webservices so konfigurieren, dass sich Benutzer gegenüber der Webanwendung oder dem Webservice authentisieren müssen, wenn diese auf geschützte Ressourcen zugreifen wollen.

#### APP.3.1.A4

__Geändert:__

APP.3.1.A4 Kontrolliertes Einbinden von Dateien und Inhalten (B)

Falls eine Webanwendung oder ein Webservice eine Upload-Funktion für Dateien anbietet, MUSS diese Funktion durch den IT-Betrieb so weit wie möglich eingeschränkt werden.


#### APP.3.1.A7

__Geändert:__

APP.3.1.A7 Schutz vor unerlaubter automatisierter Nutzung (B)

Der IT-Betrieb MUSS sicherstellen, dass Webanwendungen und Webservices vor unberechtigter automatisierter Nutzung geschützt werden.

Dabei MUSS jedoch berücksichtigt werden, wie sich die Schutzmechanismen auf die Nutzungsmöglichkeiten berechtigter Benutzer auswirken.

Wenn die Webanwendung RSS-Feeds oder andere Funktionen enthält, die explizit für die automatisierte Nutzung vorgesehen sind, MUSS dies ebenfalls bei der Konfiguration der Schutzmechanismen berücksichtigt werden.


#### APP.3.1.A14

__Geändert:__

Der IT-Betrieb MUSS sicherstellen, dass Zugangsdaten zur Webanwendung oder zum Webservice serverseitig mithilfe von sicheren kryptografischen Algorithmen vor unbefugtem Zugriff geschützt werden.

Die Dateien mit den Quelltexten der Webanwendung oder des Webservices MÜSSEN vor unerlaubten Abrufen geschützt werden.

#### Standard-Anforderungen

#### APP.3.1.A8

__Geändert:__

APP.3.1.A8 Systemarchitektur [Beschaffungsstelle] (S)

Sicherheitsaspekte SOLLTEN bereits während der Planung von Webanwendungen und Webservices betrachtet werden.

Auch SOLLTE darauf geachtet werden, dass die Architektur der Webanwendung oder des Webservice die Geschäftslogik der Institution exakt erfasst und korrekt umsetzt.


#### APP.3.1.A9

__Geändert:__

APP.3.1.A9 Beschaffung von Webanwendungen und Webservices (S)

Zusätzlich zu den allgemeinen Aspekten der Beschaffung von Software SOLLTE die Institution mindestens Folgendes bei der Beschaffung von Webanwendungen und Webservices berücksichtigen:

• sichere Eingabevalidierung und Ausgabekodierung,

• geeignetes Berechtigungsmanagement,

• Schutzmechanismen vor verbreiteten Angriffen auf Webanwendungen und Webservices sowie

• Zugriff auf den Quelltext der Webanwendung oder des Webservices.


#### APP.3.1.A12

__Geändert:__

APP.3.1.A12 Sichere Konfiguration (S)

Webanwendungen und Webservices SOLLTEN so konfiguriert sein, dass auf ihre Ressourcen und Funktionen ausschließlich über die vorgesehenen, abgesicherten Kommunikationspfade zugegriffen werden kann.

Folgendes SOLLTE bei der Konfiguration von Webanwendungen und Webservices umgesetzt werden:


#### APP.3.1.A22

__Geändert:__

Webanwendungen und Webservices SOLLTEN regelmäßig auf Sicherheitsprobleme hin überprüft werden.

#### Anforderungen bei erhöhtem Schutzbedarf

#### APP.3.1.A20

__Geändert:__

Die Konfiguration der eingesetzten WAF SOLLTE auf die zu schützende Webanwendung oder den Webservice angepasst werden.

Nach jedem Update der Webanwendung oder des Webservices SOLLTE die Konfiguration der WAF geprüft werden.

</details>

### APP.3.2

Keine inhaltlichen Veränderungen.


### APP.3.3

Keine inhaltlichen Veränderungen.


### APP.3.4

<details> 
<summary> Änderungen
</summary>

#### Basis-Anforderungen

#### APP.3.4.A1

__Geändert:__

Soll IPv6 unter Samba eingesetzt werden, MUSS auch dies sorgfältig geplant werden.

Zudem MUSS in einer betriebsnahen Testumgebung überprüft werden, ob die Integration fehlerfrei funktioniert.


</details>

### APP.3.6

Keine inhaltlichen Veränderungen.


### APP.4.2

Keine inhaltlichen Veränderungen.


### APP.4.3

<details> 
<summary> Änderungen
</summary>


#### Anforderungen bei erhöhtem Schutzbedarf

#### APP.4.3.A25

__Geändert:__

APP.4.3.A25 Sicherheitsprüfungen von Datenbanksystemen (H)

Datenbanksysteme SOLLTEN regelmäßig mithilfe von Sicherheitsprüfungen kontrolliert werden.

Bei den Sicherheitsprüfungen SOLLTEN die systemischen und herstellerspezifischen Aspekte der eingesetzten Datenbank-Infrastruktur (z. B. Verzeichnisdienste) sowie des eingesetzten Datenbankmanagementsystems betrachtet werden.

</details>

### NEU: APP.4.4

Der Baustein wurde neu hinzugefügt.


### APP.4.6

Keine inhaltlichen Änderungen


### APP.5.2

Keine inhaltlichen Änderungen


### APP.5.3

Keine inhaltlichen Änderungen


### APP.6

<details> 
<summary> Änderungen
</summary>

#### Standard-Anforderungen

#### APP.6.A8

__Geändert:__

Hierzu SOLLTE der IT-Betrieb

Zusätzlich SOLLTE sichergestellt werden, dass Software reproduzierbar konfiguriert werden kann.

Hierzu SOLLTEN die Konfigurationsdateien gesichert werden.

Alternativ SOLLTE geeignet dokumentiert werden, wie die Software konfiguriert wird.

Diese Regelung SOLLTE in das Datensicherungskonzept der Institution integriert werden.

</details>

### APP.7

Keine inhaltlichen Änderungen


---



## SYS


### SYS.1.1

<details> 
<summary> Änderungen
</summary>

#### Basis-Anforderungen

#### SYS.1.1.A1

__Geändert:__

• administrative Zugänge (siehe SYS.1.1.A5 Schutz von Schnittstellen),

• Protokollierung (siehe SYS.1.1.A10 Protokollierung),

• Aktualisierung von Betriebssystem und Anwendungen sowie

#### Standard-Anforderungen

#### NEU: SYS.1.1.A37 

Diese Anforderung wurde neu hinzugefügt.

#### Anforderungen bei erhöhtem Schutzbedarf

#### SYS.1.1.A31

__Geändert:__

SYS.1.1.A31 Einsatz von Ausführungskontrolle (H)

Es SOLLTE über eine Ausführungskontrolle sichergestellt werden, dass nur explizit erlaubte Programme und Skripte ausgeführt werden können.

Die Regeln SOLLTEN so eng wie möglich gefasst werden.

Falls Pfade und Hashes nicht explizit angegeben werden können, SOLLTEN alternativ auch zertifikatsbasierte oder Pfad-Regeln genutzt werden.


#### SYS.1.1.A36

__Geändert:__

Nicht benötigtes Schlüsselmaterial SOLLTE entfernt werden.


#### SYS.1.1.A38

Anforderung ist neu hingefüt.

</details>

### SYS.1.2.2

Keine inhaltlichen Änderungen.


### SYS.1.3

Keine inhaltlichen Änderungen.


### SYS.1.5

<details> 
<summary> Änderungen
</summary>

#### Standard-Anforderungen

#### SYS.1.5.A17

__Entfallen:__

*Auch SOLLTE überwacht werden, ob die virtuellen Netze den jeweiligen virtuellen IT-Systemen korrekt zugeordnet sind.*

</details>

### NEU: SYS.1.6

Baustein komplett neu hinzugefügt.


### SYS.1.7

In den Anforderungen des Bausteins wird anstatt von MVS- , von z/OS- gesprochen.

<details> 
<summary> Änderungen
</summary>

#### Basis-Anforderungen

#### SYS.1.7.A1

__Geändert:__

Zugänge über Webserver und andere Fernzugänge MÜSSEN durch Verschlüsselung geschützt werden.


__Hinzugefügt:__

Nicht benötigte Webserver und Fernzugänge MÜSSEN deaktiviert werden, wenn sie nicht benötigt werden.


#### SYS.1.7.A6

__Geändert:__
  
Die RSF-Kommunikation MUSS über Proxy-Server und zusätzlich über gesicherte Verbindungen (wie TLS) stattfinden.


#### SYS.1.7.A8

__Hinzugefügt:__

Falls RACF PassTickets verwendet werden, MUSS der Enhanced PassTicket Algorithmus aktiviert werden.

#### Standard-Anforderungen

#### SYS.1.7.A22

__Geändert:__

SDSF (System Display and Search Facility) und ähnliche Funktionen sowie die Prioritäten-Steuerung für Jobs SOLLTEN mittels RACF vor unberechtigtem Zugriff geschützt werden.


#### SYS.1.7.A23

__Hinzugefügt:__

Passwörter von realen Usern und Guest-Usern SOLLTEN mittels RACF für z/VM verschlüsselt werden.

</details>

### SYS.1.8

Keine inhaltlichen Veränderungen.


### SYS.2.1

<details> 
<summary> Änderungen
</summary>

#### Standard-Anforderungen

#### NEU: SYS.2.1.A34

Anforderung wurde komplett neu hinzugefügt.

#### Anforderungen bei erhöhtem Schutzbedarf

#### SYS.2.1.A31

__Geändert:__

Es SOLLTE eine Strategie zur Paketfilter-Implementierung gewählt werden, die nur benötigte Netzkommunikation explizit erlaubt.


#### SYS.2.1.A33

__Geändert:__

SYS.2.1.A33 Einsatz von Ausführungskontrolle (H)

Es SOLLTE über eine Ausführungskontrolle sichergestellt werden, dass nur explizit erlaubte Programme und Skripte ausgeführt werden können.

</details>

### SYS.2.2.2

Keine inhaltlichen Änderungen.


### SYS.2.2.3

<details> 
<summary> Änderungen
</summary>

#### Basis-Anforderungen

#### SYS.2.2.3.A4

__Geändert:__

Diese können nur unter Windows 10 Enterprise mit der Einstellung des Telemetrielevels 0 (Security) stark reduziert werden.

Wenn diese Einstellung nicht wirksam umgesetzt werden kann, dann MUSS durch geeignete Maßnahmen, etwa auf Netzebene, sichergestellt werden, dass diese Daten nicht an den Hersteller übertragen werden.


#### SYS.2.2.3.A5

__Geändert:__

Sofern nicht gleich- oder höherwertige Maßnahmen, wie z. B. Ausführungskontrolle, zum Schutz des IT-Systems vor einer Infektion mit Schadsoftware getroffen wurden, MUSS eine spezialisierte Komponente zum Schutz vor Schadsoftware auf Windows 10-Clients eingesetzt werden.

#### Standard-Anforderungen

#### ENTFALLEN: SYS.2.2.3.A11

__Ehemals:__

*SYS.2.2.3.A11 Schutz der Anmeldeinformationen unter Windows 10 (S)*

*Sofern Windows 10 in der Enterprise-Version auf einem Hardware-System direkt (nativ) installiert ist, SOLLTE der Virtual Secure Mode (VSM) aktiviert werden.*

*Zusätzlich SOLLTE der Windows Defender Credential Guard gegen Angriffe auf die im System gespeicherten Authentisierungstoken und -hashes aktiviert werden.*

*Ist dies nicht möglich, SOLLTE der Schutz des Local Credential Store LSA aktiviert werden (PPL, Protected Mode Light).*

*Die Netzanmeldung von lokalen Konten SOLLTE verboten werden.*

</details>

### SYS.2.3

Keine inhaltlichen Änderungen


### SYS.2.4

Keine inhaltlichen Änderungen


### SYS.3.1

Keine inhaltlichen Änderungen


### SYS.3.2.1

Keine inhaltlichen Änderungen


### SYS.3.2.2

Keine inhaltlichen Änderungen


### SYS.3.2.3

Keine inhaltlichen Änderungen


### SYS.3.2.4

Keine inhaltlichen Änderungen


### SYS.3.3

Keine inhaltlichen Änderungen


### SYS.4.1

Keine inhaltlichen Änderungen


### SYS.4.3

Keine inhaltlichen Änderungen


### SYS.4.4

Keine inhaltlichen Änderungen


### SYS.4.5

Keine inhaltlichen Änderungen



---



## IND

### NEU: IND.3.2

Baustein ist komplett neu hinzugefügt.



---


## NET

Keine inhaltlichen Änderungen.



---


## INF

### INF.1

Keine inhaltlichen Änderungen.


### INF.2

<details> 
<summary> Änderungen
</summary>

#### Anforderungen bei erhöhtem Schutzbedarf

#### INF.2.A23

__Geändert:__

Trassen SOLLTEN hinsichtlich Anordnung und Dimensionierung so ausgelegt sein, dass eine Trennung der Spannungsebenen sowie eine sinnvolle Verteilung von Kabeln auf den Trassen möglich sind und dass auch für zukünftige Bedarfsmehrung ausreichend Platz zur Verfügung steht.

</details>

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

Keine inhaltlichen Änderungen.


### INF.11

Keine inhaltlichen Änderungen.


### INF.12

Keine inhaltlichen Änderungen.



### NEU: INF.13

Baustein ist komplett neu hinzugefügt.


### NEU: INF.14

Baustein ist komplett neu hinzugefügt.


---


Quellen:

[BSI IT Grundschutz Kompendium Edition 2021](https://www.bsi.bund.de/SharedDocs/Downloads/DE/BSI/Grundschutz/Kompendium/IT_Grundschutz_Kompendium_Edition2021.pdf)

[BSI IT Grundschutz Kompendium Edition 2022](https://www.bsi.bund.de/SharedDocs/Downloads/DE/BSI/Grundschutz/Kompendium/IT_Grundschutz_Kompendium_Edition2022.pdf)
