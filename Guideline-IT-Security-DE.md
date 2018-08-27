Leitfaden IT-Sicherheit
==============

A) Metainformationen
----------------

### 1. Ziele des Leitfadens

Dieser Leitfaden hat das Ziel, Herstellern und benannten Stellen eine Handlungsleitung und eine konkrete Checkliste an die Hand zu geben, um 

- zu verstehen, was die Erwartungen der benannten Stellen sind,
- die schrittweise Umsetzung der IT-Sicherheit der Produkte zu befördern,
- das Fehlen einer harmonierten Norm (zwischenzeitlich) bestmöglich zu kompensieren.

Der Leitfaden hat **nicht** die Zielsetzung, als Lehrbuch oder Leitfaden für das Erreichen der IT-Sicherheit zu dienen. Vielmehr möchte er ein Leitfaden für deren Überprüfung sein.

### 2. Anwendungsbereich

Dieser Leitfaden wendet sich an Hersteller vernetzbarer Medizinprodukte und deren Dienstleister sowie an Personen und Organisation, die die IT-Sicherheit dieser Produkte bewerten müssen.

Er hat die IT-Sicherheit der Produkte im Fokus, nicht die IT-Sicherheit der Organisation. 

Der Leitfaden ist auch geeignet, um die technischen Maßnahmen zu bewerten, die der vom Datenschutz gefordert werden. Dennoch liegt der Schwerpunkt auf der Patientensicherheit, nicht der Vertraulichkeit von Daten.

### 3. Hinweise zur Verwendung 

#### a) Anwendbare Kapitel

Die Hersteller sollten den Leitfaden zuerst nutzen, um die Vollständigkeit der Vorgabedokumente (Verfahrens- und Arbeitsanweisungen, Checklisten usw.) zu prüfen. Dazu sollten sie die Kapitel B) bis D) berücksichtigen.

Anschließend sollten sie sowie die Personen, die produktspezifisch die IT-Sicherheit bewerten (u.a. interne und externe Auditoren und Prüfer der technischen Dokumentation), den Leitfaden nutzen, um für das jeweilige Produkt die IT-Sicherheit zu bewerten. In diesem Fall können sie die Kapitel C) und D) dieses Leitfadens als Checkliste nutzen.

Dieser Leitfaden enthält Anforderungen, die nicht bei allen Produkten anwendbar sind. Hersteller begründen die Ausschlüsse, die nicht offensichtlich sind.

#### b) Priorisierung

Sollten die Hersteller nicht alle Anforderungen dieses Leitfadens von Beginn an erfüllen können, sollten so möglich und sinnvoll die Anforderungen in der Reihenfolge deren Priorität (zuerst Stufe 0, zum Schluss Stufe 3) erfüllen. Diese Stufen beschreibt der Anhang.

#### c) Kommentare

Der Leitfaden enthält zu den meisten Anforderungen "Kommentare". Diese Kommentare umfassen Begründungen, Referenzen, Anmerkungen und v.a. Tipps für Auditoren und Reviewer.

#### d) Verbindlichkeit

Dieser Leitfaden weder eine gesetzliche Anforderung noch eine harmonisierte Norm. Entsprechend unterscheidet er auch nicht zwischen normativen und informativen Elementen.

Vielmehr trägt der Leitfaden Best-Practices zusammen, um den gesetzlich geforderten "State-of-the-Art" bestmöglich zu beschreiben. 

### 4. Autoren und Nutzungsrechte

Diesen Leitfaden haben die folgenden Autoren verfasst:

- Dr. Andreas Purde (TÜV SÜD)
- Olaf Teichert (TÜV SÜD)
- Prof. Dr. Christian Johner (Johner Institut)
- Georg Heidenreich (SIEMENS Healthineers)

Der Leitfaden ist unter der [Creative Commons Lizenz](https://creativecommons.org/licenses/?lang=de) vom Typ [BY-NC-SA](https://creativecommons.org/licenses/by-nc-sa/4.0/) veröffentlicht. Diese erfordert die Namensnennung der Autoren ("TÜV SÜD und Johner Institut") und erlaubt es, Dritten auf diesem Werk aufzubauen z.B. es zu verbessern; letzteres allerdings nur zu nicht-kommerziellen Zwecken.

Die Lizenz gestattet es, das Produkt zu Beratungszwecken einschließlich Audits kommerziell einzusetzen. Sie untersagt es aber, dieses Werk selbst in unveränderter oder veränderter Version kommerziell zu nutzen z.B. in Form eines Verkaufs als Broschüre.


### 5. Dokumentenlenkung, Dokumentenidentifikation

Dieses Dokument wird über das Versionsverwaltungssystem git bzw. die Plattform GitHub verwaltet. Einzig die in diesem Repository genannten Dokumente sind gültig.

Die Versionshistorie einschließlich der jeweiligen Autoren kann der Dokumentenhistorie entnommen werden.

Die freigegebenen Versionen sind über ein Tag im Repository als solche gekennzeichnet. Versionen ohne Tag sind Dokumente im Entwurfsstadium.


B) Allgemeine Anforderungen
---------------

TODO: All diese Anforderungen in binär entscheidbare Prüfkriterien überführen!

### 1. Prozesse

Die Hersteller sollten alle unten genannten Aspekte entweder in den Verfahrensanweisungen oder in den entsprechenden Plänen abdecken, um zu gewährleisten, dass die IT-Sicherheit systematisch gewährleistet wird. Üblicherweise sind die folgenden Verfahrensanweisungen bzw. Pläne betroffen:

