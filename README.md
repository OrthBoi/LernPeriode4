# Lern-Periode 4

Maxim Kohanov

20.2 bis 2.4.2024

## Grob-Planung

1. Wo stehen Sie mit Ihren Noten? In welchen Modulen waren Sie besonders stark; in welchen sind die ungenügend? Welche davon sind besonders wichtig?
Meinen Noten sind okay, aber nicht gut. Ich habe beim Modul 319 mein Portfolio nicht besonders gut geführt und habe deswegen eine ungenügende Note. Destrotrotz fühle ich mich in den Basics von C# einigermasen sicher.
   
2. Was hatten Sie sich am Ende von LP2 vorgenomenm? Was war Ihr VBV? Wie könnten Sie diesen besonders gut üben?
   
   
3. **Neu**: Was möchten Sie Neues lernen?
Objekt orientiertes programmieren
   
4. Was wäre ein geeignetes Projekt für diese LP4?
EIn Discord Bot programmieren

## 20.2.2024

✍️ Heute habe ich... (50-100 Wörter)
Ein wenig über den Prozess zur erstellung des Discord Bots recherchiert. Ich weiss nun wie ich diesen erstelle und programmiere. Danach habe ich noch für Modul 162 an der LB gearbeitet und habe diese nun bald fertig. 


## 27.2.2024

- [x] Einen Discord Bot erstellen 
- [ ] Grundlegenden Code aufbauen
- [ ] Anfangen benutzerdefinierte Funktionen zu programmieren

| Testfall-Nummer | Ausgangslage (Given) | Eingabe (When) | Ausgabe (Then) | Erfüllt? |
| --------------- | -------------------- | -------------- | -------------- | -------- |
| 1               |     Bot ist Online                 | %help               | liste mit allen Commands und was diese machen.               |  Nein        |

