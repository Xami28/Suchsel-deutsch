# Projektdokumentation

Samuel Lucena, Dorian Herzig und Simon Veljkovic

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
| 26.09 | 0.0.1   | Projekt wurde gestartet.|                                    |                  
| 05.12 | 1.0.0   | Projekt wurde beendet.|                                      |

## 1 Informieren

### 1.1 Ihr Projekt

Unser Projekt ist ein Suchsel mit verschiedenen Wortarten.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1    |  Muss           | F    | Als ein User möchte ich, das ich entscheiden kann, welche Wortart mein Suchsel hat.  |
| 2    |  Muss           | F    | Als ein User möchte ich, das ich eine eigene Rastergrösse definieren kann.|
| 3    |  Muss           | F    | Als ein User möchte ich, dass das Programm mir angibt, welche Wörter ich nicht erraten habe.|
| 4    |  Muss           | F    | Als ein User möchte ich, dass ich weiss wann ich ein Wort richtig habe.|
| 5    |  Kann           | F    | Als ein User möchte ich, dass das Programm mir zeigt welche Wörter mir gefählt haben.|
| 6    |  Kann           | Q    | Als ein User möchte ich, dass das Program mir die richtigen Wörter grün anzeigt.|
| 7    |  Kann           | Q    | Als ein User möchte ich, dass das Program mich fragt, ob ich erneut spielen möchte.|


### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1 | Das Programm fragt dich nach der deiner gewählten Wortwahl ab. | "Nomen" | Das Programm giebt das Suchsel aus. |
| 1.2 | Das Programm fragt dich nach der deiner gewählten Wortwahl ab. | "Stein" | Fehlerhafte Eingabe bitte erneut eingeben. |
| 1.3 | Das Programm fragt dich nach der deiner gewählten Wortwahl ab. | "17" | Fehlerhafte Eingabe bitte erneut eingeben. |
| 2.1 | Das Programm fragt dich wie gross das Suchsel sein soll. | "17" | Das Programm fragt die nächst Dimension. |
| 2.2 | Das Programm fragt dich wie gross das Suchsel sein soll. | "Stein" |  Fehlerhafte Eingabe bitte erneut eingeben. |
| 3.1 | Der User hat alle Versuche aufgebraucht. | keine Eingabe | Das Programm zeigt alle gefundene und nicht gefundene Wörter und schaltet ab. |
| 4.1 | Das Programm wurde gestartet und das Suchsel erstellt | richtige Eingabe | Das richtig eingegebene Wort wird Grün im Suchsel angezeigt. |
| 5.1 | Der User hat alle Versuche aufgebraucht. | keine Eingabe | Das Programm zeigt alle gefundene und nicht gefundene Wörter. |
| 6.1 | Der User hat ein Wort richtig eingegeben | Eingabe eines richtigen Worts | Das richtig geschriebene Wort wird nun grün im Suchsel angezeigt. |
| 7.1 | Das Programm ist fertig und fragt ob man nochmal spielen will. | "y"/"n" | Das Programm gibt ein neues suchsel aus oder schliesst sich. |

## 3 Entscheiden

Wir werden anhand unserer User-Stories das Projekt angehen.

## 4 Kontrollieren

### 4.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  | 05.12.2022 | OK | Simon Veljkovic |
| 1.2  | 05.12.2022 | OK | Simon Veljkovic |
| 1.3  | 05.12.2022 | OK | Simon Veljkovic |
| 2.1  | 05.12.2022 | OK | Simon Veljkovic |
| 2.2  | 05.12.2022 | OK | Simon Veljkovic |
| 3.1  | 05.12.2022 | OK | Simon Veljkovic |
| 4.1  | 05.12.2022 | OK | Simon Veljkovic |
| 5.1  | 05.12.2022 | OK | Simon Veljkovic |
| 6.1  | 05.12.2022 | OK | Simon Veljkovic |
| 7.1  | 05.12.2022 | NOK | Simon Veljkovic |