- Entwicklung
- Risikomanagement
- Verifizierung und Validierung (falls nicht Teil der Entwicklung)
- Marktbeobachtung (Post-Market Surveillance) und Vigilanz
- Service, Installation
- Kundenkommunikation
- Managementbewertung (ISO 13485 fordert "anwendbare neue oder überarbeitete regulatorische Anforderungen" zu berücksichtigen.)

Nutzt der Hersteller ausgelagerte Prozesse, so gelten die Anforderungen entsprechend. Beispielsweise müsste ein (Software-)Entwicklungsdienstleister verpflichtet werden, die Anforderungen dieser Leitlinie zu beachten.

### 2. Kompetenzen

Die Hersteller müssen sicherstellen und nachweisen, dass sie über ausreichend Kompetenzen verfügen, um eine State-of-the-Art IT-Security zu gewährleisten. Diese Nachweise gelingen oft am leichtesten durch interne oder externe Schulungen.

Hersteller können dabei auch auf die Kompetenz externer Ressourcen zugreifen. 

### 3. Dokumentation

Die Hersteller sollten den Nachweis führen können, die relevanten Anforderungen dieser Leitlinie beachtet zu haben. Es gibt keine spezifischen Anforderungen an die Dokumentation und "Objective Evidenz".

Es besteht in Europa (im Gegensatz zu den USA) auch keine Pflicht, ein spezifisches Dokument zur IT-Sicherheit zu erstellen. Vielmehr können Hersteller diese Aspekte in bereits bestehenden Dokumenten wie den Vorgabedokumenten des QM-Systems und der technischen Dokumentation (z.B. Software-Akte, Risikomanagementakte) integrieren.


C) Anforderungen an die Produktentwicklung
--------------

### 1. Zweckbestimmung und Stakeholder-Anforderungen

|ID|Anforderung|Stufe|Kommentare|
|:--:|:--|:--:|:--|
||Der Hersteller hat alle Nachbarsysteme (Medizinprodukte, IT-Systeme) bestimmt, die mit dem Produkt verbunden werden dürfen.|||
||Der Hersteller hat eine Liste an Rollen erstellt (Personen, Nachbarssysteme), die mit dem Produkt interagieren dürfen||Liste der Rollen zeigen lassen|
||Der Hersteller hat alle Märkte und alle dort relevanten regulatorischen Anforderungen festgelegt||sich die Liste der regulatorischen Anforderungen mit Bezug zur IT-Sicherheit zeigen lassen|
||Der Hersteller hat die vorgesehenen primären und sekundären Benutzer mit ihren IT-Kompetenzen festgelegt[^C1-01]|||
||Der Hersteller hat die vorgesehenen Nutzungsumgebung festgelegt[^C1-02]|||
||Der Hersteller hat die Risiken analysiert, die folgen, wenn die nicht die spezifizierten Benutzer in der spezifizierten Benutzungsumgebung mit dem System arbeiten [^C1-03]|||
||Der Hersteller hat im Risikomanagement beschrieben, welche Bedrohungen für die IT-Sicherheit bestehen und was die Folgen für Patienten, Anwender und Dritte wären|||hier nach internen und externen, absichtlichen/böswilligen und unabsichtlichen Bedrohungen fragen|
||Der Hersteller hat die Risikoakzeptanzkriterien nachvollziehbar aus dem Nutzen des Produkts und dem State-of-the-Art abgeleitet|||
||Der Hersteller hat ein System entwickelt, mit dem er IT-Sicherheitsbezogene Risiken bewerten kann[^C1-04]|2||

[^C1-01]: Primäre Benutzer sind diejenigen, die das System im Sinne der medizinischen Zweckbestimmung anwenden. Sekundäre Benutzer sind alle anderen Personen, die das Produkt im bestimmungsgemäßen Gebrauch nutzen z.B. bei der Installation, Konfiguration, Update/Upgrade

[^C1-02]: Beispiele finden sich in der Sektion zum Labeling 

[^C1-03]: Beispiele: Der Betreiber hat keinen Virenschutz installiert. Benutzer teilen sich ein Passwort.

[^C1-04]: Beispiele für solche Klassifikationssystem sind [DREAD](TODO) und [CVSS](TODO). Allerdings haben diese keinen Bezug zur "Safety".

### 2. System- und Software-Anforderungen

#### a) Authentifizierung und Autorisierung 

##### i) Dokumentation

|ID|Anforderung|Stufe|Kommentare|
|:--:|:--|:--:|:--|
||Der Hersteller hat alle Datenschnittstellen identifiziert||Liste der Datenschnittstellen zeigen lassen|
||Der Hersteller hat für jede Datenschnittstellen die Funktionen spezifiziert, die über die jeweilige Schnittstelle angeboten werden||Liste der Funktionen zeigen lassen|
||Der Hersteller hat die Sicherheitsrelevanz aller Funktionen analysiert.|||
||Der Hersteller hat die Auswirkungen sicherheitsrelevanter Funktionen im Risikomanagement dokumentiert|||
||Der Hersteller hat für jedes Benutzungsszenario oder für jede zusammengehörende Gruppe an UI-Elementen (z.B. Bildschirmseiten, Panels) eine Liste an Funktionen spezifiziert, die im Rahmen dieses Benutzungsszenarios oder über diese Gruppe an UI-Elementen angeboten werden||Liste der Benutzungsszenarien oder die UI-Spezifikation (z.B. Mockup-Screens) zeigen lassen|
||Der Hersteller hat für jede Rolle und jedes Nachbarsystem die Funktionen des Produkts bestimmt, auf die sie über die jeweilige Schnittstelle zugreifen darf ||"Mapping" von Rollen auf Funktionen zeigen lassen z.B. in Form einer Tabelle|
||Der Hersteller hat die Wahl des Authentifizierungsverfahren (Benutzername / Passwort, Biometrisches Verfahren, Token z.B. Karte) für alle Rollen und alle Nachbarsysteme begründet |1|Die Begründung sollte risikobasiert sein|
||Der Hersteller hat ggf. weitere Mechanismen gefordert, um die Wahrscheinlichkeit unautorisierter Zugriffe zu minimieren [^C2a-01]|||
||Der Hersteller hat im Risikomanagement die Auswirkungen für die Patientensicherheit analysiert, wenn eine Person nicht auf Patientendaten zugreifen kann (z.B. keine Berechtigung, Passwort vergessen), und entsprechende Maßnahmen definiert||Hier geht es um die Abwägung der Schutzziele "Vertraulichkeit" versus "Safety"|

