Konzept zum gemeinsamen "Leitfaden IT Security" des TÜV SÜD und des Johner Instituts
=================

Erwägungsgründe
-----------

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

Autoren und Nutzungsrechte
----------------

Der Leitfaden wird von den folgenden Autoren verfasst:

- Dr. Andreas Purde (TÜV SÜD)
- Olaf Teichert (TÜV SÜD)
- Prof. Dr. Christian Johner (Johner Institut)

Die Autoren oder/und deren Institutionen sind im Leitfaden genannt inklusive Logo der Institutionen.

Der Leitfaden wird unter der [Creative Commons Lizenz](https://creativecommons.org/licenses/?lang=de) vom Typ [BY-NC-SA](https://creativecommons.org/licenses/by-nc-sa/4.0/) veröffentlicht. Diese erfordert die Namensnennung der Autoren ("TÜV SÜD und Johner Institut") und erlaubt es Dritten auf diesem Werk aufzubauen z.B. es zu verbessern, letzteres allerdings nur zu nicht-kommerziellen Zwecken.

Die Lizenz gestattet es, das Produkt zu Beratungszwecken kommerziell zu nutzen. Sie untersagt es aber, dieses Werk selbst in unveränderter oder veränderter Version kommerziell zu nutzen z.B. in Form eines Verkaufs als Broschüre.


Verteilung 
------------

Die Autoren planen, den Leitfaden aktiv bekannt zu machen z.B. über die folgenden Kanäle:

- Publikation als Webseite
- Verfügbarmachung als PDF auf den Webseiten
- Veröffentlichung als Git-Repository
- Aktives Empfehlen z.B. bei Beratungsprojekten oder Audits
- Versand per Newsletter
- Vorstellung auf Messen und Kongressen 
- Publikation in eigenen Medien sowie den Medien Dritter z.B. Fachzeitschriften
- Distribution über Multiplikatoren wie Normengremien

Priorisierung von Anforderungen
-------------

Bei der Priorisierung von Anforderungen berücksichtigt der Leitfaden folgende Dimensionen:

- Risiko für Patienten (Kombination von Schweregrade und Wahrscheinlichkeit von Schäden)
- Umsetzbarkeit (finanzieller und zeitlicher Aufwand, Voraussetzungen bezüglich Werkzeuge)

Die Priorisierung mündet in den folgenden Reifegradstufen

- **Stufe 0 ("Laien-Niveau")**: Selbst die meisten Laien würden diese Anforderung erfüllen. Wer nicht einmal die Anforderungen dieser Stufe erfüllt, sollte keine Medizinprodukte entwickeln. Diese Anforderungen darf und muss ein Auditor bereits im allerersten Audit als erfüllt erwarten.
- **Stufe 1 (Niveau "fortgeschrittener Anfänger")**: Der Hersteller hat sich des Themas IT-Sicherheit bereits angenommen. Bei unkritischeren Produkten und den ersten Audits kann dieses Niveau akzeptiert werden. In jedem Folgejahr wird jedoch eine Verbesserung erwartet, bis die Stufe 2 erreicht wird.
- **Stufe 2 ("State-of-the-art")**: Das ist das Niveau, das Hersteller auf Dauer in der Regel erreichen müssen. Es entspricht aber noch nicht dem Stand der Wissenschaft.
- **Stufe 3 ("Experten-Niveau")**: Dieses Niveau erreichen hauptberufliche IT-Security-Experten. Es geht über das hinaus, was ein Auditor in der Regel bei Medizinprodukten erwarten darf. Auf diesem Niveau werden beispielsweise Schwachstellen beherrscht, die allgemein nicht bekannt sind. Energieversorger, Geheimdienste und das Militär müssten auf diesem Niveau agieren.


Aufbau des Leitfadens
------------------

1. Metainformationen (Autoren, Dokumentenlenkung, Ziele, Verweise z.B. auf Erwägungsgründe)
2. Über diesen Leitfaden
   1. Anwendungsbereich
   2. Hinweise zur Verwendung 
2. Allgemeine Anforderungen (Prozesse, Dokumentation) 
3. Anforderungen an die Produktentwicklung
   1. Zweckbestimmung und Stakeholder-Anforderungen
   2. System- und Software-Anforderungen
   3. System- und Software-Architektur
   4. Implementierung und Erstellung der Software
   5. Bewertung von Software-Einheiten
   6. System- und Software-Tests
   7. Produktfreigabe
4. Anforderungen an die der Entwicklung nachgelagerten Phasen
   1. Produktion, Distribution, Installation
   2. Marktüberwachung
   3. Rückrufe, Patches
5. Anhänge
   1. Erläuterungen zu einzelnen Anforderungen
   2. Weiterführende Literatur

Die Kapitel 4 f. enthalten die Anforderungen thematisch gruppiert in Tabellen, wie der folgenden:

|ID|Anforderung|Stufe|Begründung, Referenzen, Kommentare|
|:--:|:--|:--:|:--|
|12|Das System meldet den Anwender nach x Minuten Inaktivität automatisch wieder ab|2|UL 2900-2-1 Absatz XY, ISO 15408 Teil X Kapitel Y|
|...||||
