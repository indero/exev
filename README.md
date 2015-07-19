# Experimentieren und Evaluieren
[![PDF Status](https://www.sharelatex.com/github/repos/mexmirror/exev/builds/latest/badge.svg)](https://www.sharelatex.com/github/repos/mexmirror/exev/builds/latest/output.pdf)

Zusammenfassung der Vorlesungen des Moduls Experimentieren und Evaluieren an der Hochschule für Technik Rapperswil

## Kompilieren
Um das Dokument zu einem PDF zu machen, benötigt man eine LaTeX Distributuion. Unter Windows ist es für einsteiger am einfachsten mit [MiKTeX](http://miktex.org/)
Unter Linux benötigt man zwei Pakete, `texlive-latex-recommended` und `texlive-lang-german`. Dazu verwendet man am besten den Paketmanager seines Vertrauens. Danach kann man mit pdflatex ein PDF kompilieren.

	pdflatex main.tex

Ggf. muss man diesen Befehl zwei bis drei Mail ausführen, da ansonsten Labels nicht richtig erkannt werden etc.