[^C2a-01]: z.B. Einschränkung erlaubter IP- oder MAC-Adressen

##### ii) Produkt

|ID|Anforderung|Stufe|Kommentare|
|:--:|:--|:--:|:--|
||Das Produkt erlaubt den Benutzern nur dann seine Nutzung, wenn sie sich am Produkt authentifiziert haben|0|Zugehörige Testfälle zeigen lassen apu: sehe ich für manche Produkte kritisch|
||Das Produkt erlaubt an jeder Datenschnittstelle den daran angeschlossenen Nachbarsystemen (z.B. andere Medizinprodukte, IT-Systeme), nur dann mit ihm Daten auszutauschen, wenn diese vom Produkt authentifiziert wurden|0|dto.|
||Das Produkt erlaubt eine Authentifizierung mit Passwort nur, wenn dieses Passwort eine Länge von 6 Zeichen hat von denen mindestens eines ein nicht alphanumerisches Zeichen ist und das mindestens einen Groß- und einen Kleinbuchstaben enthält [^C2a-02]|1||
||Das Produkt hat kein Default-Passwort oder verlangt, dass ein solches bei der ersten Nutzung geändert wird|0||
||Das Produkt sperrt Benutzer und Nachbarsysteme nach n Versuchen für m Minuten aus, wobei der Hersteller n und m Werte oder Untergrenzen festlegt|1||
||Das Produkt logged Benutzer und Nachbarsysteme nach n Minuten Inaktivität aus, wobei der Hersteller für n den Wert oder dessen Obergrenze festlegt|||
||Das Produkt weist jedem Benutzer und jedem Nachbarsystem bei der Authentifizierung eine Rolle zu|1|Erklären lassen, in welcher/welchen Software-Komponente(n) Komponenten diese Funktionalität implementiert und wie dies geprüft ist|
||Das Produkt erlaubt jeder Rolle den Zugriff auf nur die Funktionen, für die die sie berechtigt ist. Dies gilt insbesondere auch für das Update/Upgrade des Produkts|1|dto.|
||Das Produkt erlaubt berechtigten Benutzern, andere Benutzer und Nachbarsysteme zu sperren|1||
||Das Produkt erlaubt berechtigten Benutzern, die Passwörter anderer Benutzer und Nachbarsysteme zurückzusetzen|1||
||Das Produkt erlaubt berechtigten Benutzern, andere Benutzer und Nachbarsysteme zu löschen|1||
||Das Produkt erlaubt es Benutzern nicht, die eigene Berechtigung zu ändern|||
||Das Produkt erlaubt es, Berechtigungen auszuhebeln ("Breaking the glas"), und identifiziert / dokumentiert die Person und die Gründe|||
||In einer Client-Server Architektur werden alle Cyber-Sicherungsmaßnahmen serverseitig berechnet und geprüft|||
||In einer Client-Server Architektur werden alle Eingaben des Clients serverseitig geprüft|||

[^C2a-02]: Idealerweise müssten auch Passwörter ausgeschlossen werden, die über Wörterbuch-Angriffe erraten werden können.

#### b) Daten, Kommunikation

##### i) Dokumentation

|ID|Anforderung|Stufe|Kommentare|
|:--:|:--|:--:|:--|
||Der Hersteller hat eine Liste aller vom System verwalteten Daten [^C2b-01] erstellt|||
||Der Hersteller hat die Schutzwürdigkeit dieser Daten mit Bezug zur Vertraulichkeit und deren Auswirkung auf die Patientensicherheit bewertet.|||
||Der Hersteller hat im Risikomanagement die Auswirkungen bewertet, wenn der Schutz besonders schützenswerter Daten nicht mehr gegeben ist|||
||Der Hersteller hat im Risikomanagement die Folgen einer Überlastung des Systems durch zu viele Anfragen (z.B. DoS) oder Anfragen mit zu großen Daten-Volumina untersucht und falls notwendig Maßnahmen definiert|||
||Der Hersteller hat allgemein oder produktspezifisch festgelegt, nach welchen Überprüfungskriterien[^C2b-02] externe Daten vor der weiteren Verarbeitung überprüft werden müssen|||

[^C2b-01]: Beispiele für solche Daten sind Patientendaten (z.B. demographische Daten, Anamnesen, Diagnosen), Untersuchungsdaten (z.B. Laborwerte, radiologische und pathologische Bilder) und Behandlungsdaten (Verschreibungen, Einstellungen von Medizingeräten), Konfigurationsdaten der Produkte, Daten der Anwender (insbesondere Zugangsdaten), Programm-Code.

