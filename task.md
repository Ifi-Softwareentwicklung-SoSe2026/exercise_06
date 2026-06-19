# Aufgabe von Maria an die Studierenden

- Ändere den Link im `README.md` auf dein studentisches Repository, damit der LiaScript-Course-Link auf dein Repository zeigt.
- Füge ein Leeres C# Projekt ein "Baufflächenverwaltung"
- Arbeite dazu in einem eigenen Branch, erstelle eine Pull Request nach `main` und warte auf Reviews von Lisa.
- danach lies die Aufgabe in der `README.md` und arbeite die Aufgabe ab.

# Validierung von Kevins Pull Request (Lisa)

- Die Akzeptanzkriterien in der `README.md` müssen vollständig und korrekt umgesetzt sein.
- Es sollte eine erweiterbare Klassenhierarchie erstellt worden sein, die die Anforderungen an Flächen und Bauvorhaben erfüllt.
- Das Anlegen der Bauvorhaben kann exemplarisch statisch in der `main()`-Methode erfolgen, um die Funktionalität zu demonstrieren. Ein CmdLine Parser ist nicht unbedingt erforderlich.

  - Klassen: `Grundstück`, `Bauvorhaben`, `Antragsteller`
  - Eigenschaften: Alle unter 1. und 2. genannten Attribute
  - Methoden: `FlächeReservieren()`, `BauvorhabenAnlegen()`, `StatusAktualisieren()`

# Issue(s) von Jürgen

- Issue soll nach Merge der Vorheringen Aufgabe triggern
- wir habene essenziel 2 issues in einem dies soll von den Studis gesplitted werden.
- Jürgen redet dabei eher im Plauderton und lobt auch die bisherigen Arbeiten von Kevin und den Studierenden.

## Issue 1: UML Diagramm

- Wenn nicht erfolgt, dann soll ein UML Diagram in die `README.md` zur Klassenstruktur.

## Issue 2: Erweiterung der Funktionalität

- Im weiteren möchte er, dass die Studierenden:
  - Erweiterung der Klassen um Validierungslogik (z. B. Prüfung, ob eine Fläche bereits bebaut ist, bevor sie reserviert wird).
  - Implementierung einer Methode `BebaubarkeitPrüfen()`, die basierend auf B-Plan-Daten die Bebaubarkeit einer Fläche zurückgibt.

# Issue(s) von Jürgen

- Diese Issues werden nach dem ersten Merge von einer der Jürgen-Aufgaben getriggert

- Der Agent gibt fünf weitere Aufgaben vor, die von den Studierenden kategorisiert werden müssen (z. B. nach Priorität, Aufwand, Abhängigkeiten).

  1. **Datenpersistenz:**
     Implementierung von Serialisierung/Deserialisierung (JSON) für Flächen und Bauvorhaben.
  2. **Benutzerverwaltung:**
     Erweiterung um Benutzerrollen (Bauamtsmitarbeiter, Antragsteller, Gutachter) mit Berechtigungen.
  3. **Output:**
     Erstellung einer einfachen Konsolenausgabe, die alle Flächen und deren Status anzeigt.
  4. **Erweiterte Validierung:**
     Prüfung von Bauvorhaben auf Überschneidungen mit Naturschutzgebieten (externe Datenquelle simulieren).
  5. **Dokumentation:**
     Automatische Generierung eines Berichts (Textdatei) mit allen aktiven Bauvorhaben und deren Status.
  6. Das System muss so gestaltet sein, dass neue Validierungsregeln (z. B. für Brandschutz oder Barrierefreiheit) einfach als zusätzliche Methoden oder Klassen hinzugefügt werden können.

- Die Studierenden sollen diese Aufgaben nach Priorität, Aufwand und Abhängigkeiten kategorisieren und entsprechend umsetzen, oder on hold packen.
