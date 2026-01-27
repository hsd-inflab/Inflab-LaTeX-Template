![Build LaTeX document](https://github.com/TimB87/HSD-LaTeX-Template/workflows/Build%20LaTeX%20document/badge.svg?branch=master)
# Inflab-LaTeX-Template
Dies ist ein LaTeX Template zur Erstellung einer Bachelor-/Masterthesis, dass grundsätzlich der PO des FB EI genügen soll.

## Allgemeines

Willkommen! Diese LaTeX-Vorlage ist für Abschlussarbeiten im Informatik-Labor (InfLab) gedacht. LaTeX bietet gegenüber herkömmlichen Textverarbeitungsprogrammen mehrere Vorteile: sauber formatierte Dokumente, konsistente Struktur, automatische Verzeichnisse und ein professionelles Layout, das besonders bei wissenschaftlichen Arbeiten sinnvoll ist.
Diese Beschreibung bezieht sich auf die Nutzung von texlive und TexStudio. Zwar sollte die Vorlage auch mit anderen Editoren/Distribution funktionieren, dies wurde jedoch nicht getestet.

## Voraussetzungen

### Windows
- Eine LaTeX-Distribution (Tex Live wird empfohlen)
- Ein Editor (TeXstudio wird empfohlen)

<!-- ### Linux
- Wer Linux nutzt, hat meist bereits die nötigen Werkzeuge oder kann sie über die Paketverwaltung installieren.

### Mac
- todo

-->

## Vorgehensweise

### Wenn LaTeX neu für dich ist
1. Vorlage aus dem **Master-Branch** herunterladen  
2. In **TeXstudio** öffnen und mit **LuaLaTeX** kompilieren  
3. PDF lesen und gleichzeitig den Quellcode vergleichen, um ein erstes Verständnis für LaTeX zu bekommen  

### Wenn LaTeX bekannt ist oder nachdem du die Einführung gemacht hast
1. Den **Branch „blank“** herunterladen (ZIP)  
2. In `authorinfo.tex` die eigenen Daten eintragen  
3. In `main.tex` das Lock-Flag entfernen, falls kein Sperrvermerk vorgesehen ist  
4. Mit dem Schreiben beginnen
   
### Kompilieren der Vorlage
Wichtig: Die Vorlage nutzt arara. Das Tool sollte mit texlive bereits mitinstalliert worden sein. Damit die Vorlage korrekt rendert, muss mit arara kompiliert werden.
So kann arara in TexStudio eingerichtet werden:
1. Optionen -> TexStudio konfigurieren..
2. Auf Reiter "Erzeugen"
3. Wie im folgenden Bild ausfüllen
![Alt-Text](images/textstudio_settings.png)

Im Anschluss für einen 

**FullBuild** (z.B. Nach Anpassung von Abbildungen, Quellen etc.)
Tools -> Benutzer -> arara auswählen

**Quickbuild** (Tippfehler korrigieren, kleinere Änderungen)
auf den grünen Startknopf oben drücken. 

## Abschließender Hinweis

Versionierung ist extrem sinnvoll, damit Texte und Fortschritt nicht versehentlich verloren gehen. GitHub eignet sich dafür besonders gut.
