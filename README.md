# Griepswold
Git-Übungen

Dieses Verzeichnis enthält Kode, der bei Übungen zu git und GitHub mit Studierenden and der [Universität Greifswald](https://de.wikipedia.org/wiki/Universität_Greifswald) entstanden ist, darunter vor allem XML-Annotationen mit Hilfe des Programms [ELAN](https://de.wikipedia.org/wiki/ELAN_software) und Literaturdatenbanken im Format [BiBTeX]([https://de.wikipedia.org/wiki/](https://de.wikipedia.org/wiki/BibTeX).

Diese Readme-Datei dokumentiert das Projekt und enthält praktische Hinweise.

# ﻿GIT mit der Kommandozeile nutzen

Es gibt viele Anleitungen im Internet, z.B. bei [rogerdudler.github.io](https://rogerdudler.github.io/git-guide/index.html).

Start
* `git init` = initiiert das Programm Git im aktuellen Verzeichnis
* `git clone {URL als Pfad}` = klont ein Verzeichnis aus der Cloud auf den eigenen Computer, z.B. von https://github.com/meehkal/Griepswold/
Status überprüfen
* `git status`
Lokalen Klon auf den Stand der zentralen Cloud bringen
* `git pull`
Lokale Änderungen auf der zentralen Cloud speichern
* `git commit -m "{Log-Nachricht}" {Name (der geänderten Datei)}` = wenn Datei bereits in der Cloud existiert
* `git push`
Neue Datei (oder neuer Ordner) lokal anlegen
* `git add {Name (der neuen Datei)}` = wenn Datei noch nicht in der Cloud existiert
* `git commit -m "{Log-Nachricht}" {Name (der neuen Datei)}`
* `git push`
 
# Nützliche UNIX-Befehle (Windows)

## Aufruf Eingabeaufforderung

`[Windows-Taste]` + `[R]` drücken  
`cmd` eingeben

## Grundlegende UNIX-Kommandos

`dir` = Inhalte im aktuellen Verzeichnis anzeigen  
`dir /w` oder `dir | more` = formatierte Anzeige  

`cd ..` = wechselt eine Verzeichnisebene höher  
`cd {/Pfad/Name/eingeben}` = wechselt in das benannte Verzeichnis  
`cd {/Pfad/Na}` + `[TAB]` = vervollständigt die begonnene Pfad-/Dateinamensangabe  
> Wiederholtes Drücken von `[TAB]` wechselt durch eventl. Alternativen

`md {Verz.name}` = erstellt ein neues Verzeichnis  
`rd {Verz.name}` = löscht ein bestehendes Verzeichnis (ACHTUNG: lässt sich nicht rückgängig machen!)

`cls` = räumt die Anzeige auf ("clear screen")

`help | more` = zeigt alle verfügbaren Befehle an  
`help {Befehlsname}` = zeigt ausführliche Info an

`[Pfeil hoch]` / `[Pfeil runter]` = ruft zuvor eigegebene Befehle wieder auf

# GIT in der Kommandozeile unter OSX nutzen

Es gibt viele Anleitungen im Internet, z.B. bei [heise.de](https://www.heise.de/ratgeber/Einfuehrung-in-die-macOS-Kommandozeile-Das-kleine-Terminal-Einmaleins-3463440.html).

## Grundlegende UNIX-Kommandos

`ls` = Inhalte im aktuellen Verzeichnis anzeigen
`ls -l` = ein Eintrag pro Zeile, mit weiteren Infos

`cd ..` = wechselt eine Verzeichnisebene höher  
`cd {/Pfad/Name/eingeben}` = wechselt in das benannte Verzeichnis  
`cd {/Pfad/Na}` + `[TAB]` = vervollständigt die begonnene Pfad-/Dateinamensangabe  
> Wiederholtes Drücken von `[TAB]` wechselt durch eventl. Alternativen

`mkdir {Name[.Endung]}` = erstellt ein neues Verzeichnis oder eine neue Datei
`rm {Name[.Endung]}` = löscht ein bestehendes Verzeichnis oder eine Datei (ACHTUNG: lässt sich nicht rückgängig machen!)

`[Pfeil hoch]` / `[Pfeil runter]` = ruft zuvor eigegebene Befehle wieder auf

# GIT in der Kommandozeile unter Linux nutzen

…
