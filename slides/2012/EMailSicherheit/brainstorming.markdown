# Warum unsicher
- SMTP von Hause aus unverschlüsselt
- Jede Mail im Netzwerk problemlos abfangbar
- Unverschlüsselte Speicherung auf dem Mailserver
- Zugriff des Sysadmins auf alle Mails
- Kommunikation zwischen den Servern unverschlüsselt
- Keine Prüfsummen, jederzeit veränderbar

# Wie man es sicherer macht
- Keine sensiblen Daten im Klartext
- GPG Verschlüsselung
- GPG Signatur für Änderungssicherheit
- S/MIME Signatur / Verschlüsselung

# Problem der Webmailer
- Darstellung im Web erfordert Klartext auf Server
- Kein Support für GPG / S/MIME

# Sonstige Probleme
- Vergessen auszuloggen
- Gleiches Passwort für alle Accounts
