Die Projektarbeit beschäftigt sich mit dem Thema Codereview, stellt die Vor- und Nachteile dar und vergleicht 6 Codereview-Tools. Das Ergebnis der Arbeit ist die Entscheidung für einen dieser Systeme/Tools.

### Buildvorgehen:
1. lualatex document.tex
2. biber document
3. lualatex document.tex
4. lualatex document.tex

### Beispielsweise in der Shell:  
lualatex document.tex && biber document && lualatex document.tex && lualatex document.tex 

### In TexMaker unter Schnelles Übersetzen User-Buildvorgehen:
lualatex -interaction=nonstopmode %.tex|biber %|lualatex -interaction=nonstopmode %.tex|lualatex -interaction=nonstopmode %.tex

### Für das Inhaltsverzeichnis:
Bearbeite die Datei .bib in Ordner \content\bib.

Füge die Quellen in BibTeX Form hinzu.
Tipp: Verwende JabRef.
