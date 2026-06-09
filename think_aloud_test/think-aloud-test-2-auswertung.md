# Auswertung Think-Aloud-Test 2

## Test 2: An einem Quiz teilnehmen

### Testsituation

Rolle der Testperson: Studentin / Teilnehmerin

Aufgabe:

> An einem Quiz teilnehmen, Fragen beantworten und erkennen, ob Antworten erfolgreich abgegeben wurden.

Der Test wurde zweimal mit unterschiedlichen Quizzen durchgefuehrt. Dadurch lassen sich Unterschiede im Teilnahmeflow gut vergleichen.

## Kurzfazit

Der Einstieg ueber den Code wurde in beiden Durchlaeufen als einfach und verstaendlich wahrgenommen. Die groessten Unterschiede zeigten sich danach im eigentlichen Frage- und Antwortflow.

Im ersten Quiz war die Testperson unsicher, was sie tun sollte, insbesondere bei einer bild- oder showcaseartigen Frage. Sie vergroesserte ein Bild, die Zeit lief ab, und sie verstand die erwartete Aktion nicht eindeutig.

Im zweiten Quiz war der Flow deutlich klarer. Die Testperson erkannte Auswahl, Absenden, Rueckmeldung und Fragetypen besser. Positiv hervorgehoben wurden der sichtbare Auswahlrahmen, der farbige Absenden-Button und die Rueckmeldung nach der Antwort.

Der wichtigste uebergreifende Befund:

> Die Teilnahme funktioniert grundsaetzlich gut, aber der Status nach einer Antwort und die visuelle Hervorhebung der naechsten Aktion muessen immer eindeutig sein.

## Positive Befunde

| Beobachtung | Bedeutung fuer Nutzerqualitaet |
|---|---|
| Der Code-Einstieg auf der Startseite wurde als einfach und direkt beschrieben. | Der Einstieg in den Teilnahmeflow ist niedrigschwellig. |
| Die Team-/Avatar-Auswahl wurde als motivierend und positiv wahrgenommen. | Gamification kann Aktivierung und Freude an der Nutzung erhoehen. |
| Im zweiten Quiz war die Auswahl durch Rahmen gut erkennbar. | Sichtbares Interaktionsfeedback reduziert Unsicherheit. |
| Der farbige Absenden-Button im zweiten Quiz wurde als klar und hilfreich beschrieben. | Primaere Aktion ist besser auffindbar. |
| Multiple Choice wurde verstanden, auch durch die Beschriftung "Multiple Choice". | Fragetyp und Interaktionsmodell waren nachvollziehbar. |
| Freitextfeld wurde verstanden. | Eingabeaufforderung und Eingabeelement passten zusammen. |
| Die Uebersicht im zweiten Quiz wurde als gut beschrieben. | Orientierung im laufenden Quiz war vorhanden. |

## Beobachtete Befunde nach Durchlauf

### Durchlauf 1

