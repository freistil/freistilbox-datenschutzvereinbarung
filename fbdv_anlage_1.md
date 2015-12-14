---
Title: Anlage 1
CSS: freistilbox.css
---

# Anlage 1

__Technische und organisatorische Maßnahmen des Auftragnehmers gemäß § 9 BDSG__

## 1. Zutrittskontrolle

_Maßnahmen, die geeignet sind, Unbefugten den Zutritt zu Datenverarbeitungsanlagen, mit denen personenbezogene Daten verarbeitet oder genutzt werden, zu verwehren._

Maßnahmen zur Zutrittskontrolle in den Rechenzentren:

- Videoüberwachung sämtlicher Zufahrten, Eingänge und Serverräume
- Personalisierte Zutrittskontrollsysteme mit Zutrittsberechtigung nur für autorisierte RZ-Mitarbeiter
- Dienstanweisungen zur Handhabung von Zutrittskontrollen
- Richtlinien zur Begleitung und Kennzeichnung von Gästen im Gebäude
- Zugang zu Serverräumen nur in Ausnahmefällen durch autorisierten Vertragspartner nach Terminvereinbarung. Vertretungsberechtigte benötigen eine schriftliche Bestätigung des Vertragspartners.
- Zugang zu den Serverräumen nur in Begleitung eines RZ-Mitarbeiters möglich
Protokollierung der Besucher


## 2. Zugangskontrolle

_Maßnahmen, die geeignet sind zu verhindern, dass Datenverarbeitungssysteme von Unbefugten genutzt werden können._

Maßnahmen zur Zugangskontrolle bei Wartung und Pflege der Hosting-Plattform:

- Wartungsarbeiten erfolgen ausschließlich über verschlüsselte SSH-Verbindungen.
- Jede/r Systemadministrator/in verfügt über individuelle SSH-Schlüsselpaare, die jeweils zusätzlich mit einer Passphrase verknüpft sind.
- Die öffentlichen Schlüssel werden durch ein zentrales System Configuration Management automatisch auf allen Servern hinterlegt, aktualisiert und nach Ausscheiden aus dem Unternehmen wieder entfernt.
- Private Schlüssel werden individuell pro Arbeitsstation erzeugt, sodass eine gezielte Sperrung möglich ist.
- Ausschließlich Systemadministrator/inn/en erhalten Wartungszugriff auf die IT-Infrastruktur.

Maßnahmen zur Zugangskontrolle auf IT-Service-Ebene:

- Vergabe individueller Benutzerkonten für jede Website durch System Configuration Management
- Nach Möglichkeit Einsatz von SSL-Verschlüsselung
- Interne IT-Dienste geschützt durch Firewalls
- Sperrung externer IP-Adressen nach mehreren fehlgeschlagenen Anmeldeversuchen

Maßnahmen zur Zugangskontrolle in den Rechenzentren:

- Serversysteme nur mit Konsolenpasswort oder über passwortgeschützte, verschlüsselte Verbindung administrierbar
- Clientsysteme nur nach passwortgeschützter Netzwerk-Authentifizierung nutzbar
- Eindeutige Zuordnung von Benutzerkonten zu Benutzern, keine unpersönlichen Sammelkonten
- Richtlinie zum sicheren, ordnungsgemäßen Umgang mit Passworten
- Richtlinie zur Erneuerung der Passwörter in bestimmten Zeitintervallen


## 3. Zugriffskontrolle

_Maßnahmen, die gewährleisten, dass die zur Benutzung eines Datenverarbeitungssystems Berechtigten ausschließlich auf die ihrer Zugriffsberechtigung unterliegenden Daten zugreifen können, und dass personenbezogene Daten bei der Verarbeitung, Nutzung und nach der Speicherung nicht unbefugt gelesen, kopiert, verändert oder entfernt werden können._

Maßnahmen zur Zugriffskontrolle bei Wartung und Pflege der Hosting-Plattform:

- Minimierung administrativer Zugriffe durch weitgehende System-Automation
- Vergabe individueller Benutzerkonten
- Administrative Zugriffe ausschließlich über verschlüsselte SSH-Verbindungen mit individuellem Schlüsselpaar und Passphrase

Maßnahmen zur Zugriffskontrolle in den Rechenzentren:

- Datenverschlüsselung
- Revisionssicheres, verbindliches Berechtigungsvergabeverfahren
- Revisionssicheres, verbindliches Verfahren zur Wiederherstellung von Daten aus Backup (Restore durch IT-Abteilung auf Anweisung von Projektleitung / Abteilungsleitung / Geschäftsleitung / Geschäftsführung)
Trennung von Berechtigungsbewilligung (organisatorisch) durch Abteilungsleitung / Geschäftsleitung / Geschäftsführung und Berechtigungsvergabe (technisch) durch IT-Abteilung
- Netzlaufwerke mit Zugriff nur für berechtigte Benutzer(gruppen)


## 4. Weitergabekontrolle

