## Vorlage für das wissenschaftliche Arbeiten am SZI der DHBW Lörrach
#### Orientiert wurde sich teilweise am Projekt von Daniel Spitzer: https://gitlab.com/spitzerd/latex-vorlage-dhbw-loerrach-szi/-/tree/master

### Buildvorgehen:
1. lualatex document.tex
2. biber document
3. lualatex document.tex
4. lualatex document.tex
### Beispielsweise in der Shell:  
lualatex document.tex && biber document && lualatex document.tex && lualatex document.tex 