| Nr. | Beobachtung | Qualitaetsproblem | Schweregrad | Verbesserungsidee |
|---|---|---|---|---|
| 1 | Die Testperson konnte dem Quiz ueber den Code problemlos beitreten. | Kein Problem; positiver Befund. | 0 | Code-Einstieg beibehalten. |
| 2 | Team-/Avatar-Auswahl wurde positiv wahrgenommen. | Kein Problem; positive Aktivierung. | 0 | Auswahl beibehalten, ggf. inklusiv und breit verstaendlich gestalten. |
| 3 | Bei einer Frage mit Bild war unklar, was zu tun ist. Die Testperson klickte auf das Bild bzw. vergroesserte es. | Aufgabenanforderung und Interaktion waren nicht eindeutig. | 3 | Primaere Antwortaktion visuell staerker hervorheben; klare Aufgabenanweisung nahe beim Eingabeelement. |
| 4 | Die Zeit lief ab, waehrend die Testperson noch interpretierte, was sie tun sollte. | Zeitdruck verstaerkt Unklarheit und fuehrt zu Abbruch-/Fehlererlebnis. | 3 | Bei komplexeren Fragetypen klarere Anleitung oder weniger dominante Bildinteraktion. |
| 5 | Nach dem Absenden war nicht eindeutig, ob die Antwort erfolgreich abgegeben wurde. Die Testperson hoffte, dass es funktioniert hat. | Fehlendes oder zu schwaches Systemfeedback nach Antwortabgabe. | 3 | Deutliche Erfolgsmeldung, z. B. "Antwort gesendet", mit Haken und ggf. Screenreader-Live-Region. |
| 6 | Der weiterlaufende Timer wurde als verwirrend empfunden. | Status nach Antwortabgabe passt nicht zur Erwartung der Nutzerin. | 2 | Erklaeren oder visuell unterscheiden: Antwort gesendet, Wartezeit bis zur naechsten Frage laeuft. |
| 7 | Eingabe-/Absenden-Bereich wurde als zu wenig praesent wahrgenommen. | Primaere Aktion ist nicht stark genug hervorgehoben. | 2 | Absenden-Button kontrastreicher und klarer als Hauptaktion darstellen. |

### Durchlauf 2

| Nr. | Beobachtung | Qualitaetsproblem | Schweregrad | Verbesserungsidee |
|---|---|---|---|---|
| 1 | Code-Eingabe und Beitritt waren wieder klar. | Kein Problem; positiver Befund. | 0 | Beibehalten. |
| 2 | Die Testperson erkannte Auswahlstatus durch Rahmen um die Antwort. | Positives Feedbackmuster. | 0 | Dieses Muster konsistent in allen Fragetypen nutzen. |
| 3 | Der farbige Absenden-Button wurde als deutlich besser beschrieben. | Positives Muster fuer primaere Aktion. | 0 | Kontrast und visuelle Prioritaet als Designstandard uebernehmen. |
| 4 | Der Timer lief auch nach Absenden weiter und irritierte weiterhin. | Statuslogik bleibt erklaerungsbeduerftig. | 2 | Nach Absenden klar anzeigen, warum Timer weiterlaeuft. |
| 5 | "Antwort gesendet" wurde wahrgenommen und als verstaendlich beschrieben. | Positives Systemfeedback. | 0 | Rueckmeldung konsistent und barrierefrei absichern. |
| 6 | Multiple Choice wurde durch Frageformulierung und Label verstanden. | Positiver Befund. | 0 | Fragetyp-Label beibehalten. |
| 7 | Freitext wurde verstanden. | Positiver Befund. | 0 | Beibehalten. |
| 8 | Am Ende fragte die Testperson "Wieso war ich falsch?" | Ergebnisfeedback ist moeglicherweise nicht ausreichend erklaert. | 2 | Bei falschen Antworten kurz anzeigen, welche Antwort erwartet wurde oder warum die Bewertung erfolgte. |

## Staerkste Befunde fuer das Referat

### Befund 1: Der Einstieg per Code funktioniert gut

Beobachtung:

Die Testperson empfand den Einstieg ueber den Code als einfach, weil die Eingabe direkt auf der Startseite sichtbar war.

Qualitaetsbedeutung:

Das ist ein positiver Nutzerqualitaetsbefund. Der Einstieg ist niedrigschwellig und unterstuetzt schnelle Teilnahme in einer Lehrveranstaltung.

Geeignete Formulierung:

> Der Teilnahme-Einstieg ueber den Code war fuer die Testperson sofort verstaendlich. Das zeigt, dass arsnova.eu an dieser Stelle bereits eine gute Einstiegshuerde bietet.

### Befund 2: Antwortstatus muss nach dem Absenden eindeutig sein

Beobachtung:

