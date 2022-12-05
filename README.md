# Projektdokumentation

Samuel Lucena, Dorian Herzig und Simon Veljkovic

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
| 26.09 | 0.0.1   | Projekt wurde gestartet.|
| 26.09 | 0.0.2   |                                                              |
|       | 1.0.0   |                                                              |

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
| 4.2 | Das Programm wurde gestartet und das Suchsel erstellt |  |  |
| . |  |  |  |

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, die der Testfall abdeckt, und `m` von `1` an nach oben gezählt. Beispiel: Der dritte Testfall, der die zweite User Story abdeckt, hat also die Nummer `2.3`.

### 1.4 Diagramme

✍️ Hier können Sie PAPs, Use Case- und Gantt-Diagramme oder Ähnliches einfügen.

## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  |       |           |              |               |
| ...  |       |           |              |               |

Total: 

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, auf die sich das Arbeitspaket bezieht, und `m` von `A` an nach oben buchstabiert. Beispiel: Das dritte Arbeitspaket, das die zweite User Story betrifft, hat also die Nummer `2.C`.

✍️ Ein Arbeitspaket sollte etwa 45' für eine Person in Anspruch nehmen. Die totale Anzahl Arbeitspakete sollte etwa Folgendem entsprechen: `Anzahl R-Sitzungen` ╳ `Anzahl Gruppenmitglieder` ╳ `4`. Wenn Sie also zu dritt an einem Projekt arbeiten, für welches zwei R-Sitzungen geplant sind, sollten Sie auf `2` ╳ `3` ╳`4` = `24` Arbeitspakete kommen. Sollten Sie merken, dass Sie hier nicht genügend Arbeitspakte haben, denken Sie sich weitere "Kann"-User Stories für Kapitel 1.2 aus.

## 3 Entscheiden

✍️ Dokumentieren Sie hier Ihre Entscheidungen und Annahmen, die Sie im Bezug auf Ihre User Stories und die Implementierung getroffen haben.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  | 26.09 |           |               |                   |
| ...  |       |           |               |                   |

✍️ Tragen Sie jedes Mal, wenn Sie ein Arbeitspaket abschließen, hier ein, wie lang Sie effektiv dafür hatten.

## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

### 5.2 Exploratives Testen

| BR-№ | Ausgangslage | Eingabe | Erwartete Ausgabe | Tatsächliche Ausgabe |
| ---- | ------------ | ------- | ----------------- | -------------------- |
| I    |              |         |                   |                      |
| ...  |              |         |                   |                      |

✍️ Verwenden Sie römische Ziffern für Ihre Bug Reports, also I, II, III, IV etc.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.
