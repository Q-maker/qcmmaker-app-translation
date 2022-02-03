# So strukturieren Sie eine txt-Datei, um Fragen und Antworten zu enthalten.
Die Frage-Antwort-Textdateien sind so strukturiert, dass sie einen oder mehrere Abschnitte mit Fragen und Antwortvorschlägen enthalten.
Wie strukturiere ich einen Frage-Antwort-Bereich?
Lassen Sie uns am Beispiel lernen; siehe Frage-Antwort-Abschnitt unten:

```
Unter den folgenden Tieren,
Welches dieser Tiere lebt im Wasser?
-Katze
-Hund
*Fisch
-Pferd
> Fische sind Wassertiere, die sich bevölkern
Meere, Ozeane, Flüsse, Teiche und Wasserstellen.
```

An diesem Beispiel können wir das hervorheben:
   * Ein Abschnitt beginnt immer mit dem Wortlaut der Frage, er kann mehrzeilig geschrieben werden.
     Es wird jedoch kein Zeilenumbruch akzeptiert (weiße Linie entspricht zwei Zeilen Return)
   * Die vorgeschlagenen Antworten folgen dem Wortlaut der Frage und sind so angeordnet, dass:

            -Den wahren Sätzen ist ein Sternchen vorangestellt (*)

            -Den falschen Sätzen ist ein Bindestrich vorangestellt (-)

            Hinweis: Sätze können auch mehrzeilig geschrieben werden (ohne Zeilenumbruch)
   * An letzter Stelle haben wir den Kommentar: ihm muss das Symbol (>) vorangestellt werden und kann auch ohne Zeilenumbruch über mehrere Zeilen geschrieben werden (Achtung: das Schreiben eines Kommentars ist nicht zwingend)



So setzt sich ein Frage- und Antwortteil zusammen.
Ein Fragebogen besteht jedoch aus einem bis mehreren Abschnitten zur Beantwortung von Fragen. Trennen Sie dazu einfach jeden Frage-Antwort-Abschnitt mit einem Zeilenumbruch;
Sie müssen also zweimal zu der Zeile zurückkehren (diejenigen, die zu einer leeren Zeile führen).
Unten sehen Sie ein Beispiel mit einem Satz von zwei (2) Frage- und Antwortabschnitten. (Beachten Sie die leere Zeile zwischen den beiden Abschnitten)

```
Unter den folgenden Tieren,
Welches dieser Tiere lebt im Wasser?
-Katze
-Hund
*Fisch
-Pferd
> Fische sind Wassertiere, die sich bevölkern
Meere, Ozeane, Flüsse, Teiche und Wasserstellen.

Welche dieser Tiere fliegen?
*Taube
-Der Hund
*Der Rabe
*Der Adler
> Die Taube, der Rabe und der Adler sind alle fliegende Vögel
```

**Note:**  
Auch wenn die Importfunktion fast alle Codierungen von Textdateien unterstützt, sollten Sie bei Codierungsproblemen lieber die **UTF-8**-Codierung verwenden, um die beste Leistung zu gewährleisten.

Fragen? Ideen? Klärungsbedarf? Kontaktieren Sie uns unter unserer E-Mail: [qcmmakerapp@gmail.com](mailto:qcmmakerapp@gmail.com)
