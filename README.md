# BerufsBuddy

## Herzlich willkommen bei BerufsBuddy - deinem Berufsberater in der Tasche!

### Ziel des Projekts ###
Ziel der Webseite von BerufsBuddy ist, dass die Jugendlichen selbst, aber auch die Eltern und Schulen sowie mögliche Partner einen Eindruck erhalten, was BerufsBuddy ist, welche Werte wir vertreten und wer dahinter steckt.

### Ablauf ###
Wir haben uns für die Designvorlage von Wanaka entschieden. Somit haben wir ihr Mockup als Inspiration genommen und einen Grossteil davon so umgesetzt. Vereinzelt haben wir in der effektiven Webseite ein paar Änderungen vorgenommen, da es entweder besser umsetzbar war oder in Hinsicht vom responsiven Design besser aufging. Für das Design haben wir uns für das Flexbox-Model entschieden.

### Schwierigkeiten ###
Zu grösseren Schwierigkeiten ist es nicht gekommen.
Die grösste Schwierigkeit war der Slider, den wir vielleicht auf etwas ungewohnte Weise kreiert haben. Mithilfe von Javascript haben wir uns für eine Variante für Display: none und Display: block entschieden. Im Gegenzug haben wir dafür keine Vorlage benutzt.
Eine andere Schwierigkeit war der doppelte Border um die Bilder und weiteren Flächen. Mithilfe einer kurzen Internetrecherche kamen wir dann auf eine passende Lösung mit dem Attribut :before.

### Hilfsmittel ###
Für den Code haben wir einige Code-Vorlagen aus bestimmten Webseites verwendet und angepasst, darunter:
w3schools.com
css-tricks.com
stackoverflow.com
Zudem haben wir den Code mit https://validator.w3.org/ und https://jigsaw.w3.org/css-validator/ geprüft.
Grundsätzlich haben wir aber die Mehrheit der Webseite aufgrund der bisherigen Programmierkenntnisse aufgebaut.

### *Wichtig für validen Code* ###
Warnings haben wir wo sinnvoll angepasst, andere erschienen uns nicht nötig.
Eine Error-Meldung mussten wir stehen lassen. Beim Einbetten der Google Fonts sind in der Schrift Leerschläge drin. Das erachtet der Validator als nicht richtig. Um die Schrift weiterhin zu nutzen, ignorierten wir diese Fehlermeldung.
Ausserdem dürften Buttons nicht in einem <a>-Tag drin sein. Da wir die mailto-Funtkion mit onclick sonst nicht hinbekommen haben, haben wir trotzdem auf diese Variante zurückgegriffen.
Ausserdem erschien es uns beim Video sinnvoll, eine Grösse von 100% zu geben statt der Pixelzahl. Daher kommt hier ebenfalls eine Fehlermeldung. Ebenso bei der Google-Maps-Karte.