[^C2b-02]: Beispiele für Überprüfungen: Überprüfung auf falsche Länge, auf Vollständigkeit, auf falschen Zeichensatz, auf nicht erwartete Zeichen, auf mehrfach geschickte Daten, auf veraltete / verspätete Daten, nicht erwartete oder falsche Formate (z.B. kein Escaping von Zeichen mit besonderer Bedeutung wie Trennzeichen, kein wohlgeformtes XML, ungültige JSON-Dateien, falsche Datentypen, XML, das nicht dem spezifizierten Schema entspricht), andere Zeichensätze, im Input enthaltene Schlüsselworte, BigEndian statt Little Endian, Werte, die nicht im vorgesehenen Wertebereich enthalten sind (z.B. im Klassifikations- oder Kodiersystem), falsche Zeitzone, falsches Zahlenformat, unmögliche Daten (z.B. Geburtstag in der Zukunft) usw.


##### ii) Produkt

|ID|Anforderung|Stufe|Kommentare|
|:--:|:--|:--:|:--|
||Das System erlaubt es berechtigten Benutzern, alle patientenspezifischen Daten zu löschen|2||
||Das System übermittelt Daten, zumindest sicherheitsbezogene Daten, über seine Datenschnittstellen nur in verschlüsselter Form|1|Nachfragen, welche Verschlüsselung zum Einsatz kommt und wie der initiale Schlüsselaustausch realisiert ist|
||Das System sichert die Integrität der Daten vor ungewollter Veränderung z.B. durch kryptographische Verfahren|2|Das gilt insbesondere für den Programm-Code.|
||Das System überprüft alle Benutzereingaben und alle eingehenden Daten vor der weiteren Verarbeitung anhand von Hersteller festgelegten Überprüfungskriterien (s.o.)||Jeweils ein Beispiel für einen Dateninput an der Benutzer- und an der Datenschnittstelle auswählen und sich die Überprüfung im Code zeigen lassen|
||Das System speichert Passwörter und personenidentifizierende Merkmale nur verschlüsselt|||



### c) Patches

##### i) Dokumentation

|ID|Anforderung|Stufe|Kommentare|
|:--:|:--|:--:|:--|
||Der Hersteller verfügt über eine dokumentierte Planung, wie Patches aufgespielt und wieder entfernt werden. Dieser Plan beinhaltet die Entwicklung, die Verteilung, die Installation und Überprüfung der Patches.||Dieser Plan kann Teil des Incident Response Plans sein (s.u.)|
||Der Hersteller verfügt eine Liste aller SOUP-/OTS-Komponenten|1|Diese Forderung zählt eher zum Kapitel "System- und Software-Architektur"|

##### ii) Produkt

|ID|Anforderung|Stufe|Kommentare|
|:--:|:--|:--:|:--|
||Das System erlaubt es, Patches (eigener Code, SOUP-/OTS-Komponenten) aufzuspielen|1|Hersteller sollte Ausnahmen begründen können, ebenso, ob das Patchen remote erfolgen darf oder muss|
||Das System erlaubt es, fehlerhafte Patches wieder zu entfernen|||
||Das System prüft geänderten Programm-Code (Patches) vor dessen ersten Ausführung auf Integrität.|2||
||Das System aktualisiert sich selbständig||Diese Anforderung ist etwas wage. Hersteller müssen Risiken, die durch solche "Auto-Updates" entstehen ebenfalls analysieren und beherrschen|

### d) Sonstiges

|ID|Anforderung|Stufe|Kommentare|
|:--:|:--|:--:|:--|
||Das System protokolliert alle wesentlichen Aktionen [^C3d-01] am/im System in einem Auditlog|||
||Das System schützt das Auditlog vor Veränderung||sich vom Hersteller erklären lassen, wie der Schutz gewährleistet wird und wie eine Änderung des Auditlogs vom System identifiziert wird. Ggf. sogar verantwortliche Software-Komponente zeigen lassen|
||Das System erkennt einen Einbruch oder Angriff [^C3d-02] und reagiert darauf [^C3d-03]|||

[^C3d-01]: z.B. erfolgreiche und nicht erfolgreiche Anmeldeversuche, Aufruf wesentlicher Funktionen (inklusive Ändern von Konfigurationseinstellungen), Aufspielen und Entfernen von Patches, Anlegen, Ändern und Löschen von Benutzern, Passwörtern und Berechtigungen

[^C3d-02]: Nicht so allgemein formulieren, sondern konkrete Systemanforderung spezifizieren z.B. System erkennt eine CPU-Auslastung größer x%, eine Datenverkehr größer y MB/s, ein Speichermedium, dass voller ist als z% usw.

[^C3d-03]: Ebenfalls sehr spezifisch formulieren, idealerweise über ein an den Schnittstellen beobachtbares Verhalten wie "schaltet sich aus", "deaktiviert die Datenverbindung", "zeigt folgende Warnmeldung an" usw.


### 3. System- und Software-Architektur

##### i) Dokumentation

