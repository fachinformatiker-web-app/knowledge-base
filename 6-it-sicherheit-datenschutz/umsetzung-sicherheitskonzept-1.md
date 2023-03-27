---
sidebar_position: 4
---

# Sicherheitskonzepte umsetzen

<!--
Umsetzung des arbeitsplatzbezogenen SicherMH upEE unterstützen können
Schaffung eines Sicherheitsbewusstseins bei den
Mitarbeitern

-   IT-Sicherheitsmanagement
-   Durch technische, infrastrukturelle, organisatorische
    und personelle Schutzmaßnahmen
-   Security by Design
-   Security by Default
-   Datensicherung/Backup-Verfahren
-   Sicherung der Verfügbarkeit, z. B. RAID-Systeme, SAN
-   Zugangs- und Zugriffskontrolle
-   Verschlüsselungstechniken, symmetrische und asymmetrische Verschlüsselung, CAs, Zertifikate, Digitale
    Signaturen, Techniken wie https, TSL
-   Authentifizierung, Passwort-Policy
-   Firewall, SSH vs. Telnet -->

## Umsetzung des arbeitsplatzbezogenen Sicherheitsmanagements

-   IT-Sicherheitsmanagement: Planung, Umsetzung und Überwachung von Schutzmaßnahmen zur Gewährleistung der IT-Sicherheit
-   Technische, infrastrukturelle, organisatorische und personelle Schutzmaßnahmen: Einsatz von Technologien, Aufbau einer sicheren Infrastruktur, Schaffung von Sicherheitsrichtlinien und Schulungen der Mitarbeiter
-   Security by Design: Einbindung von Sicherheitsaspekten in die Entwicklung von IT-Systemen und -Produkten
-   Security by Default: Auslieferung von Systemen mit voreingestellten Sicherheitseinstellungen
-   Datensicherung/Backup-Verfahren: regelmäßige Sicherung von Daten zur Vermeidung von Datenverlust
-   Sicherung der Verfügbarkeit: Einsatz von Technologien wie RAID-Systeme oder SAN zur Gewährleistung der Verfügbarkeit von Daten und Systemen
-   Zugangs- und Zugriffskontrolle: Verwaltung von Zugriffsrechten und -beschränkungen für Mitarbeiter und Systeme
-   Authentifizierung: Verifizierung der Identität von Benutzern und Systemen, Passwort-Policy für sichere Passwörter
-   Firewall: Schutzmaßnahme zur Abschirmung von Netzwerken, SSH vs. Telnet: Vergleich von sicheren und unsicheren Remote-Protokollen

## Verschlüsselungstechniken

Verschlüsselung ist ein Verfahren zur sicheren Übertragung von Informationen, bei dem die Daten so verändert werden, dass sie für Unbefugte unlesbar sind. Hier sind einige gängige Verschlüsselungstechniken:

-   Symmetrische Verschlüsselung: Bei der symmetrischen Verschlüsselung wird ein gemeinsamer Schlüssel verwendet, um sowohl zu verschlüsseln als auch zu entschlüsseln. Beide Parteien müssen den gleichen Schlüssel kennen, um auf die verschlüsselten Daten zugreifen zu können. Ein Beispiel für eine symmetrische Verschlüsselung ist der Advanced Encryption Standard (AES).
-   Asymmetrische Verschlüsselung: Bei der asymmetrischen Verschlüsselung werden zwei verschiedene Schlüssel verwendet - ein öffentlicher Schlüssel zum Verschlüsseln und ein privater Schlüssel zum Entschlüsseln. Der öffentliche Schlüssel kann frei zugänglich gemacht werden, während der private Schlüssel geheim gehalten werden muss. Ein Beispiel für eine asymmetrische Verschlüsselung ist der RSA-Algorithmus.
-   Zertifikate: Ein Zertifikat ist eine digitale Bescheinigung, die die Identität einer Person, Organisation oder eines Computersystems bestätigt. Ein Zertifikat wird von einer Zertifizierungsstelle (CA) ausgestellt und enthält Informationen über den öffentlichen Schlüssel des Zertifikatinhabers. Zertifikate werden häufig in Verbindung mit asymmetrischer Verschlüsselung verwendet, um die Authentizität von Websites oder E-Mail-Adressen zu überprüfen.
-   Digitale Signaturen: Eine digitale Signatur ist eine elektronische Methode, um die Integrität von Dokumenten oder Nachrichten zu gewährleisten. Eine digitale Signatur wird durch die Verschlüsselung einer Hash-Funktion mit dem privaten Schlüssel des Signierenden erzeugt. Empfänger können die Signatur dann mit dem öffentlichen Schlüssel des Signierenden entschlüsseln und den Hash-Wert der empfangenen Nachricht vergleichen, um die Integrität zu überprüfen.
-   HTTPS und TLS: HTTPS (Hypertext Transfer Protocol Secure) und TLS (Transport Layer Security) sind Verschlüsselungsprotokolle, die für sichere Kommunikation im Internet verwendet werden. HTTPS stellt eine verschlüsselte Verbindung zwischen Webbrowsern und Webservern her, während TLS eine sichere Verbindung zwischen Client und Server auf der Transportebene ermöglicht. HTTPS und TLS nutzen asymmetrische Verschlüsselung, um die Vertraulichkeit und Integrität von Daten zu gewährleisten.