Im ersten Durchlauf war die Testperson unsicher, ob ihre Antwort wirklich abgegeben wurde. Sie sagte sinngemaess, sie habe auf Senden gedrueckt und gehofft, dass es funktioniert hat.

Qualitaetsproblem:

Das Systemfeedback nach der Antwortabgabe war nicht eindeutig genug oder wurde nicht wahrgenommen.

Nutzerqualitaetsbezug:

Wenn Nutzerinnen und Nutzer nicht erkennen, ob eine Antwort abgegeben wurde, entsteht Unsicherheit. In Live-Lehrveranstaltungen kann das zu Stress und Fehlbedienung fuehren.

Moegliche Verbesserung:

- deutliche Erfolgsmeldung: "Antwort gesendet"
- visueller Haken
- Statusbereich nahe beim Absenden-Button
- Screenreader-kompatible Live-Region
- klare Unterscheidung zwischen "Antwort abgegeben" und "Zeit bis zur naechsten Frage"

### Befund 3: Primaere Aktion muss visuell klar hervortreten

Beobachtung:

Im zweiten Durchlauf wurde der farbige Absenden-Button als deutlich besser und leichter verstaendlich beschrieben. Im ersten Durchlauf war der Eingabebereich weniger praesent.

Qualitaetsproblem:

Wenn primaere Aktionen nicht klar genug hervorgehoben sind, steigt die kognitive Last.

Nutzerqualitaetsbezug:

Eine klare visuelle Hierarchie hilft besonders neuen Nutzerinnen und Nutzern, die naechste Handlung schnell zu erkennen.

Moegliche Verbesserung:

- Absenden-Button konsequent als primaere Aktion gestalten
- Auswahlstatus klar sichtbar machen
- Kontrast im hellen und dunklen Modus pruefen
- Fokuszustand fuer Tastaturbedienung sichtbar machen

### Befund 4: Bild- oder Showcase-Fragen brauchen klarere Handlungsanweisung

Beobachtung:

Im ersten Durchlauf sah die Testperson ein Bild, klickte es an bzw. vergroesserte es und verstand nicht, was sie beantworten sollte. Die Zeit lief dabei ab.

Qualitaetsproblem:

Die visuelle Aufmerksamkeit lag auf dem Bild, aber die erwartete Antwortaktion war nicht klar genug.

Nutzerqualitaetsbezug:

Bei komplexeren oder bildlastigen Fragen muss die Aufgabe besonders eindeutig sein, sonst wird das Bild selbst zur falschen Interaktionsspur.

Moegliche Verbesserung:

- Aufgabenanweisung naeher an Antwortbereich platzieren
- Bildvergroesserung nicht mit Antwortaktion verwechselbar machen
- Antwortbereich visuell staerker priorisieren
- Bei Bildfragen kurzen Hinweis anzeigen: "Waehle unten deine Antwort aus"

### Befund 5: Timer nach Absenden ist erklaerungsbeduerftig

Beobachtung:

In beiden Durchlaeufen irritierte der weiterlaufende Timer nach dem Absenden.

Qualitaetsproblem:

Die Testperson erwartete, dass der Timer nach der eigenen Antwort stoppt. Wenn er weiterlaeuft, entsteht Unsicherheit, ob die Antwort wirklich abgeschlossen ist.

Moegliche Verbesserung:

- Nach Absenden anzeigen: "Antwort gesendet - Warte auf die naechste Frage"
- Timer semantisch umbenennen oder in Wartezustand anders darstellen
- Fortschritts-/Statusanzeige klarer trennen: Antwortstatus vs. verbleibende Fragezeit

## Vergleich der beiden Durchlaeufe