|ID|Anforderung|Stufe|Kommentare|
|:--:|:--|:--:|:--|
||Der Hersteller hat alle SOUP-/ OTS-Komponenten dokumentiert (inkl. Version, Hersteller, Referenz auf Informationen zu Updates, Release-Notes)||Liste / Tabelle zeigen lassen|
||Der Hersteller hat die spezifischen Risiken, die sich durch die Wahl der Technologien (insbesondere Programmiersprache, SOUP- / OTS-Komponenten) ergeben analysiert.|2||
||Der Hersteller, die OTS-Betriebssysteme einsetzen, haben einer Liste aller Dienste [^C3-01] erstellt, die das Betriebssystem nach "außen" anbietet bzw. nutzt||sich diese Liste zeigen lassen|
||Der Hersteller hat für jeden Dienst begründet, weshalb dieser (zeitlich unbeschränkt) nach außen sichtbar sein muss||sich vom Hersteller erklären lassen, wie/wo gefordert und geprüft ist, dass nicht (zeitlich unbeschränkt) benötigte Dienste auch nicht (zeitlich unbeschränkt) angeboten werden. Ziel ist die "Attack Surface Reduction"|
||Wenn das Produkt eine USB-Schnittstelle anbietet, hat der Hersteller im Risikomanagement beschrieben, wie Angriffe über diese Schnittstelle beherrscht werden||eine völlige Beherrschung dieser Risiken ist i.d.R. kaum möglich, aber auch nicht notwendigerweise erforderlich|
||Der Hersteller hat für jede Funktion (siehe oben) den Prozess identifiziert, der diese Funktion anbietet / realisiert|2||
||Der Hersteller hat für jeden Prozess den Nutzer (auf Betriebssystemebene) identifiziert und begründet, wenn dieser mit maximalen Rechten (als Root) läuft|2||
||Der Hersteller hat Risiken durch mangelnde IT-Sicherheit systematisch durch ein Threat-Modeling abgeleitet. |2|Sich das Modell zeigen lassen, dass zumindest die externen Akteure und/oder Bedrohungen und die bedrohten Objekte erkennen lassen muss|
||Der Hersteller hat für alle Software-Komponenten [^C3-02], Dienste bzw. Prozesse, Daten und internen Funktionen analysiert, welche Risiken entstehen, wenn diese sich aufgrund eines Problems mit der IT-Sicherheit nicht spezifikationsgemäß verhalten ||Entspricht einem FMEA-Ansatz|
||Der Hersteller hat die Software-Anforderungen in der Software-Architektur berücksichtigt||Beispielhaft für o.g. Software-Anforderungen sich die Komponente(n) bzw. Technologien in der Architektur zeigen lassen, die die Anforderungen realisieren|

[^C3-01]: Beispiel für von Betriebssystemen üblicherweise angebotene Dienste: Webserver, RPC, Laufwerke (z.B. USB), Datenbank, DICOM, Dienste über Socket-Verbindungen

[^C3-02]: zumindest die Top-Level-Komponenten. Diese Komponenten entsprechen auch den Objekten

##### ii) Produkt / Software / Komponenten

|ID|Anforderung|Stufe|Kommentare|
|:--:|:--|:--:|:--|
||Die Software verwendet für alle kryptographischen Funktionen (z.B. Verschlüsselung, Signierung) ausschließlich bewährte Bibliotheken / Komponenten (keine eigene Implementierung)||die Bibliothek muss in der Liste der SOUP-/OTS-Komponenten enthalten sein. Vom Hersteller sich die Auswahl(kriterien) erklären lassen|
||Die Software ist vor Malware (Viren, Würmern usw.) geschützt|1|Sich erklären lassen, wo und wie der Virenschutz realisiert und aktualisiert wird.|
||Die Software basiert auf den aktuellsten Versionen der SOUP-/OTS-Komponenten||sich in SOUP-Liste ein Beispiel herauspicken und auf der Herstellerseite die aktuellste Version recherchieren|


### 4. Implementierung und Erstellung der Software

|ID|Anforderung|Stufe|Kommentare|
|:--:|:--|:--:|:--|
||Der Hersteller hat Coding-Guidelines erstellt, die Anforderungen spezifisch für die IT-Sicherheit stellt [^C4-01]|1|sich vom Hersteller die Coding-Guidelines und entsprechende Forderungen zeigen lassen|

