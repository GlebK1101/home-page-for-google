# home-page-for-google
Eine personalisierte Startseite zur Organisation von Lesezeichen. Organisieren Sie Links und Notizen in Tabellen innerhalb von Tabs. Features: Dunkles/Helles Design, automatisches Abrufen von YouTube-Titeln, Datenexport/-import (JSON), Bearbeitung von Einträgen. Funktioniert lokal im Browser via LocalStorage — einfach die Datei in Chrome öffnen.

## Ein einfaches und bequemes Tool zur Organisation Ihrer Links und Notizen. Funktioniert lokal im Browser, ohne Server und Registrierung.

### Das Problem: „Tab-Wahnsinn“
Wir alle kennen das: Man öffnet den Browser und es sind 50 Tabs offen.
- „Diesen Artikel lese ich später.“
- „Dieses Video muss ich heute Abend ansehen.“
- „Und diesen Link brauche ich nächste Woche für die Arbeit.“

Das Ergebnis: Der Browser wird langsam, der Arbeitsspeicher ist voll und den richtigen Link in diesem Chaos zu finden, ist unmöglich. Man hat Angst, einen Tab zu schließen, um ihn nicht für immer zu verlieren. *(Ja, ich kenne normale Lesezeichen, aber um die geht es hier nicht)*.

### Die Lösung
Dieses Projekt ist **eine einzige HTML-Datei**, die Ihre Standard-Startseite ersetzt.
Anstatt einen Tab offen zu halten, kopieren Sie den Link einfach hierher, fügen eine Notiz hinzu und **schließen den Tab mit ruhigem Gewissen**. Alle Ihre Links sind ordentlich in Kategorien (Reitern) sortiert und der Browser läuft schnell.

### Funktionen
1. **Organisation in Tabs**: Erstellen Sie Kategorien (z.B.: „Arbeit“, „YouTube“, „Rezepte“, „Lesen“).
2. **Intelligentes Hinzufügen**: Fügen Sie einen YouTube-Link ein und der Videotitel wird automatisch abgerufen.
3. **Datenschutz**: Alle Daten werden nur in Ihrem Browser gespeichert (LocalStorage). Keine Datenübertragung an externe Server.
4. **Anpassung**: Dunkles und helles Design, Einstellungen für die Schriftgröße.
5. **Datensicherheit**: Funktion zum Exportieren und Importieren aller Daten in eine JSON-Datei (praktisch für den Transfer auf einen anderen PC oder als Backup).
6. **Keine Installation**: Einfach die Datei herunterladen und im Browser öffnen.

### Wie man es startet
1. Laden Sie die Datei `index_de.html` aus diesem Repository herunter.
2. Öffnen Sie sie in Google Chrome (oder einem anderen Browser).
3. *(Empfohlen)* Gehen Sie in die Browsereinstellungen *(Drei Punkte -> Darstellung -> Schaltfläche „Startseite“ anzeigen)* und legen Sie diese Datei als Ihre **Startseite** fest.

### Wichtig: Was Sie wissen müssen
1. **Löschen Sie „Website-Daten“ nicht gedankenlos**: Wenn Sie den Browserverlauf löschen und das Häkchen bei *"Cookies und andere Websitedaten"* setzen, werden Ihre Einträge gelöscht.
2. **Inkognito-Modus**: Wenn Sie die Datei im Inkognito-Modus öffnen, verschwinden die dort gemachten Einträge sofort nach dem Schließen des Fensters.
3. **Verschiedene Browser = Verschiedene Daten**: Wenn Sie die Datei in Chrome und dann in Firefox öffnen, sehen Sie in Firefox eine leere Seite. Die Daten sind an den jeweiligen Browser gebunden.

### Wie Sie sich absichern
Das Projekt verfügt über eine integrierte Backup-Funktion:
1. Klicken Sie auf das große Zahnrad (Einstellungen).
2. Klicken Sie auf „Alles als JSON exportieren“.
3. Speichern Sie die Datei auf Ihrem Computer.

*Eine ähnliche Funktion gibt es auch für jeden einzelnen Tab.*

Genießen Sie die Ordnung!
