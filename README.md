# Workshop git Tag 2


## Aufwärmen

Hausaufgaben: Welche GUI für Git gefällt Euch und warum?

Git for Humans (20 Minuten) https://www.youtube.com/watch?v=eWxxfttcMts

Git-Quiz: https://www.w3schools.com/quiztest/quiztest.asp?qtest=GIT

### Die 5 Vorteile von Git

1.

2.

3.

4.

5.

## Warum es gut ist, sich auf der Shell zurechtzufinden

Die Shell ermöglicht es, Aufgaben effizient und automatisiert zu erledigen, was die Produktivität erheblich steigern kann. Durch das Erlernen von Shell-Kommandos und Skripten können komplexe Prozesse vereinfacht und wiederholbare Aufgaben automatisiert werden. Zudem ist die Shell ein unverzichtbares Werkzeug für Entwickler und Systemadministratoren, da sie direkten Zugriff auf das Betriebssystem und die damit verbundenen Ressourcen bietet. Diese Fähigkeiten können die Problemlösungsfähigkeiten und das Verständnis für Computersysteme erheblich verbessern.

### Oh My Posh auf Windows

Für Windows gibt es eine ähnliche Möglichkeit wie Oh My Zsh, die speziell für die Windows-Umgebung und die Eingabeaufforderung bzw. die PowerShell entwickelt wurde. Oh My Posh ist ein benutzerdefiniertes Prompt-Thema für PowerShell, das ähnlich wie Oh My Zsh auf macOS und Linux funktioniert. Es bietet eine Vielzahl von Themes und Anpassungsoptionen, die die Arbeit im Terminal angenehmer und übersichtlicher machen.

#### Installation:

1.  Installiere PowerShell (falls noch nicht vorhanden).
2.  Installiere Oh My Posh via PowerShellGet:

```
Install-Module oh-my-posh -Scope CurrentUser
```

Konfiguriere das Theme:

```
Set-PoshPrompt -Theme Paradox
```

#### Vorteile:

-   Einfach zu installieren und zu konfigurieren.
-   Große Auswahl an Themes.
-   Kompatibel mit der Windows PowerShell und PowerShell Core.

Weitere Informationen und eine Übersicht der verfügbaren Themes findest du [hier](https://ohmyposh.dev/docs/themes).



## Git Übungen auf der Shell

https://lerneprogrammieren.de/git/



## SSH-Key erstellen und in Deinem Github-Account hinterlegen

### Vorteile der Nutzung von GitHub über SSH

1.  **Sicherheit:** SSH bietet eine sichere Methode zur Authentifizierung und Verbindung mit GitHub, indem es verschlüsselte Verbindungen verwendet.
2.  **Komfort:** Einmal eingerichtet, ermöglicht SSH eine kennwortlose Authentifizierung, was die Nutzung von Git-Operationen schneller und bequemer macht.
3.  **Vermeidung von Token:** Mit SSH müssen keine persönlichen Zugriffstokens oder Passwörter bei jeder Git-Operation eingegeben werden.
4.  **Automatisierung:** SSH-Schlüssel sind ideal für automatisierte Skripte und CI/CD-Pipelines, da sie ohne Benutzereingriffe funktionieren.

### Einrichtung von GitHub über SSH

https://jdblischak.github.io/2014-09-18-chicago/novice/git/05-sshkeys.html

Aufgaben

1.   Hinterlege bei Github Deinen SSH-Key

2.   Lass Dir anzeigen, welche remote origins Dein Repo hat: 

     `git remote -v`

3.   Ändere den remote origin auf die ssh-URL Deines Repos bei Gitub: git remote set-url origin [ssh-URl deines Repos]





## Git-Glossar

**Branch** - ein paralleler Entwicklungszweig innerhalb eines Repositories, der es ermöglicht, unabhängig vom Hauptentwicklungsstrang zu arbeiten.

**Checkout** - Zeitreisen zu einer bestimmten Version eines Branches.

**Clone** - das Kopieren eines Remote-Repositories auf den lokalen Rechner, inklusive aller Dateien, Historie und Branches.

**Commit** - ein Schnappschuss der aktuellen Änderungen, der im Repository gespeichert wird und eine eindeutige Kennung erhält.

**Fetch** - das Herunterladen von neuen Änderungen aus einem Remote-Repository, ohne diese in den aktuellen Branch zu integrieren.

**Hash** - eine eindeutige ID für Deinen Commit

**HEAD** - der Zeiger auf den aktuell aktiven Branch bzw. Commit.

**Index** - der Staging-Bereich, in dem Änderungen gesammelt werden, bevor sie committet werden.

**Merge** - das Zusammenführen von Änderungen aus verschiedenen Branches.

**Pull** - das Herunterladen und Zusammenführen von Änderungen aus einem Remote-Repository in den aktuellen Branch.

**Push** - das Hochladen von Commits aus dem lokalen Repository in ein Remote-Repository.

**Remote** - ein anderer Computer mit einem Repository.

**Repository (Repo)** - ein Ordner, der alle Dateien und die gesamte Historie der Änderungen eines Projekts enthält.

**Reset** - das Zurücksetzen des aktuellen Branches auf einen bestimmten Commit, wobei Änderungen optional verworfen oder behalten werden können.

**Staging** - der Prozess des Hinzufügens von Änderungen zum Index, um sie für den nächsten Commit vorzubereiten.

**Tag** - ein markierter Punkt in der Commit-Historie, oft verwendet, um Versionsnummern zu kennzeichnen.

**Working Directory** - das aktuelle Verzeichnis auf dem lokalen Rechner, das die Dateien des Repositories enthält und Änderungen widerspiegelt.