[^C4-01]: Beispiele sind Code-Metriken (z.B. McCabe Maß), Vorgaben zur Dokumentation / Kommentierung des Codes und zu dessen Formatierung, ebenso das Verbot unsicherer Funktionen (in C "gets", "strcopy" und [weiterer Funktion](https://msdn.microsoft.com/library/bb288454.aspx)), zudem die Pflicht mit Annotationen (z.B. [SAL](TODO)) zu verwenden, um Buffer-Overflows zu vermeiden, die Pflicht, die Übergabeparameter auch für interne Schnittstellen grundsätzlich zu überprüfen usw.

### 5. Bewertung von Software-Einheiten

|ID|Anforderung|Stufe|Kommentare|
|:--:|:--|:--:|:--|
||Der Hersteller hat mindestens eine Methode festgelegt, mit der die Einhaltung der Coding-Guidelines überprüft wird||das wird dem Hersteller gelingen, wenn er Werkzeuge zur statischen Code-Analyse einsetzt und/oder Vorgaben für die Code-Reviews macht.|
||Der Hersteller verlangt Code-Reviews für alle Komponenten, die (IT-)sicherheitsrelevanten Funktionen abbilden|2||
||Der Hersteller hat konkrete Prüfkriterien[^C5-01] in seinen Vorgabedokumenten für die Code-Reviews |||
||Der Hersteller hat festgelegt, welche Tests (z.B. Unit-Tests) mit welchen Testfällen[^C5-02] und welchem zu erreichenden Abdeckungsgraden notwendig sind|1||
||Der Hersteller hat für alle SOUP- bzw. OTS-Komponenten beschrieben, wie diese zu verifizieren sind|||

[^C5-01]: Beispiele: Keine Verwendung unsicherer Funktionen, "Input-Sanitization" zumindest bei allen externen Schnittstellen

[^C5-02]: Beim Ableiten der Testfälle kann man sich an der o.g. Liste von Überprüfungskriterien orientieren.

### 6. System- und Software-Tests

|ID|Anforderung|Stufe|Kommentare|
|:--:|:--|:--:|:--|
||Der Hersteller sieht im Testplan [^9] Portscans an allen relevanten Datenschnittstellen vor und führt diese auch durch|1||
||Der Hersteller sieht im Testplan  Penetrationstests an allen relevanten Datenschnittstellen und/oder für alle bekannten Schwachstellen der eingesetzten OTS-Komponenten [^10] vor und führt diese auch durch|2|für eine bekannte OTS-Komponente in der [NIST Common Vulnerability Database](TODO)  eine Schwachstelle recherchieren und vom Hersteller erklären lassen, wie er sicherstellt, dass diese nicht ausgenutzt werden kann |
||Der Hersteller sieht im Testplan Fuzz-Tests an allen relevanten Datenschnittstellen mit mindestens einem Werkzeug vor und führt diese auch durch|2||
||Der Hersteller sieht im Testplan eine Simulation der üblichen Angriffsvektoren vor [^11]|||
||Der Hersteller sieht im Testplan die Überprüfung aller System-/Software-Anforderungen (s.o.) vor|||



[^9]: Dieser Plan kann Teil des Entwicklungsplans, eines V&V-Plans oder eines anderen Plans sein.

[^10]: Die Schwachstellen sind z.B. in der [NIST Common Vulnerability Database](TODO) hinterlegt

[^11]: z.B. DoS, SQL-Injection, Cross-Site-Scripting, Directory Transversal, Buffer-Overflow, syntaktisch oder semantisch fehlerhafte Anfragen,


### 7. Begleitmaterialien

|ID|Anforderung|Stufe|Kommentare|
|:--:|:--|:--:|:--|
||Die Gebrauchsanweisung legt die vorgesehene IT-Umgebung fest[^13]|1||
||Die Gebrauchsanweisung legt fest, welche Aktivitäten[^14] der Betreiber wie häufig durchführen müssen|1||
||Die Installations- und Service-Anleitungen legen fest, welche weiteren Rollen (Betreiber, Service-Techniker) welche Aktivitäten[^15] wie häufig durchführen müssen|1||
||Die Begleitmaterialien beschreiben, wie mit verlorengegangenen oder gestohlenen Produkten Tokens (z.B. Karten) sowie mit vergessenen Passwörtern umgegangen werden soll|||
||Die Begleitmaterialien beschreiben, wie die Anwender erkennen können, dass das Produkt ein Problem mit der IT-Sicherheit hat, und wie sie sich in diesem Fall verhalten sollen|||


Ggf. müssen die Hersteller auch Trainingsmaterialien bereithalten.

[^13]: Beispiele: Netzwerk (Bandbreite, Verfügbarkeit, Ports, IP-Ranges, Latenzen, Verschlüsselung, Firewalls usw.), Virenschutz, Betriebssysteme, physische Zugriffsberechtigungen, andere Software, die zeitgleich auf dem System laufen darf oder eben nicht (Spiele?, Firewall, Datenbank, Webserver)

[^14]: Beispiele: Ausbildung der Anwender (z.B. zum Umgang mit Passwörtern), Aktualisierung des Virenschutzes, Information des Herstellers über Zwischenfälle, Aufspielen von Updates und Patches, Monitoring

[^15]: Beispiele: Auswerten Auditlog, Löschen nicht benötigter Benutzer, Austausch von Schlüsseln oder Zertifikaten, Löschen von temporären Dateien

### 8. Produktfreigabe

|ID|Anforderung|Stufe|Kommentare|
|:--:|:--|:--:|:--|
||Der Hersteller hat die häufigsten Fehler [^20] in der Risikoanalyse adressiert oder kann zumindest darlegen, weshalb diese Risiken beherrscht sind||ein Beispiel aus einer der verlinkten Listen häufigster Fehler auswählen und den Hersteller um eine Begründung bitten|
||Der Hersteller diskutiert in der Risikoanalyse Risiken durch alle relevanten Angriffs-Vektoren (s.o.) und zeigt, wie diese beherrscht werden|||
||Der Hersteller hat alle Maßnahmen zur Risikobeherrschung auf Wirksamkeit überprüft||z.B. Referenzen auf entsprechende Tests zeigen lassen|
||Der Hersteller hat den Risikomanagementbericht und den IT Security Report erstellt.||Der IT Security Report kann in Europa durchaus Teil des Risikomanagementberichts sein, in den USA nicht.|
||Der Hersteller hat die notwendigen Pläne für die der Entwicklung nachgelagerten Phase (z.B. Incident Response Plan) erstellt||Details weiter unten|

[^20]: z.B. gemäß [OWSAP top 10](TODO), [SWE/SANS cusp list](TODO), [CWE/SANS top 25](TODO) 


D) Anforderungen an die der Entwicklung nachgelagerten Phasen
--------------

### 1. Produktion, Distribution, Installation

|ID|Anforderung|Stufe|Kommentare|
|:--:|:--|:--:|:--|
||Der Hersteller hat beschrieben, wie sichergestellt ist, dass nur genau die vorgesehenen Artefakte (Dateien) in genau der vorgesehenen Version im Produkt oder als Produkt ausgeliefert werden||hier geht es ums Konfigurationsmanagement. Auch bei Downloads oder AppStores relevant|
||Der Hersteller hat beschrieben, wie die für die Installation verantwortlichen Personen wissen, welches die aktuellste Version ist und wie Verwechslungen bei der Installation ausgeschlossen werden können||Dies ist nur bei stand-alone Software relevant. Hier wäre eine Verfahrens- oder Arbeitsanweisung zu erwarten|
||Der Hersteller hat beschrieben, wie bei der Installation sichergestellt wird, dass die Anforderungen, die in den Begleitmaterialien spezifiziert sind (s.o.) tatsächlich erfüllt sind||Hier wäre eine Verfahrens- oder Arbeitsanweisung zu erwarten|


### 2. Marktüberwachung

|ID|Anforderung|Stufe|Kommentare|
|:--:|:--|:--:|:--|
||Der Hersteller hat einen Post-Market Surveillance Plan erstellt.|||
||Der Hersteller hat beschrieben, welche Informationen aus der nachgelagerten Phase gesammelt werden [^D2-01]|||
||Der Hersteller hat beschrieben, wie und über welche Kanäle Informationen aus der nachgelagerten Phase gesammelt werden|||
||Der Hersteller hat beschrieben, wie Informationen aus der nachgelagerten Phase ausgewertet bzw. bewertet werden ||erklären lassen, wie der Hersteller eine Trendumkehr erkennt und definiert und welche Schwellwerte er dazu festgelegt hat [^D2-02] |
||Der Hersteller hat beschrieben, welche Maßnahmen daraus resultieren [^D2-03]||sich die Verbindung zu den Korrektur- und Vorbeugemaßnahmen in den Prozessbeschreibungen zeigen lassen|
||Der Hersteller hat für jede OTS-Komponente mindestens eine Quelle und die Frequenz deren Überwachung festgelegt, über die er über IT-Sicherheitsbezogene Probleme informiert wird [^D2-04] und beschrieben, welche Rolle mit welchen Werkzeugen diese Auswertung vornimmt||Zu diesen Quellen sollten die Webseiten des OTS-Herstellers sowie die [NIST Datenbank mit den Common Vulnerabilities](TODO)  zählen.|

[^D2-02]: Beispiele: Auditlogs, Vulnerability Datenbanken, Kundenbeschwerden, Anrufe bei Hotline, Beobachtungen (z.B. Verhalten der Anwender), Behörden-Datenbanken (FDA MAUDE, BfArM, SwissMedic etc.) auch zu ähnlichen Produkten oder Technologien, Normen, Gesetze etc.

[^D2-02]: Die MDR fordert dies im Anhang zur Post-Market Surveillance

[^D2-03]: Maßnahmen können beinhalten: Rückrufe, Behördenmeldungen, CAPA, Produktverbesserung, Prozessverbesserung, Training (Anwender, intern), Information der Kunden, Änderung der Begleitmaterialien, Einschränkung der Zweckbestimmung

[^D2-04]: Die Frequenz müsste mindestens jährlich, bei kritischen Komponenten häufiger als monatlich erfolgen. Die UL 2900-2-1 spricht von Update-Zyklen von zwei Wochen.

### 3. Incident Response Plan 

(inkl. Rückrufe, Patches, Kundenkommunikation)

|ID|Anforderung|Stufe|Kommentare|
|:--:|:--|:--:|:--|
||Der Hersteller hat einen Incident Reponse Plan erstellt [^D3-01] |||
||Der Incident Response Plan regelt, nach welchen Kriterien der Hersteller Informationen aus dem Markt bewertet und wann er den Notfallplan in Kraft setzt ...|||
||wer wie innerhalb welcher Fristen die Patches entwickelt und freigibt,|||
||wie der Hersteller erfährt, bei welchen Kunden das Produkt im Einsatz ist und über welche Kanäle er die Kunden erreicht,|||
||wie der Hersteller die Patches zum Kunden bringt und dort deren Installation sichergestellt,|||
||wer die Kunden in welcher Form und Frist informiert,|||
||in welchen Fällen eine Stillegung oder ein sonstiger Rückruf des Produkts wie angeordent wird|||

[^D3-01]: Der Incident Response Plan kann Teil anderer Pläne oder Dokumente sein z.B. des Post-Market Surveillance Plans  oder der Vorgaben zur Vigilanz.



E) Anhänge
-------------

