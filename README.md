# IMISE LaTeX-Institutsvorlagen
LaTeX-Vorlagen für Seminar- und Abschlussarbeiten

## Deutsch

### Anpassung
Diese Vorlage ist eine inoffizielle Hilfestellung zum Aufsetzen von Seminar- und Abschlussarbeiten in LaTeX am IMISE.
Falls in Ihrem Seminar oder für Ihre Abschlussarbeit abweichende Vorgaben gelten, z.B. zu Rändern, Zeilenabstand, Schriftarten oder Zitierstil, dann haben diese Vorrang und die Vorlage muss entsprechend angepasst werden.
Bei Seminararbeiten ist aber erfahrungsgemäß keine Anpassung nötig.

### Abschlussarbeiten
Gemeint sind Bachelor- Diplom- und Masterarbeiten.
Abschlussberichte von Seminaren zählen zu Seminararbeiten.
Sie können diese Vorlage zwar für Abschlussarbeiten benutzen, wir empfehlen aber die wesentlich schönere [ClassicThesis-Vorlage](https://github.com/IMISE/imise-classicthesis).
Diese Vorlage ist eine Alternative für LaTeX-Anfänger, denen die ClassicThesis-Vorlage zu kompliziert ist.
Ich empfehle trotzdem, erst einmal die ClassicThesis-Vorlage auszuprobieren.

#### Weitere Vorraussetzungen 
Abschlussarbeiten dürfen nicht mit Ringbindung gedruckt werden, sie können z.B. eine Leim- oder Klemmbindung verwenden.
Die Eigenständigkeitserklärung muss unbedingt vorhanden und unterschrieben sein. 

### Weitere Informationen

* [Anträge und formale Richtlinien zu Abschlussarbeiten der Informatik beim Prüfungsamt](http://studium.fmi.uni-leipzig.de/fileadmin/Studienbuero/documents/Formulare/HinweiseAbschlussarbeit.pdf).
* [Ablauf und Betreuung im Projektbereich MIG des IMISE](http://www.imise.uni-leipzig.de/Lehre/MedInf/Abschlussarbeiten/Ablauf.jsp)

### Installation
Benötigt eine LaTeX-Installation mit Standardpaketen.
Minimalbeispiel auf Arch Linux:

    sudo pacman -S texlive-core texlive-science texlive-latexextra
    latexmk -pdf seminar.tex
    latexmk -pdf thesis.tex

## English
These are unofficial templates to get you started in doing your seminar paper, bachelor or master thesis. If there are differing requirements, you need to adapt these templates but at least for seminar papers this probably isn't the case.