_Maßnahmen, die gewährleisten, dass personenbezogene Daten bei der elektronischen Übertragung oder während ihres Transports oder ihrer Speicherung auf Datenträger nicht unbefugt gelesen, kopiert, verändert oder entfernt werden können, und dass überprüft und festgestellt werden kann, an welche Stellen eine Übermittlung personenbezogener Daten durch Einrichtungen zur Datenübertragung vorgesehen ist._

Die zur Erbringung der Dienstleistung durch den Auftragnehmer genutzten Server
befinden sich auschließlich in Rechenzentren auf dem Gebiet der Bundesrepublik
Deutschland.

Maßnahmen zur Weitergabekontrolle bei Wartung und Pflege der Hosting-Plattform:

- Verschlüsselte Übertragung der Daten, z.B. via SSH/SCP
- Richtlinie zur Übertragung von Daten auf Systeme außerhalb der Hosting-Plattform

Maßnahmen zur Weitergabekontrolle auf IT-Service-Ebene:

- Nach Möglichkeit verschlüsselte Übertragung der Daten, z.B. via SSL/TLS

Maßnahmen zur Weitergabekontrolle in den Rechenzentren:

- Datenverschlüsselung
- Leitungsverschlüsselung


## 5. Eingabekontrolle

_Maßnahmen, die gewährleisten, dass nachträglich überprüft und festgestellt werden kann, ob und von wem personenbezogene Daten in Datenverarbeitungssysteme eingegeben, verändert oder entfernt worden sind._

Maßnahmen zur Eingabekontrolle bei Wartung und Pflege der Hosting-Plattform:

- Protokollierung manueller Logins

Maßnahmen zur Eingabekontrolle in den Rechenzentren:

- Registrierung der Benutzer und Uhrzeit der jeweiligen Änderung im Teilnehmerverwaltungssystem


## 6. Auftragskontrolle

_Maßnahmen, die gewährleisten, dass personenbezogene Daten, die im Auftrag verarbeitet werden, nur entsprechend den Weisungen des Auftraggebers verarbeitet werden können._

Maßnahmen zur Auftragskontrolle bei Wartung und Pflege der Hosting-Plattform:

- Dokumentation der Durchführung von Aufträgen via Ticketsystem
- Auswahl des Auftragnehmers unter Sorgfaltsgesichtspunkten (insbesondere hinsichtlich Datensicherheit)
- Vorherige Prüfung und Dokumentation der beim Auftragnehmer getroffenen Sicherheitsmaßnahmen
- Schriftliche Weisungen an den Auftragnehmer (z.B. durch Auftragsdatenverarbeitungsvertrag) i.S.d. § 11 Abs. 2 BDSG
- Verpflichtung der Mitarbeiter des Auftragnehmers auf das Datengeheimnis (§ 5 BDSG)
- Sicherstellung der Vernichtung von Daten nach Beendigung des Auftrags
- Vereinbarung wirksamer Kontrollrechte gegenüber dem Auftragnehmer
- Laufende Überprüfung des Auftragnehmers und seiner Tätigkeiten

Maßnahmen zur Auftragskontrolle in den Rechenzentren:

- Die AGB des RZ-Dienstleisters enthalten detaillierte Angaben über Art und Umfang der beauftragten Verarbeitung und Nutzung personenbezogener Daten des Auftraggebers.
- Die AGB des RZ-Dienstleisters enthalten detaillierte Angaben über die Zweckbindung der personenbezogenen Daten des Auftraggebers.
- Der RZ-Dienstleister hat einen betrieblichen Datenschutzbeauftragten bestellt und sorgt durch die Datenschutzorganisation für dessen angemessene und effektive Einbindung in die relevanten betriebliche Prozesse.


## 7. Verfügbarkeitskontrolle

_Maßnahmen, die gewährleisten, dass personenbezogene Daten gegen zufällige Zerstörung oder Verlust geschützt sind._

Maßnahmen zur Verfügbarkeitskontrolle in den Rechenzentren:

- Redundante Anbindung über verschiedene Leitungsanbieter
- Unterbrechungsfreie Stromversorgung (USV) und Notstrom-Aggregate
- Feuer- und Rauchmeldeanlagen sowie Löschanlagen
- Alarmmeldung bei unberechtigten Zutritten

Maßnahmen zur Verfügbarkeitskontrolle innerhalb der Hosting-Plattform:

- Einsatz von Festplattenspiegelung bei allen relevanten Servern
- Backup- & Recoverykonzept mit täglicher Sicherung aller relevanten Daten; Regelmäßige Prüfung der Datenwiederherstellung
- Sachkundiger Einsatz von Schutzprogrammen (Virenscanner, Firewalls, Verschlüsselungsprogramme, Spamfilter)
- Redundante Speicherung der Daten auf räumlich getrennten Systemen


## 8. Trennungsgebot

_Maßnahmen, die gewährleisten, dass zu unterschiedlichen Zwecken erhobene Daten getrennt verarbeitet werden können._

Maßnahmen zum Trennungsgebot innerhalb der Hosting-Plattform:

- Physikalisch getrennte Speicherung auf gesonderten Systemen
- Logische Mandantentrennung (softwareseitig)
- Trennung von Produktiv- und Testsystemen