### 1. Erläuterungen zu einzelnen Anforderungen

### 2. Priorisierung

Bei der Priorisierung von Anforderungen berücksichtigt der Leitfaden folgende Dimensionen:

- Risiko für den einzelnen Patienten (Kombination von Schweregrade und Wahrscheinlichkeit von Schäden)
- Tragweite (nur ein Patient, ganzes Krankenhaus etc.)
- Umsetzbarkeit (finanzieller und zeitlicher Aufwand, Voraussetzungen bezüglich Werkzeuge)

Die Priorisierung mündet in den folgenden Reifegradstufen

- **Stufe 0 ("Laien-Niveau")**: Selbst die meisten Laien würden diese Anforderung erfüllen. Wer nicht einmal die Anforderungen dieser Stufe erfüllt, sollte keine Medizinprodukte entwickeln. Diese Anforderungen darf und muss ein Auditor bereits im allerersten Audit als erfüllt erwarten.
- **Stufe 1 (Niveau "fortgeschrittener Anfänger")**: Der Hersteller hat sich des Themas IT-Sicherheit bereits angenommen. Bei unkritischeren Produkten und den ersten Audits kann dieses Niveau akzeptiert werden. In jedem Folgejahr wird jedoch eine Verbesserung erwartet, bis die Stufe 2 erreicht wird.
- **Stufe 2 ("State-of-the-art")**: Das ist das Niveau, das Hersteller auf Dauer in der Regel erreichen müssen. Es entspricht aber noch nicht dem Stand der Wissenschaft.
- **Stufe 3 ("Experten-Niveau")**: Dieses Niveau erreichen hauptberufliche IT-Security-Experten. Es geht über das hinaus, was ein Auditor in der Regel bei Medizinprodukten erwarten darf. Auf diesem Niveau werden beispielsweise Schwachstellen beherrscht, die allgemein nicht bekannt sind. Energieversorger, Geheimdienste und das Militär müssten auf diesem Niveau agieren.