## Datensicherung/Backup-Verfahren

-   Regelmäßige Sicherung wichtiger Daten zur Wiederherstellung im Falle von Datenverlust
-   Backup-Konzepte: Planung und Durchführung von Backups
-   Vollständige Backups: Sicherung aller Daten auf einem Datenträger
-   Inkrementelle Backups: Sicherung nur der veränderten Daten seit dem letzten Backup
-   Differentielle Backups: Sicherung aller veränderten Daten seit dem letzten vollständigen Backup
-   Offsite-Backup: Sicherung von Daten an einem anderen Ort zur Erhöhung der Ausfallsicherheit
-   Backup-Methoden: verschiedene Methoden zur Durchführung von Backups, z.B. Bandlaufwerke, Festplatten, Cloud-Backup
-   Recovery-Verfahren: Wiederherstellung von Daten aus Backups, z.B. durch Wiederherstellung auf einem neuen System oder Rekonstruktion von Daten

## Schaffung eines Sicherheitsbewusstseins bei den Mitarbeitern

-   Schulung und Sensibilisierung: Mitarbeiter über Risiken und Maßnahmen informieren, um Fehlverhalten zu vermeiden
-   Sicherheitsrichtlinien: klare Vorgaben und Regeln zur IT-Sicherheit, die von den Mitarbeitern einzuhalten sind
-   Sicherheitsbeauftragter: eine Person im Unternehmen, die für IT-Sicherheit zuständig ist und Mitarbeiter unterstützt

## Beispiel-Fragen

-   Was versteht man unter IT-Sicherheitsmanagement und welche Maßnahmen sind zur Gewährleistung der IT-Sicherheit erforderlich?
-   Was ist Security by Design und wie kann es bei der Entwicklung von IT-Systemen und -Produkten umgesetzt werden?
-   Welche Verschlüsselungstechniken gibt es und wofür werden sie eingesetzt?
-   Wie kann die Zugangs- und Zugriffskontrolle in einem Unternehmen umgesetzt werden?
-   Was ist eine Firewall und welche Funktion hat sie im Rahmen des IT-Sicherheitsmanagements?
-   Was ist der Unterschied zwischen symmetrischer und asymmetrischer Verschlüsselung?
-   Wie wird die Integrität von Dokumenten oder Nachrichten durch digitale Signaturen gewährleistet?
-   Was sind Zertifikate und wozu werden sie verwendet?
-   Welche Rolle spielen HTTPS und TLS bei der sicheren Kommunikation im Internet?
-   Was sind die Unterschiede zwischen vollständigen, inkrementellen und differentiellen Backups?
-   Welche Backup-Methoden gibt es und welche Vor- und Nachteile haben sie?
-   Was versteht man unter Offsite-Backup und warum ist es wichtig?
-   Wie wird ein Recovery-Verfahren durchgeführt und welche Schritte sind dabei zu beachten?
