# Auswertung Think-Aloud-Test 1

## Test 1: Quizfrage erstellen und bearbeiten

### Testsituation

Rolle der Testperson: Lehrperson

Aufgabe:

> Eine Quizfrage bzw. ein Quiz erstellen, mehrere Fragen anlegen und anschliessend eine Frage bearbeiten.

Ziel der Auswertung:

Die Auswertung betrachtet nicht, ob die Testperson "gut" war, sondern welche Nutzungshuerden in arsnova.eu beobachtbar wurden.

## Kurzfazit

Die Testperson konnte die Aufgabe grundsaetzlich abschliessen, benoetigte aber Orientierung und musste mehrere Funktionen interpretieren. Besonders auffaellig waren:

- unklare Einstiegspunkte zum Erstellen eines Quiz
- missverstaendliche oder erklaerungsbeduerftige Begriffe wie "Quiz starten" und "Blitzlicht"
- Unsicherheit beim Speichern einzelner Fragen vs. des gesamten Quiz
- unklarer Weg zurueck zur Startseite
- Sorge, versehentlich fremde oder bestehende Quizze zu bearbeiten

Damit ist der Test sehr gut als Usability-Nachweis geeignet: Die Probleme sind beobachtbar, wiederholbar und in konkrete Verbesserungen uebersetzbar.

## Beobachtete Befunde

| Nr. | Beobachtung | Qualitaetsproblem | Schweregrad | Moegliche Verbesserung |
|---|---|---|---|---|
| 1 | Die Testperson konnte mit Symbolen auf der Startseite zunaechst nichts anfangen und vermisste Beschriftungen. | Unklare visuelle Orientierung; Icons sind ohne Text nicht selbsterklaerend. | 2 | Icons mit sichtbaren Labels, Tooltips oder klaren Accessible Names versehen. |
| 2 | "Quiz starten" wurde als mehrdeutig empfunden. Die Testperson war unsicher, ob damit ein Quiz erstellt, gestartet oder teilgenommen wird. | Unklare Button-Beschriftung und mentaler Modellbruch. | 3 | Buttontext praezisieren, z. B. "Quiz erstellen", "Quiz praesentieren" oder "Quiz-Sammlung oeffnen". |
| 3 | Der Begriff "Blitzlicht" war unverstaendlich. | Fach-/Projektbegriff ohne Kontext oder Erklaerung. | 2 | Kurzer Hilfetext, Tooltip oder Untertitel, z. B. "Schnelles Stimmungsbild starten". |
| 4 | Die Testperson suchte nach dem Einstieg zur Fragenerstellung, obwohl "Neue Frage" vorhanden war. | Funktion ist vorhanden, aber nicht sofort auffindbar. | 2 | Primaere Aktion "Neue Frage" prominenter platzieren oder nach dem Anlegen eines Quiz klarer fuehren. |
| 5 | Beim Anlegen weiterer Fragen war unklar, ob eine einzelne Frage gespeichert wird oder nur das gesamte Quiz. | Fehlendes bzw. zu allgemeines Systemfeedback beim Speichern. | 3 | Getrennte oder klar beschriftete Speicheraktionen: "Frage speichern" und "Quiz speichern"; sichtbarer Speicherstatus. |
| 6 | Die Testperson fand den Weg zum Anlegen weiterer Fragen zunaechst umstaendlich und suchte nach einem direkteren Weg. | Flow wirkt nicht linear genug; Folgeschritt ist nicht deutlich. | 2 | Nach Speichern einer Frage direkte Folgeaktion anbieten: "Weitere Frage hinzufuegen". |
| 7 | Beim Verlassen des Quiz war unklar, wie man zur Startseite zurueckkommt. | Navigationsstatus und Rueckweg sind nicht eindeutig. | 2 | Breadcrumb, Home-Link oder klarer "Zur Startseite"-Button. |
| 8 | Die Testperson hatte kurz Angst, versehentlich bestehende oder fremde Quizze zu bearbeiten. | Unsicherheit ueber Besitz, Bearbeitungsrechte und Kontext. | 2 | Eigene Quizze klarer kennzeichnen; Bearbeiten-Aktion mit Kontext; ggf. Besitzer/Status anzeigen. |
| 9 | Obere Schnellaktionen wurden als weniger hilfreich empfunden als ein direkter Einstieg in "Quiz erstellen" oder "Uebersicht". | Priorisierung der Startseitenaktionen passt nicht voll zum Nutzerziel. | 2 | Startseite nach Hauptaufgaben strukturieren: "Quiz erstellen", "An Quiz teilnehmen", "Meine Quizze". |

## Staerkste Befunde fuer das Referat

### Befund 1: Unklarer Einstieg in den Erstellungsflow

Beobachtung:

Die Testperson suchte zunaechst nach einem klaren Einstieg zum Erstellen eines Quiz. Die vorhandenen Optionen "Quiz starten", "Q&A oeffnen" und "Blitzlicht starten" wurden nicht eindeutig verstanden.

Qualitaetsproblem:

Der Einstieg bildet nicht klar genug die mentale Aufgabe der Nutzerin ab. Wer "ein Quiz erstellen" moechte, erwartet eine entsprechend benannte Aktion.

Nutzerqualitaetsbezug:

Unklare Einstiegspunkte erhoehen kognitive Last und koennen dazu fuehren, dass neue Nutzerinnen und Nutzer abbrechen oder falsche Bereiche oeffnen.

