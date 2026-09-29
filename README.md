# Gleiswacht-Updater

Update-Kanal der Desktop-App **Gleiswacht**. Hier liegen nur die signierten
Windows-Installer, ihre Blockmaps und `latest.yml`. Die installierte App fragt
diese Releases ohne Anmeldung ab. Der Quellcode liegt nicht in diesem Repository.

## Erstinstallation oder Umstieg von Version 1.1

Im neuesten Release `Gleiswacht Setup <Version>.exe` herunterladen und
ausführen. Vorhandene Daten (Datenbank, Uploads, Einstellungen) bleiben
erhalten; vor dem ersten Start der neuen Version wird der bisherige Stand
automatisch gesichert.

## Updates

Danach meldet Gleiswacht neue Versionen beim Start. Installiert wird per Klick
unter **Einstellungen → Software-Update**; vorher sichert die App den
Datenstand.

## Für die Freigabe

Neue Versionen lädt die Release-Pipeline als **Entwurf** hoch. Kunden sehen
eine Version erst, wenn der Entwurf veröffentlicht wird. Der Text des Releases
erscheint in der App als „Änderungen in dieser Version“.
