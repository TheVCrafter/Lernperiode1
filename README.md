# Lern-Periode 1

23.08.2024-20.09.2024

## Grob-Planung
Ich möchte mein **Programmieren verbessern**. Dazu habe ich mir zum Ziel gesetzt ein **Hangman in C# zu programmieren**.
Der Code soll ein zufälliges **Deutsches Wort** wählen, welches man anschliessend erraten muss. Wenn man einen Buchstaben errät wird er im Wort 
angezeigt. Falls man einen Falschen Buchstaben rät, Wird der Hangman um ein Strich erweitert. Wenn man das Wort erraten wird bevor der Hangman vollständig ist,
gewinnt man das Spiel und die Konsole wird geschlossen. Falls der Hangman vervollständigt wird verliert man das Spiel und die Konsole wird geschlossen

## 30.08.2024
- [x] Weitere Planung des Projekts (PAP-Designer)
- [x] Beginnen mit Programmieren, das jeder Buchstaben eines Wortes(zunächst nur eins) als _ anzeigt wird und beim Erraten eines Buchstabens des Wortes wieder als Buchstaben.
- [x] "
- [x] "

Heute habe ich eine .Txt-Datei mit *vielen deutschen Wörtern* heruntergeladen, und anschliessend mein Programm dazu gebracht, ein Wort aus der Liste auszuwählen
und anschliessend in form von *Unterstrichen* auszugeben. Ausserdem kann man inzwischen Buchstaben raten und die **Unterstriche werden durch die Erratenen Buchstaben ersetzt**.
Ein Problem ist noch, das dass Programm zwischen **Gross- und Kleinbuchstaben unterscheidet**, ein *richtiger Buchstabe also nicht erkannt wird wenn er im Lösungswort gross geschrieben ist,
aber in der Eingabe klein*.

## 06.09.2024
- [x] Versuchen das Programm dazu zu bringen nicht zwischen Gross- und Kleinbuchstaben zu unterscheiden
- [x] Die verschiedenen Phasen des Hangmans designen
- [x] Die Phasen in den Code einbauen
- [x] Eventuell weitere Sachen einbauen (z.B. eine Restart-/Beenden-Option innerhalb der Konsole beim Ende des Spiels)

Heute habe ich es geschafft, dass das Programm bei der Eingabe eines Buchstabens nicht mehr zwischen Gross- und Kleinschreibung unterscheidet. Ausserdem habe ich mithilfe von **Ascii Art**
einen Hangman erstellt und diesen anschliessend in mein Spiel eingebaut. Auch die Restart/ Beenden option am Ende des Spiels konnte ich fertigstellen. Danach habe ich noch eine Start 
funktion eingebaut und mit Hilfe von Ascii Art das Spiel besser Designt. Ich habe auch noch programmiert, dass das zu erratene Wort im **Game Over Menü** angezeigt wird. 
Das Spiel ist eigentlich so gut wie fertig, trotzdem möchte ich in der Nächsten Stunde noch ein paar zusätzliche Sachen einbauen. Ich möchte zum Beispiel versuchen, auch **Ton in das Spiel 
einzufügen** und ausserdem das Design noch verbessern.

## 13.9.2024
- [x] Ton in das Spiel einfügen
- [x] Design verbessern
- [x] eventuell auch noch weitere Funktionen einbauen
- [ ] Nach neuer Projektidee suchen