| Aspekt | Durchlauf 1 | Durchlauf 2 | Erkenntnis |
|---|---|---|---|
| Einstieg per Code | klar | klar | Einstieg funktioniert gut. |
| Aufgabenverstaendnis | unklar bei Bildfrage | klar bei einfachen Frageformaten | Komplexere Fragetypen brauchen bessere Anleitung. |
| Auswahlstatus | nicht deutlich genug wahrgenommen | gut sichtbar durch Rahmen | Auswahlfeedback sollte konsistent stark sein. |
| Absenden | unsicher | deutlich besser durch farbigen Button | Primaere Aktion muss visuell hervortreten. |
| Rueckmeldung | Antwortabgabe nicht eindeutig | "Antwort gesendet" wurde wahrgenommen | Statusfeedback ist zentral. |
| Timer | irritierend | weiterhin irritierend | Timer nach Antwortabgabe braucht bessere Erklaerung. |
| Gesamtwirkung | verwirrend | deutlich leichter | Layout und visuelle Hierarchie beeinflussen Nutzbarkeit stark. |

## Verbindung zu didaktischer Dokumentation

Aus Test 2 ergeben sich gute Inhalte fuer eine Guidde-Anleitung:

- "An einem Quiz teilnehmen"
- "Code eingeben und Team auswaehlen"
- "Antwort auswaehlen und absenden"
- "Woran erkenne ich, dass meine Antwort gesendet wurde?"
- "Was bedeuten Single Choice, Multiple Choice und Freitext?"
- "Warum laeuft der Timer weiter?"

Besonders geeignet:

> Kurzer Guidde-Guide: "An einem Quiz teilnehmen und Antwort abgeben"

## Verbindung zu Barrierefreiheit

Die Befunde haben direkte A11y-Relevanz:

- Auswahlstatus muss nicht nur farblich, sondern auch semantisch erkennbar sein.
- "Antwort gesendet" sollte fuer Screenreader als Statusmeldung ausgegeben werden.
- Der Absenden-Button braucht sichtbaren Tastaturfokus.
- Der Timer darf nicht allein visuell oder stressverstaerkend wirken.
- Bildfragen brauchen Textalternativen und klare Aufgabenanweisungen.

## Priorisierte Verbesserungsideen

### Prioritaet hoch

1. Antwortstatus nach Absenden konsistent und deutlich anzeigen.
2. Absenden-Button und Auswahlstatus in allen Fragetypen klar hervorheben.
3. Timer nach Antwortabgabe erklaeren oder visuell vom Antwortstatus trennen.

### Prioritaet mittel

4. Bildfragen mit klarer Handlungsanweisung versehen.
5. Ergebnisfeedback bei falschen Antworten verstaendlicher machen.
6. Fragetypen und Antwortmoeglichkeiten konsistent beschriften.

### Prioritaet niedrig

7. Team-/Avatar-Auswahl erweitern oder verbessern.
8. Dark-/Light-Mode-Kontraste gezielt vergleichen.

## Formulierung fuer das Referat

> Im Teilnahme-Test zeigte sich, dass der Einstieg ueber den Code bereits sehr gut funktioniert. Die eigentlichen Nutzungshuerden traten erst im Frageflow auf: Die Testperson musste erkennen, welche Aktion erwartet wird, ob eine Antwort ausgewaehlt ist und ob sie erfolgreich abgesendet wurde. Besonders wichtig war dabei klares Systemfeedback. Der Vergleich der beiden Quizdurchlaeufe zeigte, dass sichtbare Auswahlrahmen, ein deutlicher Absenden-Button und eine Statusmeldung wie "Antwort gesendet" die Nutzbarkeit spuerbar verbessern.

## Geeigneter PR-Fokus aus Test 2

Ein guter spaeterer PR-Fokus waere:

> Antwortstatus und Absenden-Feedback im Teilnahmeflow konsistenter und barrierefreier machen.

Warum dieser Fokus stark ist:

- direkt aus zwei Testdurchlaeufen ableitbar
- betrifft zentrale Nutzungssituation von Studierenden
- verbindet Usability und A11y
- gut messbar durch Vorher/Nachher-Test
- mit Guidde-Dokumentation kombinierbar

