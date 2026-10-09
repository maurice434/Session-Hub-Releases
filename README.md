# Claude Session Hub – Releases

Installationspakete für den **Claude Session Hub**: eine lokale Web-App, die mehrere Claude-Code-Sessions nach Projekten geordnet im Browser betreibt und ihren Status anzeigt (arbeitet / wartet auf dich / fertig).

Dieses Repository enthält nur die fertigen Setups und die Release-Notizen.

## Installieren

1. Unter **[Releases](https://github.com/maurice434/Session-Hub-Releases/releases/latest)** die Datei `ClaudeSessionHub-Setup-<version>.exe` herunterladen und ausführen – ohne Admin-Rechte.
2. Erscheint „Der Computer wurde durch Windows geschützt“: „Weitere Informationen“ → „Trotzdem ausführen“ (das Setup ist nicht signiert).
3. Fehlen Claude Code oder PowerShell 7, bietet das Setup an, sie mitzuinstallieren.

**Voraussetzungen:** Windows 10 (1809 oder neuer) oder Windows 11, x64. Für Claude Code ein eigenes Abo (Pro, Max, Team, Enterprise) oder ein Console-Zugang – die Anmeldung erfolgt in der ersten Session.

Nach der Installation sitzt das Symbol ✳ im Infobereich der Taskleiste; Doppelklick öffnet den Hub im Browser.

## Updates

Ab Version 0.3.0 meldet der Hub neue Versionen selbst: In der Titelleiste erscheint „⬆ Update x.y.z“. „Jetzt aktualisieren“ lädt das Setup, installiert es und startet den Hub neu. Laufende Sessions werden dabei beendet und lassen sich mit „▶ Fortsetzen“ wieder aufnehmen.

Ältere Versionen: das neue Setup einfach über die bestehende Installation installieren – Daten und Autostart bleiben erhalten.

## Deinstallieren

Einstellungen → Apps → Installierte Apps → Claude Session Hub. Die Daten unter `%APPDATA%\claude-session-hub\` bleiben erhalten.