Moegliche Verbesserung:

Startseitenaktionen klarer nach Nutzerzielen benennen:

- "Quiz erstellen"
- "An Quiz teilnehmen"
- "Meine Quizze"
- "Blitzlicht starten" mit erklaerendem Untertitel

### Befund 2: Unsicherheit beim Speichern

Beobachtung:

Die Testperson war mehrfach unsicher, ob sie eine einzelne Frage oder das gesamte Quiz speichert. Sie suchte nach einem Speicherbutton direkt bei der Frage.

Qualitaetsproblem:

Der Speicherstatus ist nicht eindeutig genug. Der Button "Speichern" sagt nicht, welche Einheit gespeichert wird.

Nutzerqualitaetsbezug:

Unsicherheit beim Speichern ist kritisch, weil sie Angst vor Datenverlust erzeugt und den Bearbeitungsflow verlangsamt.

Moegliche Verbesserung:

- Buttontext konkreter machen: "Frage speichern" oder "Quiz speichern"
- Erfolgsmeldung nach Speichern anzeigen
- Sichtbaren Status verwenden: "Alle Aenderungen gespeichert"
- Bei ungespeicherten Aenderungen vor dem Verlassen warnen

### Befund 3: Fachbegriffe ohne Kontext

Beobachtung:

Der Begriff "Blitzlicht" wurde nicht verstanden. Auch "Quiz starten" wurde als mehrdeutig bewertet.

Qualitaetsproblem:

Projektinterne Begriffe sind fuer neue Nutzerinnen und Nutzer nicht automatisch verstaendlich.

Nutzerqualitaetsbezug:

Unklare Begriffe behindern Orientierung und Lernbarkeit. Das betrifft sowohl Usability als auch didaktische Dokumentation.

Moegliche Verbesserung:

- Kurze Untertitel oder Tooltips
- Guidde-Anleitung mit zentralen Begriffen
- Kontextuelle Hilfe beim ersten Besuch

## Positive Beobachtungen

Die Testperson hat auch positive Aspekte benannt:

- Die Vorschau beim Erstellen einer Frage wurde als hilfreich wahrgenommen.
- Das Design wurde als schlicht, simpel und nicht ueberladend beschrieben.
- Der direkte Code-Einstieg fuer Teilnehmende wurde positiv bewertet.

Diese Punkte sind wichtig, weil sie zeigen: Nicht die gesamte App ist problematisch. Es gibt bereits gute Ansaetze, aber bestimmte Stellen im Flow brauchen mehr Klarheit.

## Verbindung zu didaktischer Dokumentation

Aus dem Test ergeben sich gute Kandidaten fuer Guidde oder kontextuelle Hilfe:

- "Ein Quiz erstellen"
- "Eine Frage hinzufuegen"
- "Eine bestehende Frage bearbeiten"
- "Was bedeutet Blitzlicht?"
- "Woran erkenne ich, dass meine Aenderungen gespeichert sind?"

Besonders sinnvoll waere ein kurzer Guide:

> In 3 Minuten: Quiz erstellen und erste Frage bearbeiten

## Verbindung zu Barrierefreiheit

Einige Usability-Probleme haben direkte A11y-Relevanz:

- Icons ohne erkennbare Beschriftung koennen auch fuer Screenreader-Nutzende problematisch sein.
- Mehrdeutige Buttontexte erschweren die Nutzung mit Screenreader.
- Unklarer Speicherstatus ist fuer blinde Nutzerinnen und Nutzer besonders kritisch, wenn Feedback nur visuell oder gar nicht erfolgt.
- Fehlende eindeutige Navigation erschwert Tastatur- und Screenreader-Flows.

## Priorisierte Verbesserungsideen

### Prioritaet hoch

1. Speicheraktion klarer beschriften oder Speicherstatus sichtbar machen.
2. Startseitenaktion fuer "Quiz erstellen" eindeutiger benennen.

### Prioritaet mittel

3. "Blitzlicht" mit kurzer Erklaerung versehen.
4. Nach dem Speichern einer Frage direkte Folgeaktion "Weitere Frage hinzufuegen" anbieten.
5. Rueckweg zur Startseite klarer machen.

### Prioritaet niedrig

6. Bestehende Quizze klarer nach Besitzer oder Kontext kennzeichnen.
7. Hilfetexte oder Guidde-Link fuer Erstnutzung ergaenzen.

## Formulierung fuer das Referat

> Im Think-Aloud-Test konnte die Testperson die Aufgabe zwar abschliessen, benoetigte aber mehrfach Orientierung. Besonders deutlich wurde die Unsicherheit bei Einstieg, Begriffen und Speicherstatus. Diese Befunde zeigen, dass Nutzerqualitaet nicht nur von vorhandener Funktionalitaet abhaengt, sondern davon, ob Nutzerinnen und Nutzer die Funktion im konkreten Moment verstehen und sicher anwenden koennen.

## Geeigneter PR-Fokus aus diesem Test

Ein sehr guter erster Code- oder Doku-Beitrag waere:

> Speicherstatus und Button-Beschriftungen im Quiz-Editor klarer machen.

Warum dieser Fokus stark ist:

- direkt aus Testbeobachtung ableitbar
- relevant fuer Usability
- relevant fuer A11y, wenn Feedback auch fuer Screenreader verfuegbar gemacht wird
- gut im Referat mit Vorher/Nachher belegbar