### 3. Weiterführende Literatur

#### a) Gesetze

- MDR
- IVDR
- DSGVO
- 21 CFR Part 11

#### b) Normen und Best-Practice Guides

- Norm zur Kommunikation von Schwachstellen
- AAMI/TIR57
- IEC 62443-4-1
- IEC 62443-4-2
- IEC 82304-1
- FDA guidances 
   - “Content of Premarket Submissions for Management of Cybersecurity in Medical Devices”
   - “Wireless Medical Telemetry Risks and Recommendations”
- BSI-CS 132
- IEC/TR 80001-2-8, 
- UL 2900-1
- UL 2900-2-1

#### b) Fachliteratur, Lehrbücher

- Eckert: TODO
- Johner Institut: [Videotrainings zur IT-Sicherheit bei Medizinprodukten](www.auditgarant.de)

### 4. Erwägungsgründe

1. Hersteller entwickeln immer mehr vernetzte Medizinprodukte. Dadurch erhöhen sich die Risiken durch mangelnde IT Sicherheit (z.B. gegen Cyberangriffe). Dem Tragen viele Hersteller nur unzureichend Rechnung.
2. Die EU-Verordnungen (MDR, IVDR) fordern explizit die IT-Sicherheit. Die EU-Richtlinien fordern dies indirekt. Diese Vorgaben finden sich in den jeweiligen Anhängen I mit den grundlegenden (Sicherheits- und Leistungs-)Anforderungen. 
3. Im Gegensatz zu den meisten anderen grundlegenden Anforderungen sind keine Normen zum Thema IT-Sicherheit harmonisiert. Daher gibt es keinen kanonischen Katalog an Anforderungen, der anerkannt den geforderten Stand der Technik reflektiert.
4. Die FDA hat sowohl mehrere *Guidance Documents* veröffentlicht als auch Normen wie die UL 2900-2-1 anerkannt. Diese Vorgaben sind uneinheitlich bezüglich der Granularität, Vollständigkeit und konzeptionellen Integrität. Sie erfüllen nur bedingt die Ansprüche, die an die Qualität einer Norm üblicherweise gestellt werden.
5. Weil die meisten Medizinproduktehersteller die IT-Sicherheit nicht oder nur unzureichend adressieren, erfüllen sie die grundlegenden Anforderungen nur teilweise.
6. Für die meisten Hersteller wäre es weder zeitlich noch finanziell umsetzbar, mit einem Schlag ein IT-Sicherheits-Niveau zu erreichen, wie es z.B. der UL 2900 fordert. Daher sollten die Hersteller schrittweise ein State-of-the-Art Niveau bezüglich der IT-Sicherheit anstreben und erreichen. Damit verfolgt dieser Leitfaden das Ziel, lieber schnell erste Verbesserungen umzusetzen, als wegen Überforderung nichts zu tun.
7. IT-Sicherheit muss bei allen Produkt-Lebenszyklusprozessen berücksichtigt werden. Eine Beschränkung auf das Testen ist unzureichend.
8. Es ist zu erwarten, dass Normen zur IT-Sicherheit von Medizinprodukten entwickelt und harmonisiert werden, was aber noch Jahre in Anspruch nehmen kann. Daher bedarf es eines Leitfadens (nur) in dieser Zwischenphase. 
9. Dieser Leitfaden sollte sehr zeitnah (bis November 2018) zur Verfügung, um rasch den Herstellern als Orientierung zu dienen und es ihnen zu ermöglichen, sofort zu handeln. Die hohe Geschwindigkeit seiner Entwicklung macht Kompromisse bezüglich der Abstimmung mit möglichst vielen Parteien unumgänglich.
10. Da der Leitfaden von einer stufenweisen Annäherung auf ein State-of-the-Art-Nivau ausgeht und zudem in sehr kurzer Zeit entsteht, kann er keinen Anspruch auf Vollständigkeit erheben.
11. Der Leitfaden soll dennoch ein weitgehend allgemein akzeptiertes Niveau an Anforderungen repräsentieren. Die Auswahl und Priorität dessen Anforderungen müssen daher möglichst transparent nachvollziehbar sein.
12. Ein solcher Leitfaden muss die Spezifika von Medizinprodukten berücksichtigen, wozu die Prinzipen der Patientensicherheit (Safety) und eines risikobasierten Ansatzes zählen.
13. Die einfache Verständlichkeit und Umsetzbarkeit ist entscheidend für den erhofften positiven Einfluss eines Leitfadens auf die IT-Sicherheit.
13. Um die Verteilung und den Bekanntheitsgrad zu fördern, soll der Leitfaden kostenfrei verfügbar sein und bleiben. 
14. Der Leitfaden sollte auf Deutsch und Englisch verfügbar sein.
15. Der Fokus liegt auf der IT-Sicherheit der Medizinprodukte, nicht auf der IT-Sicherheit von Organisationen wie Krankenhäusern oder Medizinprodukteherstellern.