✍️ Heute habe ich... (50-100 Wörter)
Ich habe gelernt wie ich meinen Bot aufsetzte und habe ihn zum Server hinzugefügt. Ich muss ausserdem mit JS arbeiten (was mir nicht bewusst war) aber da es sehr ähnlich ist sollte es kein grosses Hinderniss sein, das nächste mal kann ich komplett durchstarten mit Coden. Damit der Bot online ist werde ich mithilfe einer [Website](https://google.com) den Bot hosten.


## 05.03.2024

- [ ] Bot Online bringen
- [ ] Eine Funktion namens %help schreiben der dem User erklärt wie der Bot funktioniert und was er alles machen kann.
- [ ] Ein Wörter Zähler coden der dem User sagt wie viele Wörter sein Text hat (nützlich für LernPeriode GitHub Commits)
- [ ] Paar Memes einbauen
      

| Testfall-Nummer | Ausgangslage | Eingabe | Ausgabe | Erfüllt? |
|-|-|-|-|-|
|1|W Bot ist Online ||||
|2|Bot ist Online|%help|Liste mit Funktionen und Commands||
|3|Bot ist Online|String|Anzahl Wörter||
|4|Bot ist Online|%meme|Zufälliger Meme||

Heute hatte ich grosse schwierigkeiten und konnte keines der Arbeitpakete erfüllen. Ich hatte probleme als ich den Bot mithilfe von nodemon online bringen wollte --> ![image](https://github.com/OrthBoi/LernPeriode4/assets/142886297/8fc501ca-3644-48c7-8199-91c7304e35eb)
Ich hatte schon vorher Problem mit Node, nämlich konnte ich den Code überhaupt nicht ausführen. Das lag daran das scripts auszuführen auf meinen Gerät deaktiviert war, dies habe ich dann mit Set-ExecutionPolicy -ExecutionPolicy RemoteSigned in PowerShell behoben. 

Ich werde beim nächsten mal den Bot sicherlich online bringen (somit wäre der schwerste Teil auch erledigt) die Funktionen mit % zu programmieren ist somit der einfachste Teil.

## Bis zum 12.03.2024

- [x] Nodemon Error beheben und Bot Online bringen
- [x] Eine Funktion namens %help schreiben der dem User erklärt wie der Bot funktioniert und was er alles machen kann.
- [x] Ein Wörter Zähler coden der dem User sagt wie viele Wörter sein Text hat (nützlich für LernPeriode GitHub Commits)
- [x] Paar Memes einbauen
      

| Testfall-Nummer | Ausgangslage | Eingabe | Ausgabe | Erfüllt? |
|-|-|-|-|-|
|1|W Bot ist Online |||Ja|
|2|Bot ist Online|%help|Liste mit Funktionen und Commands|Ja|
|3|Bot ist Online|String|Anzahl Wörter|Ja|
|4|Bot ist Online|%meme|Zufälliger Meme|Ja|

Ich habe heute den Bot online gebracht, das Problem mit Nodemon lag daran das mein Bot noch in keinen Server drinnen war. Ich habe alle Funktionen programmiert, am Anfang war es verwirrend aber nun habe ich einen überblick und weiss ungefähr wie die Basics von JS funktionieren zum Beispiel wie man mit Variabeln umgeht (try und var) da es kein string und int gibt wie in C# an denen ich mich bereits gewöhnt habe. Ich habe eine help liste erstellt und dabei \n benutzt für neue Zeilen. Für den Wörter Zähler musste ich mit ChatGPT nachhelfen nachdem mein Model nicht funktionert hat, das lag darn das die Funktionen anders heissen zBs heisst "contains" in JS "includes" usw. Als meme habe ich von der Kanti ein paar witzige Sprüche von unserem Wirtschaftslehrer genommen. Dieser Text hat 148 Wörter, das weiss ich weil es mir mein Bot gesagt hat :)

## 19.03.2024

- [x] Ich werde mir videos zu JS anschauen, Variabeln, Funktionen usw da es nicht so ähnlich ist wie erwartet
- [ ] ich will ein Reminder für Tests programmieren der Namen, Fach und Datum speichert. 5 Tage vor dem Test wird eine erinnerung geschickt

| Testfall-Nummer | Ausgangslage | Eingabe | Ausgabe | Erfüllt? |
|-|-|-|-|-|
|1|Bot ist Online |%reminder + Name + Fach + Datum|Erinnerung 5 tage vor x Datum||

Ich habe die basics von JS gelernt, was jedoch nicht sehr nützlich war wie erwartet da discord.js diese nicht 1 zu 1 übersetzt benutzt. Ich hatte grosse schwierigkeiten mit dem Discord Bot und bin immer wieder in Loops reingelaufen wobei der Bot sich selber geantowrtet hat und gecrasht ist. Ausserdem habe ich herausgefunden das der Discord Bot nur für wenige Minuten online ist sobald ich mein Visual Studio schliesse, somit ist er gar nicht nützlich und als Projekt untauglich. Darum habe ich mir ein neues Projekt überlegt und zwar ein Sport Manager mit Windows Forms womit man Kalorien und seine Sportlichen Aktivitäten Speichern kann und bestimmte Ziele berechnen kann wie zbs Gewichtsabnahme Gewichtszunahme usw.

## 26.03.2024

- [x] Ich werde die GUI zuende gestalten
- [x] Ich werde mithilfe von Arrays Daten speichern
- [ ] Ich werde benutzerdefinierte feedbacks einbauen je nach ziel

|Testfall Nummer| Ausgangslage | Eingabe | Ausgabe| Erfüllt? |
|-|-|-|-|-|
| 1 | GUI ist fertig | | |Ja|
| 2 | Eingabemöglichkeiten sind bereit | Kalorien, Sportaktivitäten usw| |Ja|
| 3 | Daten sind gespeicher | | Feedback je nach Ziel | | 

Ich habe die Gui fertig gestaltet und für jede Funktion (Kcal zählen und Aktivitäten erfassen) ein eigenes Fenster erstellt und übergebe die Daten auf das Main Forms. Mann kan beim Kcal zähler den Namen, Kcal anzahl und nährwerte angeben welche dann in arraysd gespeichert werden. Man kann individuelle Ziel festsetzten und sieht, ob man sie heute errreicht hat.

## 02.04.2024

- [x] Ich möchte das Feedback system programmieren und Tipps einbauen, wie man seine Ziele erreichen kann je nach Gebiet (Diät, Sport)
- [ ] Ich möchte das aussehen der App verbessern.

| Testfall-Nummer | Ausgangslage | Eingabe | Ausgabe | Erfüllt? |
|-|-|-|-|-|
|1|User hat Daten eingegeben|Sportaktivitäten/Nahrung|Persönliches Feedback|x|

## 23.04.2024

- [ ] Ich möchte mich heute auf's Modul 106 Konzentrieren da ich noch viele Lücken habe. Ich möchte 10 Arbeitsaufträge abschliessen.

      
## Reflexion

Formen Sie Ihre Zusammenfassungen in Hinblick auf Ihren VBV zu einem zusammenhängenden Text von 100 bis 200 Wörtern (wieder mit Angabe in Klammern).
