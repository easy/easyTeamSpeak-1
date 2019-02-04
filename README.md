# easyTeamSpeak
### ONLY FOR DEBIAN 8, DEBIAN 9 (64 BIT)

easyTeamSpeak ist ein sehr mächtiges Script für die Installation und Verwaltung von TS³-Servern, welches stetig weiterentwickelt und verbessert wird.

## Funktionen
- [x] Installieren / Deinstallieren
- [x] Updaten / Downgraden
- [x] Starten / Stoppen / Neu starten
- [x] Whitelist (Ansehen, IP hinzufügen, IP entfernen)
- [x] Blacklist (Ansehen, IP hinzufügen, IP entfernen)
- [x] Backup (Backups ansehen, Erstellen, Einspielen, Löschen) 

## Installation
Gehe mit `cd` in das Root-Verzeichnis und lade dort mit `wget https://github.com/easy/easyTeamSpeak/releases/download/v1.0/easyTeamSpeak.sh` das Script herunter. Gebe dem Script 777-Rechte mit `chmod 777 easyTeamSpeak.sh`. Nun kann das Script genutzt werden.

## Benutzung
Die Benutzung des Scripts ist sehr einfach. Du musst jediglich `./easyTeamSpeak.sh` im Root-Verzeichnis ausführen. Der Rest ist selbsterklärend.

## Sceenshots
- Menu: ![menu pic](data:image/png;base64,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)
- Installation: https://prnt.sc/mg6ta5 https://prnt.sc/mg6tfz
- White-/ Blacklist: https://prnt.sc/mg6tno
- Backup: https://prnt.sc/mg6tt4
