# Mein Youtube Video Beschreibungs Log

Hallo werter Zuschauer und oder vorbeilaufender Mensch,

Dies ist eine Übersicht bzw. Sammlung all der vielen vielen Beschreibungen die ich immer untern den Videos tue wenn ich sie veröffentliche. Wenn man das alles zusammenzählt habe ich bestimmt schon einige Tage Arbeit in das Schreiben von solchen Texten gesteckt. Viele mit haarsträubend vielen Rechtschreibfehlern. Bei anderen fehlt einfach eine klare Linie oder überhaupt irgendwie der Sinn. So manche sind bestimmt sinnentleert und einfach nur durch Übermüdung zu erklären. Aber andere enthalten vielleicht Einsichten die ich während des Spielens so nicht in der Lage war zu geben.

## Fragen ? Antworten!

* **Da scheinen mir aber schon einige viele Spiel zu fehlen**

  Das ist korrekt. Für den Anfang habe ich nur die Beschreibungen eingefügt die ich tatsächlich da hatte. Also alles was ich wirklich per Hand eingefügt und ab kopiert habe. Recht zeitnah werde ich hier aber auch die restlichen Beschreibungen hinzufügen, die sind dann aber Computer generiert bzw. aus der Youtube API ausgelesen und in ein entsprechendes Format gelegt.

* **Was zur Hölle ist eigentlich dieses Markdown?**

  Eine relativ simple Methode in begrenzten Umfang Texte zu schreiben. Es erlaubt einige Formatierungen ohne das ganze Zeug das man bei _großen_ Texteditoren wie Word dran hängen hat. Es wird gerne von Softwareentwicklern genutzt weil letztendlich alles auf reinen Text basiert den man gut auf Unterschiede prüfen kann. Außerdem kann man es im Gegensatz zu beispielsweise HTML auch schön flüssig tippen. Weiter Informationen hat [Wikipedia](https://de.wikipedia.org/wiki/Markdown)

* **Wieso hast du dann überhaupt irgendwelche Beschreibungen ab kopiert?**

  Gute Frage! Die mir nie jemand so stellen wird. Ursprünglich habe ich die Beschreibungstexte angefangen ab zu kopieren weil es Unstimmigkeiten gab. Mehr als nur ein paar Mal ist es vorgekommen das ich Texte geschrieben habe. Diese waren dann im Videomanager auch zu erkennen aber wenn man das Video selbst angeklickt hat war auf einmal nichts mehr da. Ich weiß nicht ob es an meinem Browser lag, einer Sub-Version des *Youtube Studios* oder an kosmischer Gammstrahlung die genau den richtigen Bit geflippt hat. Da ich mir schon ein wenig Mühe gebe dachte ich mir das ich ein Backup des Beschreibungen brauche. Am Anfang war alles eine große Datei.

* **Ist Github nicht irgendwie der falsche Ort dafür?**

  Da kann man jetzt viel argumentieren, aber ich habe schon mehr als ein Code-Repo gesehen das nur aus einer Link Sammlung bestand. Außerdem zeigt mit Github Markdown Dateien schön aufgelistet an. Das ist eigentlich alles was ich brauche. Klar könnte ich das auch mit einem *Flat File System CMS* auf eigenen Webspace hosten, aber warum? Kostet nur Geld. Und ich denke Microsoft kann die paar Megabyte Textdateien vertrösten.

* **Manche Beschreibungstexte sehen aber nicht schön aus, warum?**

  Das ärgert mich tatsächlich und ich bin noch am überlegen wie ich das am besten löse. Am Anfang habe ich die Beschreibung noch in einem Zitat-Feld gemacht, also sowas hier:
  
  > That’s the funny thing about arriving somewhere," [..] “Once you’re there, the only thing you can really do is leave  again.”  
  >   ―      Brandon Sanderson, The Final Empire  
  
  Das sah zwar irgendwie gut aus und wird vom Github Markdown Interpreter auch schön dargestellt hat aber den Nachteil das bestimmte Zeilen trotz Zeilenumbruch bei Youtube in einer Zeile dargestellt werden. Das gefällt mir nicht. Also bin ich auf Code Blocks umgestiegen, also sowas hier:
  
  ```python
  def main:
  	loop_var = ["green", "red", "yellow"]
  	for item in loop_var:
  		print(item)
  ```
  
  nur halt als Codeblock für _Markdown_. Das sieht zwar ganz schön aus und ich kann das auch gut ab kopieren. Ärgerlicherweise scheint *Github* das ein wenig falsch zu interpretieren. Oder auch richtig. Je nachdem. Der eigentliche Text hat ja wirklich keinen Zeilenumbruch und bei manchen Sprache (zum Beispiel Python das ich oben im Beispiel benutzt habe) ist ein Zeilenumbruch tatsächlich relevant. Ich weiß nicht so recht wie ich hier fortfahren soll. Für meine eigene Anwendung ist es relativ egal, ich verwende lokal [Typora](https://typora.io/) zum editieren und sieht es _für mich_ richtig aus.
  
* **Warum machst du das hier überhaupt**?

  In den Worten von _GladOS_: 
  
  > "We Do What We Must Because We Can"
  
  Einfach nur weil ich kann. Der Aufwand ein:
  ```shell
  git add .
  git commit -m "Update `date +'%Y-%m-%d %H:%M:%S'`"
  git push origin
  ```
  am Ende des Schreibens zu machen ist für mich quasi kein Aufwand und ich kann mich in dem Gedanken wissen das ich eine weitere  Stufe an Backup habe
  