Zu Beginn hab ich heute recherchiert wie genau man Töne mit der Konsole ausgeben kann und bin schnell auf die SoundPlayer funktion gestossen. Anschliessend habe ich im internet nach passenden 
Tönen für mein Spiel gesucht. Ich wollte für das Spiel nur 8-Bit-Sounds verwenden. Ich brauchte eine **Titelmusik**, einen **Ton welcher beim Start des Spieles abgspielt wird**, einen **Ton für korrekte 
Antworten**, einen **für falsche Antworten**, einen **Ton welcher abgespielt wird wenn man das Wort errät** und schliesslich noch einen **Ton welcher abgespielt wird wenn der Hangman vervollständigt wird**. 
Auf [Pixabay](www.pixabay.com) wurde ich schliesslich fündig und konnte die Sounds *kostenlos* herunterladen. Anschliessend musste ich die Downloads vom *MP3-Format* ins *WAV-Format* konvertieren. 
Dies habe ich Online mit [Cloudconvert](www.cloudconvert.com) gemacht. Dann habe ich die WAV-Dateien in den **Debug-Folder** des Projektes verschoben und anschliessend im Code eingebaut. Dabei habe ich gemerkt, 
dass die Konsole nur einen Sound zugleich abspielen kann, aber das war zum Glück nicht weiter tragisch. Als nächstes habe ich das Farbdesign des Spiels angepasst. Dies machte ich mit
`Console.Foregroundcolor`. Nachdem ich so das Spiel relativ schön gestalten konnte, habe ich die Datei mit den deutschen Wörtern auch noch in den Debug-Folder verschoben und den Code 
entsprechend umgebaut. Leider bin ich noch nicht dazu gekommen, nach einer neuen Projektidee zu suchen.

## 20.9.2024
- [x] Die Funktion hinzufügen, dass bereits geratene Buchstaben nicht nochmals geraten werden können
- [ ] Neue Projektidee suchen

Heute habe ich versucht zu verhindern, dass **bereits geratene Buchstaben nicht nochmals geraten** werden können. Nachdem ich den Code dazu geschrieben hatte, gab es beim Starten des Programms 
ständig eine Fehler Meldung, weil mein Antivirus das Programm als Virus erkannte. Also habe ich eine neue Projektdatei erstellt und den ganzen Code dort hinein kopiert und es hat tatsächlich 
funktioniert. Anschliessend habe ich noch versucht eine Funktion einzufügen, welche erkennt wann mehrere Buchstaben eingegeben werden und es anschliessend einen Fehler gibt. Jedoch funktioniert 
dies bis jetzt noch nicht so wie ich es gerne möchte.

## Reflexion
Diese Lernperiode hat mir geholfen viele neue Sachen über C# zu lernen und bereits bekanntes richtig anzuwenden. Ich habe zum Beispiel gelernt wie und wann man bestimmte *Loops* anwendet, wie 
man *Arrays und Indexes* nutzt, wie man if, else if und else anwendet und sogar wie man *Sound in das Programm einfügen* kann (.net Framework). Auch mit *Funktionen* habe ich mich in dieser Lernperiode 
befasst. Ausserdem habe ich gelernt wie man *Ascii-Art in der Konsole ausgeben* kann. Ich habe herausgefunden, wie wichtig die Grundlagen sind um auch kopliziertere Programme zu schreiben und wie 
viele Sachen man nur damit überhaupt schon programmieren kann. In der nächsten Lernperiode muss ich unbedingt meinen Variabeln sinnvollere Namen um den **Überblick im Code nicht zu verlieren**. 
Es wäre auch Sinnvoll für mich, zukünftig auch **Notizen in den Code einzufügen**. Ich habe auch bemerkt, dass es mir viel mehr spass macht zu programmieren, wenn ich auch wirklich gefordert werde. 
Also werde ich auch in der nächsten Lernperiode vermutlich versuchen, etwas eher kompliziertes zu programmieren.

## fertiges Projekt
Bei meinem Code handelt es sich wie bereits erwähnt um ein Hangmanspiel. Das Ziel ist es ein Wort herauszufinden indem man rät welche Buchstaben darin enthalten sein könnten. Wenn man einen Buchstaben rät welcher nicht in dem Wort enthalten ist, wird der Hangman erweitert. Die bereits geratenen Buchstaben werden übrigens angezeigt. Man kann ausserdem auch einfach das richtige Wort eingeben um schneller zu gewinnen. Gibt man jedoch ein flasches Wort ein wird auch der Hangman erweitert. Wenn der Hangman vervollständigt wird, verliert man das Spiel. Kann man das Wort jedoch vorher erraten, gewinnt man. Anschliessend ist es möglich das Spiel neu zu starten.
